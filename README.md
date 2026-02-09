# Crypto Beach Soccer

![Crypto Beach Soccer Banner](./client/public/textures/banner.png)

> A 3D web-based soccer game combining blockchain culture with competitive beach sports. Play as cryptocurrency characters in fast-paced matches with physics-based gameplay and Web3 authentication.

[![Play Now](https://img.shields.io/badge/Play-Online-brightgreen)](https://crypto-beach-soccer.netlify.app/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Quick Start](#quick-start)
- [Installation](#installation)
- [Gameplay Guide](#gameplay-guide)
- [Technical Stack](#technical-stack)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

**Crypto Beach Soccer** is a 3D web-based soccer game that combines blockchain culture with competitive beach sports. Players control cryptocurrency-themed characters (Bitcoin, Ethereum, Dogecoin, PepeCoin) in fast-paced matches set in a tropical beach environment.

Built with modern web technologies including Three.js for 3D rendering, React for the user interface, TypeScript for type safety, and Web3 authentication via Orange ID. The game features physics-based gameplay mechanics, character-specific abilities, and cross-platform compatibility.

### Key Highlights

- **Physics-Based Gameplay**: Realistic ball physics and character interactions
- **Web3 Integration**: Secure authentication with Orange ID
- **Cross-Platform**: Optimized for desktop, mobile, and tablet
- **3D Graphics**: Immersive beach environment with detailed visuals
- **Character Abilities**: Unique special abilities for each cryptocurrency character

---

## Features

### Gameplay Features
- **Cryptocurrency Characters**: Play as Bitcoin (BTC), Ethereum (ETH), Dogecoin (DOGE), or PepeCoin (PEPE)
- **3D Character Models**: Additional characters including Giga Chad and Beach Baddy
- **Character Abilities**: Each character features unique special abilities based on their cryptocurrency identity
- **AI Opponent**: Single-player mode with intelligent AI for competitive matches
- **Physics Engine**: Realistic ball physics and character movement powered by Cannon.js

### Technical Features
- **Web3 Authentication**: Secure authentication via Orange ID (Google, Apple, Web3 wallets)
- **3D Beach Environment**: Immersive tropical beach field with detailed graphics
- **Cross-Platform Support**: Responsive design for desktop, mobile, and tablet devices
- **Multiple Control Schemes**: Keyboard controls for desktop, touch controls for mobile
- **Real-Time Physics**: Advanced physics simulation for realistic gameplay

---

## Quick Start

### Play Online

The easiest way to play is directly in your browser:

**[Play Crypto Beach Soccer Now](https://crypto-beach-soccer.netlify.app/)**

No installation required - just open the link and start playing!

### Local Development

See [Installation](#installation) section for detailed setup instructions.

---

## Installation

### Prerequisites

- **Node.js** (v16 or higher)
- **npm** or **yarn** package manager

### Step 1: Clone the Repository

```bash
git clone https://github.com/crypto-beach-soccer/crypto-beach-soccer.git
cd crypto-beach-soccer
```

### Step 2: Install Dependencies

Install dependencies for both client and server:

```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

### Step 3: Start Development Servers

Start both client and server in separate terminals:

```bash
# Terminal 1 - Start client
cd client
npm run dev

# Terminal 2 - Start server
cd server
npm run dev
```

### Step 4: Access the Application

Open your browser and navigate to:
```
http://localhost:5173
```

---

## Gameplay Guide

### Controls

#### Desktop Controls
- **Movement**: `WASD` keys or `Arrow` keys
- **Jump**: `SHIFT` key
- **Kick**: `SPACEBAR`
- **Ability**: `E` key
- **Restart**: `R` key

#### Mobile Controls
- **Movement**: On-screen directional buttons
- **Jump**: Jump button
- **Kick**: Kick button
- **Ability**: Special ability button

### Playable Characters

#### Cryptocurrency Characters

1. **Bitcoin (BTC)**
   - **Ability**: HODL - The Diamond Hands Upgrade
   - **Effect**: Increases kick power (150%) and ball control radius
   - **Duration**: 7 seconds

2. **Ethereum (ETH)**
   - **Ability**: Smart Contract - Gas Fee Turbocharger
   - **Effect**: Enhances jump height (150%) and provides 50% speed boost
   - **Duration**: 7 seconds

3. **Dogecoin (DOGE)**
   - **Ability**: To The Moon - Lunar Gravity Edition
   - **Effect**: Grants temporary invincibility, 120% speed boost, and enhanced kicking
   - **Duration**: 5 seconds

4. **PepeCoin (PEPE)**
   - **Ability**: Meme Magic - The Rare Pepe Power
   - **Effect**: Enhances ALL abilities by 80%
   - **Duration**: 6 seconds

#### 3D Character Models

5. **Giga Chad**
   - **Ability**: Womanizer
   - **Effect**: Makes opponents magnetically attracted for 3 seconds
   - **Duration**: 3 seconds

6. **Beach Baddy**
   - **Ability**: Captivating Presence
   - **Effect**: Freezes opponents in place for 2 seconds
   - **Duration**: 2 seconds

### Game Rules

1. **Match Duration**: Matches last 3 minutes - player with most goals wins
2. **Ability Cooldown**: Special abilities recharge after 12-15 seconds
3. **Power-ups**: Appear on the field periodically (15-30 seconds)
4. **Ball Reset**: Press `R` to reset the ball if it gets stuck
5. **Field Boundaries**: Stay within the field boundaries to maintain control

### Strategy Tips

1. **Power-up Collection**: Collect glowing coin power-ups for temporary boosts
2. **Ability Timing**: Save special abilities for critical scoring or defensive moments
3. **Ball Control**: Position yourself properly before kicking to aim accurately
4. **Field Positioning**: Maintain good field coverage without straying too far from center
5. **Jump Shots**: Use jump kicks for higher trajectories to clear opponent blocks
6. **Character Selection**: Choose characters based on your playstyle preferences

### Authentication

Crypto Beach Soccer integrates with Orange ID Web3 authentication:

- Sign in with Google or Apple accounts
- Connect Web3 wallets (coming soon)
- Save game progress across devices (coming soon)
- Play as guest without signing in
- View Orange ID profile within the game

---

## Technical Stack

### Core Technologies

- **Three.js** - 3D rendering and animations
- **Cannon.js** - Physics engine for realistic ball movement
- **React** - UI components and game structure
- **TypeScript** - Type-safe code
- **Zustand** - State management

### Additional Technologies

- **WebSocket** - For future multiplayer implementation
- **Orange ID SDK** - Web3 authentication integration
- **Vite** - Build tool and development server
- **Express** - Backend server framework

### Development Tools

- **ESBuild** - Fast bundler for production builds
- **Drizzle ORM** - Database toolkit
- **PostCSS** - CSS processing
- **Tailwind CSS** - Utility-first CSS framework

---

## Project Structure

```
crypto-beach-soccer/
├── client/                 # Frontend application
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── game/          # Game logic and components
│   │   ├── auth/          # Authentication components
│   │   └── lib/           # Utilities and stores
│   ├── public/            # Static assets
│   └── package.json
├── server/                # Backend server
│   ├── index.ts          # Server entry point
│   └── routes/           # API routes
├── shared/               # Shared types and utilities
├── package.json          # Root package.json
└── README.md
```

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For inquiries, support, or collaboration opportunities:

- **Telegram**: [@borysdraxen](https://t.me/borysdraxen)
- **Live Game**: [https://crypto-beach-soccer.netlify.app/](https://crypto-beach-soccer.netlify.app/)

---

## Acknowledgements

- Crypto community for inspiration
- Three.js community for resources and documentation
- Orange ID team for authentication SDK
- All contributors and playtesters

---

<div align="center">

Made with code | © 2025 Crypto Beach Soccer

[Play Now](https://crypto-beach-soccer.netlify.app/) • [Contact](https://t.me/borysdraxen)

</div>
