# Mailbox directory

This directory is reserved for agent-to-agent communication and message handoff storage.

## Layout

- `agent-to-agent/inbox/` - messages received by the current agent
- `agent-to-agent/sent/` - messages sent from the current agent

The repo also includes the mailbox implementation in `scripts/mailbox_exchange.py` for a lightweight JSON-based message store.
