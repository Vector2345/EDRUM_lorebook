# EDRUM_lorebook

A SillyTavern WorldInfo lorebook for an original high fantasy RPG setting — **Ederum**.

## About

Ederum is a high fantasy world featuring two rival empires, complex morality, and a first-person narrative system. Built for immersive TTRPG-style play with real consequences.

Developed over iterative testing sessions with assistance from Claude (Anthropic).

## Features

- 33 WorldInfo entries with keyword triggers
- DO / SAY / STORY command system
- d20 dice mechanics
- Faction-aware NPC knowledge system
- Legal system with consequences — arrest, trial, execution
- Three different prison systems per race
- Class determination through player behavior

## Recommended Model

**L3-8B-Stheno-v3.2-Q4_K_M**

Tested and optimized for this model. Other roleplay-focused models should work but are untested.

## Files

| File | Description |
|------|-------------|
| `edrum_worldinfo_v6b.json` | Main WorldInfo lorebook |
| `edrum_system_prompt_v4.txt` | System prompt |
| `edrum_prompt_v7.txt` | Main prompt |
| `edrum_first_message.txt` | Opening message |
| `Default.json` | Sampler settings — temperature, penalties, generation parameters |
| `ST-formatting-2026-03-01.json` | SillyTavern response format settings |

## Setup

1. Import `edrum_worldinfo_v6b.json` into SillyTavern WorldInfo
2. Load `edrum_system_prompt_v4.txt` as system prompt
3. Load `edrum_prompt_v7.txt` as main prompt
4. Use `edrum_first_message.txt` as opening message
5. Import `Default.json` into your sampler settings
6. Import `ST-formatting-2026-03-01.json` into SillyTavern formatting settings

## Commands

- `DO [action]` — physical action
- `SAY "[dialogue]"` — speak to NPC
- `STORY [reflection]` — inner narrative or time skip

## License

GNU General Public License v2.0
