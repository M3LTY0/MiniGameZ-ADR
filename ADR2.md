# ADR 002 - Navigation Strategy

## Status - Proposed

## Context

MiniGamez will contain multiple screens, including menus and individual game screens. Users need a consistent way to navigate between these screens without making the application difficult to use.
## Decision
The team has chosen to use Expo Router to handle navigation through the application. 
## Consequences
- Provides a consistent navigation structure across the application.
- Allows new screens and games to be easily added as additional files as the project expands.
- Changes to the application's directory structure may affect navigation routes.
