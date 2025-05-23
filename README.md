# PokéSharp (Educational Purpose Only)

> This project is a **non-commercial, educational clone** of the original Pokémon games, developed purely to demonstrate how such a game can be implemented from scratch using C#.

## Purpose

This project wasn't originally intended for the public and its main aim was to teach me how to develop and finish a project from start to finish, as I often tend not to finish what I start. I set myself the rather crazy challenge of recreating a clone of the Pokémon game in 48 hours of pure work, and I think I can consider that I succeeded in this challenge. 
Today I've decided to publish the repository in order to share with you a project I'm quite proud of and to allow the community to potentially learn from it. But as you can imagine, we can't reach the moon in 48 hours of work, which is why there's still a lot of work to do.

For the future of this project, I'd like to create an active community that will help me and enable me to create a stable project that will aim to understand and learn how to make a similar project.

> pls Nintendo don't sue me.

It is **not affiliated with Nintendo, Game Freak, or The Pokémon Company**, and is not intended for commercial distribution or public gameplay.

For the moment, none of the game's assets are hosted on the repository in order to avoid any copyright problems. See the Getting Started section for further informations

---

## Screenshots

### Gameplay
![Player walking in zone](assets/overworld.png)

### Wild Battle
![Wild battle system](assets/battle.png)

### NPC Dialogue
![NPC system with patrol and interaction](assets/npcs.png)

---

## Game Features

- **Player Movement**: Classic top-down 2D grid-based movement.
- **NPCs**:
  - Patrol behavior
  - Dialogue interaction system
- **Creatures**:
  - Battle system with health, damage, and stats
  - Element types (Fire, Water, Dragon, etc.) similar to the original games
  - Movement and turn-based attacks
- **Wild Battles**:
  - Triggered when walking on tall grasses

---

## Engine Features

- **Coroutine System**: Custom lightweight coroutine implementation for asynchronous flow.
- **Tweening System**: Smooth movement/animation handling via coroutine-driven tweening.
- **Screen Manager**: Handles transitions and screen stack management.
- **Tiled Integration**:
  - Loads maps and entities using the [Tiled Map Editor](https://www.mapeditor.org/)
- **Animation System**: Frame-based sprite animations with custom animation controller.

---

## Disclaimer

This project:
- Is **strictly for educational use**
- **Is not for sale or monetized** in any way
- Will **never be used in a commercial context**
- May be taken down at any time upon request by the rightful copyright holders

If you are a rights holder and have any concerns, please [open an issue](https://github.com/) or contact me directly.

---

## Getting Started
For the moment, none of the game's assets are hosted on the repository in order to avoid any copyright problems. This will prevent you from generating and launching the project on your local machine.  

I'm currently working on a ROM loader that will extract the game assets at runtime from your ROM (that you of course have to own :)) in order to solve this issue.

---

## License

This project is not licensed for redistribution or commercial use. It is shared solely for educational demonstration under fair use assumptions.
