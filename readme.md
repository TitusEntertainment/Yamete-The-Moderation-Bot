<img width="150" height="150" align="left" style="float: left; margin: 0 10px 0 0;" alt="Runa" src="https://i.imgur.com/4BMLwt0.gif">

# Runa

[![Build Status](https://www.travis-ci.org/TitusEntertainment/Runa.svg?branch=master)](https://www.travis-ci.org/TitusEntertainment/Runa)
[![Discord Server](https://discordapp.com/api/guilds/585164156710158337/embed.png)](https://discord.gg/jQ9cN55)

> This bot is available for invite via the embed above.

Runa is a discord bot written in javascript with [discord.js](https://discord.js.org/#/) using the
[discord-akairo](https://discord-akairo.github.io/#/) wrapper. Runa's job, just like in the series is to oversee and moderate!

## Installing

1. Make sure you have installed [Node.js](https://nodejs.org/en/), [Git](https://git-scm.com/) and [yarn](https://yarnpkg.com/).
2. Clone this repository with `git clone https://github.com/https://github.com/TitusEntertainment/Runa`.
3. Run `cd Runa/src` to move into the folder that you just created.
4. Create a file named `.env` and fill it out as shown in `.env.md`.
5. Now go back into the terminal and run `yarn add`.
6. After you've installed all the dependencies run `yarn add global add pm2.
7. Open the terminal again and run `cd src`.

### You're now ready to start the bot!

To start the bot run `pm2 start bot.js`

## Commands

### Bot

- **help:** sends a list of all commands

### Moderation

- **warn:** warns a user if user has three warnings the user get's kicked. (optional reason)
- **ban:** bans a user (optional reason)
- **uban:** unbans a user (optional reason). **NEEDS USERID**
- **kick** kicks specified user (optional reason)
- **clear:** clears user defined amount of messages (1-100)
- **tempmute:** mutes defined user for a defined amount of time. For an example 10min.
- **tempban:** temporarily bans a user for a defined amount of time (If no argument given it's 1 day by default)
- **pardon:** removes all warnings from the user, aka pardons the user.

### Guild specific

- **setRules:** lets guild owner or admin set guild rules (max char length is 6000)
- **rules:** lets guild member see the set rules (if there is any).
- **lookup:** Looks up the mentioned user.
- **log:** Sets a new log channel (default is modlogs)
- **bans:** Sends info about how many bans the guild has banned with the bot and the latest user to get banned
