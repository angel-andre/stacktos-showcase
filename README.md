# Stacktos: Aptor's Ascent

**An Aptos Game.** A one-tap tower climber where Aptor stacks live Aptos transactions as blocks, climbing through six zones to the summit at height 470.

**Play:** coming soon

Stacktos is part of the **Bitcade** series of browser arcade games.

![Stacktos gameplay](docs/gameplay.gif)

![Stacktos](docs/card.png)

## How to play

A plasma launcher below the tower carries each new block back and forth. Tap to fire it up and land it on the tower under Aptor. Any overhang is trimmed off, so the tower narrows; land a block exactly for a **Perfect**, which grows the tower back. Perfect landings build combos, and 5 in a row triggers **Fever** for double Perfect bonuses. Miss the tower and the run is over. Every block is a real, recent Aptos mainnet transaction: transfers, swaps, contract calls and more, with gold blocks for stablecoin transfers.

## The climb

![Six zones to the summit](docs/diagrams/zone-progression.png)

| Zone | Starts at |
| --- | --- |
| Genesis | 0 |
| Mainnet | 60 |
| Parallel Heights | 144 |
| Block-STM Skies | 229 |
| Finality Orbit | 314 |
| Move Nebula | 412 |
| **Summit** | **470** |

| Title | Genesis | Mainnet |
| --- | --- | --- |
| ![Title](docs/screenshots/phone440_title.png) | ![Genesis](docs/screenshots/phone440_genesis.png) | ![Mainnet](docs/screenshots/phone440_mainnet.png) |

| Parallel Heights | Block-STM Skies | Finality Orbit | Move Nebula |
| --- | --- | --- | --- |
| ![Parallel Heights](docs/screenshots/phone440_parallel.png) | ![Block-STM Skies](docs/screenshots/phone440_blockstm.png) | ![Finality Orbit](docs/screenshots/phone440_orbit.png) | ![Move Nebula](docs/screenshots/phone440_nebula.png) |

![All zones](docs/screenshots/zone_strip.png)

## Features

- **Intro cinematic** that sets up Aptor's ascent

  <img src="docs/screenshots/intro.png" alt="Intro" width="480">

- **Live Aptos data**: blocks are real mainnet transactions
- **Daily Climb**: everyone gets the same climb each UTC day, with a daily height goal of 20 to 35 blocks, its own daily leaderboard and a streak counter that never penalizes a missed day
- **Trophies** and **unlockables**
- **Aptos tips with sources** between runs
- **Global leaderboard**
- **Original soundtrack**, one theme per zone

## Soundtrack

- [Title](docs/music/00-title.mp3)
- [Genesis](docs/music/01-genesis.mp3)
- [Mainnet](docs/music/02-mainnet.mp3)
- [Parallel Heights](docs/music/03-parallel-heights.mp3)
- [Block-STM Skies](docs/music/04-block-stm-skies.mp3)
- [Finality Orbit](docs/music/05-finality-orbit.mp3)
- [Move Nebula](docs/music/06-move-nebula.mp3)
- [Build Complete](docs/music/07-build-complete.mp3)

## Architecture

![Architecture](docs/diagrams/architecture.png)

## License

Copyright (c) 2026 Angel Fundora. All rights reserved. Source code is private.
See [LICENSE](LICENSE).
