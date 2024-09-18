# Telegram Sticker Bot

A simple Telegram bot that allows users to convert images from links into stickers. Users can send an image URL, and the bot will process it and send back a sticker.

## Features

- Responds to the `/start` command with a welcome message and a button linking to the Posters Universe channel.
- Users can send image URLs, and the bot converts those images into stickers.
- Handles image validation and error reporting.

## Requirements

- Python 3.x
- `python-telegram-bot` library
- `Pillow` library
- `requests` library

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/telegram-sticker-bot.git
   cd telegram-sticker-bot
2. **Install the required libraries**
   > either u can do that
   `
   pip install python-telegram-bot Pillow requests
   `
   > or you can install it by
   `pip install -r requirements.txt`
3. **Set your bot token:**
   ```bash
   Step 1: Create a New Bot
   Open Telegram: You can use the desktop app or the mobile app.
   Search for BotFather: In the search bar, type @BotFather and select the official bot.
   Start a Chat: Click the "Start" button or type /start in the chat with BotFather.
   Create a New Bot: Send the command /newbot to BotFather.
   Follow Instructions:
   Name your bot: Choose a name for your bot (this will be displayed in contact details).
   Choose a username: Create a username that ends with "bot" (e.g., MyAwesomeBot).
   Receive Your Token: After creating the bot, BotFather will provide you with a token. It will look something like this:
   123456789:ABCdefGhIJKlmnoPQRstuVWXyz1234567890
   Step 2: Copy or Save Your Bot Token somewhere and just replace it in bot.py
   ```
## Usage
> - Run the bot:
`python bot.py`

- if on vps or ubantu check ur python version `python --version` and if its 3 then `python3 bot.py` like python(version) bot.py


### Open Telegram and search for your bot.

Send the /start command to initiate the bot.

Send a valid image URL to receive a sticker in return.

Example
To convert an image, simply send a message with the URL of the image:
`https://images.cdn.prd.api.discomax.com/2024/06/20/26eb6a8a-4b81-34f7-938d-01c8b92a627d.png`

- Adjust any details according to your preferences and additional features you may want to highlight. 

### Let me know if you need any more modifications!
