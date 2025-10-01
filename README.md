# Discord Cloner Bot

A simple Discord bot built with discord.py that allows server owners to clone the structure of one server into another. This includes:

- Copying roles (permissions, colors, mentionability, etc.)

- Copying categories, text channels, and voice channels

- Cleaning the target server before cloning (removing old roles and channels)

⚠️ Important: This bot is only intended for personal testing or for cloning your own servers as backups. Misuse of this bot may violate Discord’s Terms of Service.

# ✨ Features

/clone <source_id> <target_id> command to copy server structure

Deletes all existing channels and roles in the target (except @everyone) before cloning

Copies:

Roles with permissions

Categories and their channels (text + voice)

Channel overwrites for roles
