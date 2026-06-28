# Example Blueprint — Mobile Idle Farming Game

This is a fictional beginner game example.

## Project level

L2 — MVP / Micro Product

## Game concept

A cozy 2D mobile idle farming game where the player plants local crops, waits, harvests, sells, and upgrades a small garden.

## Platform

Android-first prototype.

## Target player

Casual mobile player who wants a relaxing 3-7 minute session.

## Core fantasy

The player slowly builds a peaceful small garden inspired by Indonesian daily life and nature.

## Core loop

```text
Plant crop → wait → harvest → sell → buy upgrade → unlock new crop → repeat
```

## MVP mechanics

Must-have:

- One small farm scene
- Three crops
- One currency
- Plant/harvest interaction
- Simple shop upgrade
- Local save

## Out of scope

Do not build yet:

- Multiplayer
- Cloud save
- Ads
- In-app purchase
- Complex story
- 50 crops
- NPC relationship system

## Scene map

- Main menu
- Farm scene
- Shop panel
- Progress/save indicator

## Asset list

| Asset | Quantity | MVP note |
| --- | --- | --- |
| Farm background | 1 | Simple placeholder OK |
| Crop sprites | 3 | Seed/growing/ready states optional |
| UI buttons | 5 | Plant, harvest, shop, upgrade, save |
| Sound effects | 2 | Optional |

## Suggested toolchain

- Engine: Godot for beginner 2D
- Art: Pixelorama or placeholder shapes first
- Planning: Claude/ChatGPT
- Code help: Cursor/Codex/Claude Code
- Playtest: local APK or itch.io later

## 4-week roadmap

### Week 1

Write GDD, create one farm scene, and place crop slots.

### Week 2

Implement plant/wait/harvest loop.

### Week 3

Add currency, shop upgrade, and local save.

### Week 4

Polish UI, test on device, collect feedback.

## AI prompt starter

```text
Help me build a minimal Godot 2D idle farming prototype.
Scope: one farm scene, three crops, one currency, simple plant/harvest loop, one shop upgrade, and local save.
Do not add ads, multiplayer, cloud save, or complex story.
Explain each step for a beginner.
```

## Resume point

Last done: MVP GDD created.  
Next action: create a Godot project with one farm scene and three crop slots.  
Do not do yet: monetization, cloud save, many crops, complex art.
