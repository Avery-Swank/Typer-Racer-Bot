# typer-racer-bot
A Selenium Webdriver NodeJS application for playing Typer Racer.

[Typer Racer](https://play.typeracer.com)

## Summary
Typer Racer is an intriuiging little way to cheat the website into thinking you are actually typing. However, the website has good bot prevention. You certainly cannot be put on the leaderboard for using this application because it verifies your typing with an image of words rather than the words itself, making it hard to pull for a computer to read.

You can adjust the milliseconds between typing workds here: `const timeBetweenWords = 150`

It buildings its own browser instance to run the bot, that could be changed with an update.

Average bot performance without interrutptions for being a bot is 340+ words per minutes.

## How to Run
Type: `node bot.js`
