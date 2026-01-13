# Roblox Leaderstats – Server-Side Score System

## Overview
This project implements a basic leaderstats system in Roblox Studio (Lua/Luau) using server-side scripting.
It demonstrates how to initialize player data on join, store numeric values using IntValue, and expose them automatically through Roblox’s built-in leaderboard UI.

---

## Technical Goals
- Implement leaderstats following Roblox engine conventions
- Manage player-scoped data using Roblox Instances
- Demonstrate server-authoritative score handling
- Provide a minimal and extensible foundation for score-based systems

---

## Core Concepts Covered
- Players.PlayerAdded event
- Instance creation with Instance.new
- Folder usage for leaderboard binding
- Numeric state storage using IntValue
- Runtime debugging with print()
- Server execution via ServerScriptService

---
All logic runs on the server
No client-side mutation of score values
Uses Roblox’s automatic UI binding to leaderstats

##Implementation Flow
Player joins the server
A Folder named leaderstats is created and parented to the Player
An IntValue (e.g. Points) is added to leaderstats
Roblox detects leaderstats and renders it in the leaderboard UI
Score updates are reflected in real time

## Example Use Cases
Score and currency systems
Educational projects
Prototyping XP, kills, or progression systems
Base structure for DataStore persistence

## Extensibility
DataStoreService integration
Event-driven score updates
Multiple tracked stats (XP, Kills, Level)
Anti-exploit validation
Custom UI with ScreenGui

## Requirements
Roblox Studio
Basic knowledge of Lua/Luau
Understanding of client vs server execution

## Notes
This project intentionally avoids UI scripting and persistence to keep the focus on core engine behavior and clean server-side design.
## Architecture

```text
ServerScriptService
└── Leaderstats (Script)

