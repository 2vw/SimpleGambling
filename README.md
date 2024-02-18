# SimpleGambling

## Description
A discord.py bot created for the sole purpose of gamblnig

## Table of Contents
- [Features](#features)
- [Commands](#commands)
- [Setup](#setup)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features
- Roulette
- Built in Leaderboard
- PyMongo Supported
- Discord.py Coded
- Gambling 🤑

## Commands
### 1. !roulette
   - Description: Place bets on the roulette wheel.
   - Usage: `!roulette <bet_type> <bet_amount>`
   - Example: `!roulette red 50`

### 2. !spin
   - Description: Spin the roulette wheel and determine winners and losers.
   - Usage: `!spin`
   - Example: `!spin`

### 3. !leaderboard
   - Description: Display the biggest winners or losers in the roulette game.
   - Usage: `!leaderboard [winners/losers] [limit]`
   - Example: `!leaderboard winners 5`

### 4. !blackjack
   - Description: Play a game of blackjack against the bot.
   - Usage: `!blackjack <bet_amount>`
   - Example: `!blackjack 100`

## Setup
1. Clone the repository: `git clone https://github.com/your-username/your-bot-repo.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your MongoDB database and update the URI in the code.
4. Obtain your Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications).
5. Replace `'YOUR_BOT_TOKEN'` in the code with your actual bot token.
6. Run the bot: `python bot.py`

## Usage
Provide instructions on how to use your Discord bot and any additional information users might need.

## Dependencies
List the main dependencies your bot relies on.

## Contributing
If you'd like to contribute to the project, please follow the [Contribution Guidelines](contributing.md).

## License
This project is licensed under the [MIT License](LICENSE).
