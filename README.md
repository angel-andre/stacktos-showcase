# Stacktos: Aptor's Ascent

**An Aptos Game.** A one-tap tower climber where Aptor stacks live Aptos transactions as blocks, climbing through six zones to the summit at height 470.

**Status: in development** (latest build v1.25.0, not launched yet)

Stacktos is part of **Bitcade**, my series of browser arcade games.

![Stacktos gameplay](docs/gameplay.gif)

![Stacktos](docs/card.png)

## Why I'm making it

I'm a community manager at the Aptos Foundation, in crypto since 2021. Explaining how a blockchain works is hard; playing with one is easy. Stacktos turns real Aptos mainnet transactions into the blocks you stack, so every run is a small, fun lesson about the network, with zones named after Aptos ideas like Block-STM, parallel execution and Move.

## Who it's for

Aptos community members and crypto-curious players who want a quick, one-tap game on their phone, and anyone who'd like to learn a little about Aptos along the way.

## The numbers

*As of October 15, 2026:* Stacktos is **in development** and hasn't launched, so there are no player numbers yet. The current build is **v1.25.0**, with **6 zones**, a summit at height **470**, and an **8-track original soundtrack**.

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

## How I'm building it

A phone-first browser game on Cloudflare's edge, with a small serverless backend for live Aptos data and the leaderboards. It builds on what I learned shipping Decicat.

![Architecture](docs/diagrams/architecture.png)

## Design decisions

- **One tap, phone first.** The whole game is a single input, so anyone can play in seconds.
- **Real data as the game.** Blocks are recent mainnet transactions, so the network itself becomes the level.
- **Learning without lecturing.** Zone names and short Aptos tips (with sources) teach a little between runs.
- **A Daily Climb that respects your time.** Same climb for everyone each day, a reachable goal, and a streak that never punishes a missed day.
- **Comeback mechanics.** Perfect landings grow the tower back, so skill is rewarded and runs stay tense.

## What I'm learning

- **Shipping on Cloudflare** and keeping live data fast and reliable.
- **Building in public** with the X community and testing builds with players.
- **Iterating from feedback**: many versions so far, each one tightening feel and pacing.
- **Data accuracy**: showing real network activity faithfully.
- **Privacy and security basics**: no accounts and minimal data.

## License

Copyright (c) 2026 Angel Fundora. All rights reserved. Source code is private.
See [LICENSE](LICENSE).
