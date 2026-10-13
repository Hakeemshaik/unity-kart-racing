# Kart Racing (Unity)

A kart racing game with three race modes (beginner, advanced and checkpoint), AI opponents, story dialogue between races and spectators around the track.

## What I built
- **AI racers on waypoints**: `Agent.cs` follows a linked list of waypoints so racers always know the next target on the track.
- **Factory pattern**: `RacerFactory` / `AIRacerFactory` spawn racers with different appearances and speeds.
- **Race logic**: `RacecourseManager`, `CheckpointRaceManager` and `CheckpointTrigger` handle laps, checkpoints and results.
- **Audio system**: `SfxManager` with a custom hash map for fast sound lookup.
- **Narrative**: dialogue scenes and triggers before each race, with skip support.

## Scenes
`main menu` → `Beginner Race` / `Advanced Race` / `CheckpointRace`, each with a dialogue scene.

## Run it
Open in **Unity 2022.3.7f1** and start from `Assets/Scenes/main menu.unity`.

Track and kart art uses free Asset Store packs (MgKarting Racetrack, BEDRILL Modular Track); the gameplay code is my own.

---
Built by **Hakeem Shaik** during my BSc (game development modules). See my AI work: [Pursuit](https://github.com/Hakeemshaik/pursuit-ai-job-agent) · [Fitted](https://github.com/Hakeemshaik/fitted) · [Boom & Crash Desk](https://github.com/Hakeemshaik/boom-crash-desk)
