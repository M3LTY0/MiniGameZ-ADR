# ADR 004 - Local Data Storage

## Status - Accepted

## Context

MiniGameZ may need to retain information between application sessions, such as game progress, high scores, and user preferences. The team needs a storage solution that fits the project's scope.
## Decision
The team will use AsyncStorage to store application data locally on the user's device.
## Consequences
- Allows information to persist between application sessions.
- Does not require a remote database or server.
- Simplifies the application's architecture.
- AsyncStorage is not encrypted by default, so sensitive information should not be stored using this approach.
- The team will need to implement appropriate methods for saving, retrieving, and updating stored information.