# Fisherbot
Uses the [discord.js](https://discord.js.org/) framework

## Setup
Windows build tool will help installing packages if installing on Windows: https://github.com/felixrieseberg/windows-build-tools/blob/master/README.md

1. Install NVM if you haven't already - https://www.nvmnode.com/guide/download.html
   Install and use Node 18
   ```
   nvm install 18
   nvm use 18
   ```
2. Install node-canvas dependencies - https://github.com/Automattic/node-canvas#compiling

3. Install FFmpeg - https://ffmpeg.org/download.html

4. Install remaining depencies
   ```
   npm install
   ```
5. Find the file `config.json.example` in the directory `docs/deploy/`
   Create a copy of this file within this directory and name it `config.json`
   Replace the placeholder bot token in `config.json` with your own

## Usage
Start the bot with `npm run pmstart` and stop it with `npm run pmstop`
Use `!help` in the server the bot was added to see all bot commands