Zig Base Agent
==============

Learn zig trying to create a event based loop app
that receive (using polling) tasks, commands, etc.

The idea is create a basic client/agent for distributed client server architecture.

Ag <-> AgHdl

AgHdl send Task, Commands, Queries, Configs to the Ag.

- Tasks: Long term process async
- Command: Short term process sync
- Queries: Short term process with result
- Config: Change some config in the Ag


