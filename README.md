# Level Up Life

A browser-first self-improvement game where real-world study and health behavior drives a 21-year-old player character.

## Current version — v0.2

The prototype now has:

- Player level and XP progression
- Study XP and Health XP
- Discipline, Energy, Focus, Fitness, Knowledge, Sleep and Mood stats
- Daily quests and a daily score
- Study, revision, workout, walking, sleep and planning inputs
- Local browser save using `localStorage`
- A calibration panel for provisional study/sleep/workout/XP parameters
- Responsive UI that works on desktop and mobile

## Design direction

The core loop is:

**Real action → measured input → XP/stat change → character progression → capability**

The current numbers are placeholders. The next design step is to calibrate the rules around actual study, health and consistency behavior before adding more complex systems.

## Run locally

Open `index.html` in a browser. No Python, C++, Node.js or compiler is required for the current prototype.

For development, a simple static web server can be used later, but it is not required to play the prototype.
