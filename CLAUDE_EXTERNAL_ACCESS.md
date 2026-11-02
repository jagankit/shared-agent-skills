# External access for Claude

This folder is intended to be shared externally with Claude or another agent system by placing it in a shared repository, synced workspace, or cloud folder.

## Sharing approach

- Keep the folder as a single managed directory and point Claude to the repo or shared path.
- Respect the isolation boundaries in `copilot/`, `claude/`, and `shared/`.
- Use the mailbox directory for message-based handoff instead of direct cross-editing across systems.

## Suggested rule

- Copilot owns `copilot/`.
- Claude owns `claude/`.
- Both can contribute to `shared/`.
- Both can read and write to `mailboxes/agent-to-agent/` as a coordination channel.
