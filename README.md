# kbot

A multi-purposes [Telegram bot](https://t.me/savkaviktor_bot).

## Features

- Give a single answer if you type "hello"

## Installation

1. Clone the repository:
```bash
git clone git@github.com:savkaviktor16/kbot.git
```

2. Set up your Telegram Bot Token:
```bash
export TELE_TOKEN="your_telegram_bot_token"
```

3. Build the application:
```bash
go build -ldflags -X=github.com/savkaviktor16/kbot/cmd.appVersion=v1.0.2
```

## Usage

Start the bot:
```bash
./kbot start
```

### Available Commands

- `hello` - Get a greeting from the bot

### Project Structure

- `cmd/` - Contains the main command implementations
  - `kbot.go` - Main bot implementation
  - `root.go` - Root command configuration
  - `version.go` - Version command implementation