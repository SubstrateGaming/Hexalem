# Hexalem

- **Initial Kickof:** 7th November 2023
- **Project Type:** Multiplayer Mobile Fully On-chain Blockchain Game
- **Genre:** Strategy / Godgame
- **Platform:** Android & iOS

# Description

Hexalem is a multiplayer strategy game built on a hexagonal grid, designed to leverage the transparency and immutability of blockchain technology. At its core, the game is a strategic contest where players, acting as deities overseeing their realms, manage resources on a personal 5x5 grid to grow their civilization and harness the mystical energy known as Mana.

Players begin with a central home tile, expanding their territory by strategically placing and upgrading tiles that represent various biomes—each with distinct resource implications. The resources—Mana, Humans, Water, Food, Wood, Stone, and Gold—are not just game mechanics but are integral to the game’s economic system and player progression.

The blockchain aspect is crucial, as it records each move, ensuring a transparent gameplay history and providing a foundation for a trustless gaming environment. The use of blockchain also opens the door for unique game features such as proof of ownership, traceable in-game assets, and the potential for player-driven economies.

The game’s round-based mechanics allow for thoughtful, turn-by-turn gameplay, where players' actions are sequential rather than concurrent for now. This design choice respects the need for strategic planning and decision-making, which is central to the game's experience. The shared tile selection pool introduces an element of shared fate and competition, as players must anticipate and react to the choices of their opponents.

The current version of Hexalem allows players to engage with their grids, yet future updates are poised to expand the scope of interaction. Players will be able to influence their opponents' boards by utilizing mana to cast spells, potentially disrupting resource production or demolishing elemental structures. These strategic maneuvers are designed to provide a competitive edge and advance players toward their goals.

Hexalem distinguishes itself as a strategy-god game, offering an immersive single-player experience while boasting robust multiplayer functionality. The integration of blockchain technology is not merely an added feature but a core aspect of the game's architecture. It introduces a layer for digital ownership and an unbreakable backend, to host thousands of games, establishing Hexalem as a prime candidate for a mobile game first and a candidate to become a UNity Demo game for the Polkadot Unity SDK. The ambition of Hexalem is to explore and expand the frontiers of strategy gaming through the lens of blockchain innovation.

Game Core Loop: Start, Place Tile, Gain Resources, Upgrade Tile, End Turn, and Repeat

# Sync submodules

Use the following command to download the full contents of this repo:

```
git submodule update
```

# Project Structure

- `Substrate.Hexalem.Node` - Substrate Node Template with the custom Hexalem pallet. Provides the on-chain logic.
- `Substrate.Hexalem.NET` - The off-chain logic of the game + logic to combine the on-chain logic with off-chain logic.
- `Substrate.Hexalem.Unity` - UI of the game made in Unity.

[View on IcePanel](https://s.icepanel.io/zWHET9Tj4wybDh/elfG)

# Presentation

- [Polkadot Winter Hackathon 2023 recording of the presentation](https://www.youtube.com/live/_6uUkeI99yQ?si=UWKEnjk0jyGr6xG1&t=7532)
- [Polkadot Winter Hackathon 2023 slides](https://www.canva.com/design/DAF4AVc2_nc/L6IIl1GMuLPskensTYxf3g/edit?utm_content=DAF4AVc2_nc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

# Polkadot Winter Hackathon 2023 Awards

- 1st place in **Building Blockchain Based On Polkadot SDK** category
- 1st place in **Tanssi's favourite team** bounty
- **Best By The Developer's Vote** award

More about the hackathon: https://dorahacks.io/zh/hackathon/polkadot-hackathon-2023-winter/detail

# Team

- Rostislav Litovkin (https://github.com/RostislavLitovkin)
- Romain Friot (https://github.com/Apolixit)
- Cedric Decoster (https://github.com/darkfriend77)
