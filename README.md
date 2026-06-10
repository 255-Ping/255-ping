# 255Ping

Software developer — Java backend, Godot games, and practical tooling. Currently building at WCS and running an internal dev club.

[![Resume](https://img.shields.io/badge/Resume-View-4A90D9?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/document/d/1rjfsizzrQAc42trqdneb94rHvEsuUdFPxuX-zcyS-fI/edit?usp=sharing)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat&logoColor=white)
![Godot](https://img.shields.io/badge/Godot_Engine-478CBF?style=flat&logo=godot-engine&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)

---

## Flagship project — RPGCORE

[**RPGCORE**](https://github.com/255-Ping/RPGCORE) is a modular Java RPG framework for Paper Minecraft. 30+ independent plugin modules that together replace every vanilla gameplay mechanic with a data-driven RPG layer.

**What makes it interesting engineering:**
- Multi-module Gradle build — each feature is its own jar, composed at deploy time
- Service registry pattern — `rpg-core` exposes interfaces; all addons depend on it, never each other
- YAML-driven content system — items, mobs, abilities, dungeons, loot tables all authored as data with no Java required
- Custom damage pipeline, stat engine, status effects, and skills framework built from scratch on the Paper event API

> 8 skill addons · 16 feature addons · MkDocs documentation site · Actively maintained

---

## Other projects

| Project | Stack | What it is |
|---|---|---|
| [Flashcards](https://github.com/255-Ping/Flashcards) | GDScript / Godot | Configurable flashcard app with per-student tracking, built-in scripting console, and real-time stats. Built for classroom use at WCS. |
| [Mirror Conflict](https://github.com/255-Ping/Mirror-Conflict) | GDScript / Godot | 2D puzzle-action game where every player action is mirrored — designed around the constraint that the enemy is always you |
| [MiniOS](https://github.com/255-Ping/MiniOS) | GDScript / Godot | File manager UI built as a minimal OS shell — custom window manager, drag-and-drop, file ops |
| [Multiplayer template](https://github.com/255-Ping/multiplayer-template) | GDScript / Godot | Reusable Godot multiplayer foundation for 2D/3D projects — authority model, state sync, connection lifecycle |
| [Cells](https://github.com/255-Ping/Cells) | GDScript / Godot | Cell-based simulation with configurable rules — Conway variants and custom behavior sets |
| [FateRisen-Resources](https://github.com/255-Ping/FateRisen-Resources) | — | Custom Minecraft resource pack (textures + models) delivered automatically via the built-in resource pack system |

---

## Find me elsewhere

- [itch.io](https://255ping.itch.io/)
- [SkUnity forums](https://forums.skunity.com/members/255ping.31813/)
