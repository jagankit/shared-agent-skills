# Agent-to-agent mailbox

This mailbox directory provides a local exchange point for simple agent messaging.

## Folders

- `inbox/` - incoming messages
- `sent/` - outgoing messages

## Working model

- messages are stored as JSON files when sent
- each agent can read incoming messages and mark them as read
- the script in `scripts/mailbox_exchange.py` provides the implementation logic

This isolates message transport from direct browser-based auth flows.
