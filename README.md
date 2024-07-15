<h1 align="left">Discord Poll Bot</h1>
<p align="left">A JavaScript Discord bot that utilises MongoDB to create a poll system that allows members of the Discord server to vote on a topic of discussion with two options.</p>

<p align="left">See it in action here: (Insert Link Here!)</p>
<h2>About</h2>
<p>
  While working on my Discord bot for the computer science Discord server, I found two unique features I created that I would like to showcase separately: a suggestion system bot and a poll bot. When working on the suggestion system, I realised that I could also turn it into a poll system, where the figures and bars update in real time as people vote for the options, just like the suggestion system but configured to display differently.
</p>

<h2>Language and Modules Used</h2>
<div align="start">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/discordjs/discordjs-original.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongoose/mongoose-original.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/motdotla/dotenv/master/dotenv.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/underctrl-io/commandkit/next/apps/docs/public/logo_lg.webp" hieght="50" width="60">
</div>

<h2>Tools Used</h2>
<div align="start">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" hieght="50" width="60">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" hieght="50" width="60">
</div>

<h2>Features</h2>

- Currently allows the users to vote between two options with buttons they can click to vote with
- Checks to see if someone has already voted, so you can’t vote twice
- Bars update in real time through the use of a MongoDB database
- Admins can decide when it’s time to end a poll by pressing the ‘Results’ button

<h2>Usage</h2>
<p align="left">Make sure you install the latest NodeJS version and have a Discord bot application to run the code smoothly.</p>
<p align="left">You can find out how to set up a Discord bot application here: https://discord.com/developers/docs/quick-start/getting-started</p>
<p align="left">You find out how to set up a MongoDB database here: https://www.youtube.com/watch?v=edeNqzKvj0g</p>

- Install discord.js + other dependencies (run each command separately)
```
npm install discord.js
npm install commandkit
npm install mongoose
npm install dotenv
```

- Create a .env file with the following details
```
TOKEN = YOUR_BOT_TOKEN
MONGODB_URI = YOUR_MONGODB_URI
```

- Download the rest of the project files
- Make sure the bot you created is added the discord server you want to run it in
- Start the bot by running the following command
```
node .
```

<h2>Configuring the Bot</h2>


