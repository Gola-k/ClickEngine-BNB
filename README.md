### Vision

ClickEngine envisions a world where game development is accessible to everyone, regardless of their technical background. Our goal is to empower creators, from hobbyists to professionals, by providing a no-code, open-source platform that simplifies the entire game development process. By integrating with Internet Computer's Chain Fusion technology, we aim to create a secure, transparent, and efficient environment for managing digital assets and transactions across multiple blockchains. Our ultimate vision is to democratize game development and foster a community where creativity knows no bounds.

### Description

#### Project Overview

ClickEngine is a cutting-edge, no-code, open-source game development software designed to make game creation accessible to everyone. Whether you're building games for mobile, desktop, or web, ClickEngine offers an intuitive and powerful event-based system that simplifies the process. ClickEngine leverages Internet Computer's Chain Fusion technology to handle all transactions, including creating assets or templates as NFTs, buying and selling these assets, and purchasing published ClickEngine games from the ClickEngine store. All smart contracts are deployed on the Internet Computer, ensuring a secure and seamless transaction experience.

#### Key Features

- *No-Code Game Development*: ClickEngine enables users to develop games without any coding skills. Its user-friendly interface and event-based system allow for fast and easy game logic creation.
- *Multi-Platform Support*: Create games for mobile, desktop, and web platforms with ease, ensuring your creations reach a wide audience.
- *Chain Fusion Integration*: ClickEngine integrates seamlessly with Internet Computer's Chain Fusion technology, allowing for secure transactions and management of digital assets, including NFTs and in-game purchases.
- *Full-Featured Development Environment*: The platform includes a robust game editor built with React, Electron, and PixiJS, offering a comprehensive suite of tools for game development.
- *Open Source and Extensible*: ClickEngine is open-source, promoting collaboration and customization. It includes a variety of extensions to enhance the game engine's capabilities, from objects and behaviors to new features.
- *Secure and Transparent Transactions*: By utilizing Chain Fusion technology, ClickEngine ensures all transactions within the platform are secure, transparent, and efficient.

#### Architecture Overview

ClickEngine is built around several key components:

- *Core Library*: The ClickEngine core library provides essential tools to implement the IDE and manage ClickEngine games.
- *GDJS (Game Engine)*: The game engine, written in TypeScript, uses PixiJS for rendering and powers all ClickEngine games.
- *ClickEngine.js Bindings*: These bindings integrate Core, GDJS, and Extensions into JavaScript, utilizing WebAssembly for efficient performance.
- *newIDE (Game Editor)*: The game editor, built with React, Electron, and PixiJS, provides a robust environment for game development.
- *Extensions*: A collection of extensions that add objects, behaviors, events, and new features to the game engine, enhancing its capabilities.

#### Chain Fusion Integration

Chain Fusion is Internet Computer's innovative technology that allows seamless multichain integration without the need for bridges, oracles, or intermediary services. Key features include:

- *Direct EVM Interaction*: ICP canister smart contracts can sign Ethereum transactions and interact with EVM RPC providers directly via HTTPS Outcalls.
- *Secure and Efficient Transactions*: Utilizing Chain Fusion ensures that all transactions within ClickEngine are secure and efficient.
- *Multichain Asset Management*: Easily manage digital assets across multiple blockchains, including ckBTC and ckETH tokens.

ClickEngine's integration with Chain Fusion allows for seamless handling of game-related transactions, from creating and managing NFT assets to purchasing games from the ClickEngine store.

#### Vision for the Future

As we continue to develop ClickEngine, our vision is to expand its capabilities and make game development even more accessible. We plan to introduce more extensions, enhance our integration with the Internet Computer ecosystem, and build a thriving community of game developers. Our mission is to lower the barriers to entry in game development, enabling creators from all backgrounds to bring their ideas to life and monetize their creations effectively. Join us on this journey to revolutionize game development with ClickEngine!



ClickEngine is a full-featured, no-code, open-source game development software. You can build games for mobile, desktop and the web. ClickEngine is fast and easy to use: the game logic is built up using an intuitive and powerful event-based system.

## Open the netlify link here

[ClickEngine-Netlify](https://66af2aebfe7aad5bc52183ba--dancing-tartufo-bb6b0e.netlify.app/)

## Overview of the architecture

| Directory        | ℹ️ Description                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------- |
| `Core`           | ClickEngine core library, containing common tools to implement the IDE and work with ClickEngine games. |
| `GDJS`           | The game engine, written in TypeScript, using PixiJS (WebGL), powering all ClickEngine games.           |
| `ClickEngine.js` | Bindings of `Core`, `GDJS` and `Extensions` to JavaScript (with WebAssembly), used by the IDE.          |
| `newIDE`         | The game editor, written in JavaScript with React, Electron and PixiJS.                                 |
| `Extensions`     | Extensions for the game engine, providing objects, behaviors, events and new features.                  |

To learn more about ClickEngine Architecture, read the [architecture overview here](Core/ClickEngine-Architecture-Overview.md).

Pre-generated documentation of the Core library, C++ and TypeScript game engines is [available here](https://docs.ClickEngine.io).

Status of the tests and builds: [![Windows Build status](https://ci.appveyor.com/api/projects/status/84uhtdox47xp422x/branch/master?svg=true)](https://ci.appveyor.com/project/4ian/ClickEngine/branch/master) [![https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation)

## License

- The Core library, the native and HTML5 game engines, the IDE, and all extensions (respectively `Core`, `GDJS`, `newIDE` and `Extensions` folders) are under the **MIT license**.
- The name, ClickEngine, and its logo are the exclusive property of Florian Rival.

Games exported with ClickEngine are based on the GDevelop game engine (see `Core` and `GDJS` folders): this engine is distributed under the MIT license so that you can **distribute, sell or do anything** with the games you created with GDevelop. In particular, you are not forced to make your game open-source.

[node.js]: https://nodejs.org

### Credits for GDJS Game Engine: GDevelop
