# LifePaws
The program provides a virtual pet so users can experience pet ownership without real-life costs or restrictions. It includes interactive care tasks such as feeding, playing, and cleaning to help users practice responsibility while building an emotional connection through the pet’s moods and reactions. 
# LifePaws
The program provides a virtual pet so users can experience pet ownership without real-life costs or restrictions. It includes interactive care tasks such as feeding, playing, and cleaning to help users practice responsibility while building an emotional connection through the pet’s moods and reactions. 
# LifePaws 🐾

LifePaws is a browser-based virtual pet simulator designed to teach real-life pet care habits through gameplay. Players adopt and customize a pet, manage health-related stats, budget money for care, play mini-games, and build long-term responsibility skills.

## Project goal

LifePaws exists for people who cannot keep a real pet because of cost, allergies, housing limits, or time constraints. The game translates pet ownership into an interactive simulation focused on:

- daily care routines
- budgeting and planning
- time management
- consistency and accountability

## What is included in this project

This repository currently contains:

- `README.md` (project documentation)
- `Source Code` (single-file HTML/CSS/JS implementation of the full game)

## Core gameplay systems

The current game implementation in `Source Code` includes:

### 1) Onboarding and help
- Startup directions overlay with clear play instructions
- Built-in Q&A helper for common player questions

### 2) Pet setup and customization
- Pet type selection
- Color theme options
- Accessory selection
- Name input and difficulty selection

### 3) Pet life simulation
- Main stats management (e.g., happiness, hunger, health, energy, hygiene, social)
- Mood/condition feedback and loss conditions
- Leveling + XP progression
- Turn-based lifecycle updates

### 4) Actions and care loop
- Multiple pet-care activities (feeding, playing, resting, bathing, vet visits, grooming, etc.)
- Challenge-based interactions (timing and mash-style mechanics)
- Costed actions for realistic resource tradeoffs

### 5) Economy and progression
- Wallet/currency and spending tracking
- Chores for earning money
- Shop purchases for stat boosts and utility
- Wealth chart and money-focused dashboard elements

### 6) Games and side activities
- Arcade-style mini-games, including:
  - Tic Tac Toe
  - 8-Ball
  - HORSE Shootout
  - Snake
- Rewards tied into main progression

### 7) Achievements and milestones
- Badge unlock system
- Care streaks
- Event/history tracking
- End-of-run summary screen

### 8) Interface architecture
- Multi-tab layout (Home, Life, Games, Skills, Money)
- Modal-driven actions (shop, chores, badges, settings, mini-games)
- Animated, mobile-friendly UI styling and transitions

## How to run locally

Because the app is written as a single HTML file, you can run it in two simple ways:

### Option A: Open directly
1. Rename `Source Code` to `index.html` (optional but recommended).
2. Open the file in a modern browser.

### Option B: Serve with a local HTTP server (recommended)
From the project root:

```bash
python3 -m http.server 8080
```

Then open:

- `http://localhost:8080/`

If you keep the filename as `Source Code`, navigate directly to that file path in your browser.

## Recommended repository cleanup (future)

To make collaboration easier, consider reorganizing into:

```text
LifePaws/
  README.md
  index.html
  assets/
    css/
    js/
    images/
```

This is optional, but splitting HTML/CSS/JS into separate files will improve maintainability and version control diffs.

## Contribution notes

If you continue development, prioritize:

- separating inline CSS/JS into dedicated files
- adding basic linting/formatting
- adding lightweight tests for core game logic (stat updates, economy math, win/loss checks)
- documenting feature changes in this README

---

LifePaws is both a game and a learning tool: fun pet simulation with practical responsibility training.
