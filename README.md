# VCHARS AI BOT

VCharsAI Bot is an automation tool designed for vChars.ai chat interactions. It enables automated conversations with AI characters.

## Features

- Automatic AI character selection
- 24-hour chat cycle automation
- Detailed logging with colored output
- Interactive countdown timers
- Error handling and automatic retries
- Customizable character selection
- User-friendly configuration and setup

## Prerequisites

Before running the bot, make sure you have:

1. Node.js installed (version 16 or higher)
2. A Groq API key get it from [Groq Console](https://console.groq.com/keys)
3. A vChars.ai account register [here](https://t.me/vchars_bot/)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Rambeboy/vchars-ai-bot && cd vchars-ai-bot
```

2. Install dependencies:

```bash
npm install
```

3. Set up your configuration:
- Edit `data.txt` file in the project root
- Copy your vChars.ai user data into `data.txt`

## Configuration

1. Edit `data.txt`:

- Launch vChars.ai
- Copy the user data from your network tab
- Paste it into `data.txt`

2. Configure GROQ API:
- Get your API key from [Groq Console](https://console.groq.com/keys)
- Replace the `groq_api_key` in `index.js` with your key

## Usage

Run the bot:

```bash
npm run start
```

The bot will:

1. Display the startup banner
2. Ask you to select an AI character
3. Start the automated chat session
4. Wait 24 hours before the next cycle

## Error Handling

The bot includes robust error handling:

- Automatically retries on errors
- Waits 1 hour between retry attempts
- Detailed error logging
- Gem depletion detection

## Disclaimer

This bot is for educational purposes only. Make sure to comply with vChars.ai's terms of service when using this bot.

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more details.
