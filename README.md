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
