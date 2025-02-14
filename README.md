# Skyrim AI Companion Mod

## Overview
This project aims to create an advanced AI-powered companion for Skyrim using modern machine learning frameworks. The companion will intelligently interact with the player, make decisions in combat, and adapt to different playstyles.

## Features
- **AI Decision Making**: The companion will use reinforcement learning to make combat and survival decisions.
- **SKSE Integration**: A custom SKSE plugin will extract game state data.
- **Machine Learning**: The AI model will be trained using PyTorch/Stable-Baselines3.
- **Modular Design**: The AI logic will be separate from the game logic to allow future expansion.

## How It Works
1. **Game State Extraction** - The SKSE plugin gathers real-time data (player health, enemy positions, etc.).
2. **AI Processing** - The data is sent to a machine learning model, which decides the best action.
3. **Game Execution** - The AI decision is sent back to Skyrim and executed via scripts.

## Repository Structure
```
📂 skyrim-ai-companion
│-- 📂 skse_plugin         # SKSE plugin source code
│-- 📂 ai_model            # AI training scripts and models
│-- 📂 game_scripts        # Papyrus scripts for in-game execution
│-- 📂 data_exchange       # Files/sockets for AI-game communication
│-- 📜 README.md           # Project documentation
│-- 📜 requirements.txt    # Dependencies for AI components
```

## Getting Started
### Requirements
- **Skyrim Special/Anniversary Edition**
- **SKSE (Skyrim Script Extender)**
- **Visual Studio + CommonLibSSE** (for plugin development)
- **Python + PyTorch** (for AI training)

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB/skyrim-ai-companion.git
   ```
2. Install dependencies (Python & SKSE plugin tools).
3. Run the SKSE plugin to extract game state.
4. Train the AI model using provided scripts.
5. Launch Skyrim and test the AI-driven companion.

## Contributing
We welcome contributions! Check out our [Issues](https://github.com/RJL3m0s/skyrim-ai-companion/issues) for open tasks.

### To Contribute:
- Fork the repo
- Create a new branch (`feature-your-feature`)
- Submit a Pull Request (PR)

## Roadmap
- [ ] Implement basic SKSE plugin
- [ ] Set up AI model training
- [ ] Create AI behavior scripts
- [ ] Optimize for real-time decision making

## Open Issues & Tasks
### SKSE Plugin Development
- [ ] Create an SKSE plugin that extracts player health and position
- [ ] Implement enemy detection and combat status logging
- [ ] Set up a communication bridge between the AI model and the game

### AI Model Training
- [ ] Develop a reinforcement learning model for NPC decision-making
- [ ] Train AI to adapt to different player combat styles
- [ ] Optimize AI performance for real-time decision making

### Game Integration
- [ ] Implement AI action execution in Skyrim using Papyrus scripts
- [ ] Test AI behavior in combat and exploration scenarios
- [ ] Debug and refine AI responses to dynamic in-game events

## Community & Support
Join our Discord for discussions: **[Discord Invite Link]**

