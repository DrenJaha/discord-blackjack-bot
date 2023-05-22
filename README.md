# discord-blackjack-bot
## Description
Blackjack Bot: A Discord bot that allows users to play the classic card game Blackjack. Users can start a new game, hit, stand, and automatically win when they get a perfect Blackjack. The bot keeps track of the state of each game per user, ensuring a seamless gaming experience. Built with Python using the discord.py library.

## Installation & Setup
1. Clone this repository to your local machine using: 'https://github.com/DrenJaha/discord-blackjack-bot.git'.
2. Install the required dependencies: 'pip install discord.py'
3. Create a new bot on the [Discord Developer Portal](https://discord.com/developers/applications), retrieve the bot token, and enable the necessary intents (Message Content, Guilds, Messages).
4. Replace your-token in the last line of discord_bot.py with your bot's token.
5. Invite the bot to your server by creating an invite link as explained in the Discord Developer Portal.
6. Run discord_bot.py to start the bot.

## Usage
To start the game: !start-blackjack
To hit(get another card): !hit
To stand(not get another card): !stand
The bot will automatically check for Blackjack (a hand with a total of 21).

## Dependencies
This project uses the following dependencies:
  - Python 3.8 or later
  - discord.py (latest version)

Please install these using pip (Python's package installer) as mentioned in the Installation & Setup section above.
