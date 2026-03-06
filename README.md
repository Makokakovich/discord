# Discord Bot

A Discord bot built with Python and discord.py, featuring a modular cog-based architecture.

## About

Personal project by **Maksim Karmaiznovskiy**. Built to automate moderation, fun commands, and server management using an extensible cog system.

## Features

- Modular cog system for easy command management
- Slash commands support
- Moderation tools
- Fun and general commands
- Docker support

## Setup

Rename `.env.example` to `.env` and fill in your values:

```
TOKEN=your_discord_bot_token
PREFIX=your_bot_prefix
INVITE_LINK=your_invite_link
```

## Install & Run

```bash
python -m pip install -r requirements.txt
python bot.py
```

### Docker

```bash
docker compose up -d --build
```

## Built With

- [Python 3.12](https://www.python.org/)
- [discord.py](https://discordpy.readthedocs.io/)

## License

Apache License 2.0 — see [LICENSE.md](LICENSE.md)
