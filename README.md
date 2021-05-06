<h1 align="center">
  <br>
  <br>
  Nolonia Discord Bot
  <br>
</h1>

<h3 align=center>A fully customizable bot built with <a href=https://github.com/aoijs/aoi.js>aoi.js</a></h3>


<div align=center>

 

</div>

<p align="center">
  <a href="#about">About</a>
  •
  <a href="#features">Features</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="#setting-up">Setting Up</a>
  •
  <a href="#license">License</a>
  •
  <a href="#credits">Credits</a>
</p>

## About

Nolonia is an open source, fully customizable Discord bot that is constantly growing. She comes packaged with a variety of commands and a multitude of settings that can be tailored to your server's specific needs. Her codebase also serves as a base framework to easily create Discord bots of all kinds. You can invite her to your Discord server using [this](https://discord.com/api/oauth2/authorize?client_id=839436962057551892&permissions=8&redirect_uri=https%3A%2F%2Fdiscord.gg%2F7CgzRGCUvC&response_type=code&scope=guilds.join%20bot) link! Also, you can join the official [Nolonia Support Server](https://discord.gg/7CgzRGCUvC) for all questions, suggestions, and assistance!

If you liked this repository, feel free to leave a star ⭐ to help promote Nolonia!

## Features

**10+** commands and counting across **2** different categories!

  * **Administration:** A huge amount of settings to customize with commands like `setprefix`
  * **Moderation:** Commands such as `kick`, `ban`, and `mute` to assist your moderator staff

Nolonia also comes packed with a variety of features, such as:

  * **Auto role** assignment* via reactions


## Installation

You can add Nolonia to your server with [this](https://discord.com/api/oauth2/authorize?client_id=839436962057551892&permissions=8&redirect_uri=https%3A%2F%2Fdiscord.gg%2F7CgzRGCUvC&response_type=code&scope=guilds.join%20bot) link! Alternatively, you can clone this repo and host the bot yourself.
```
git clone https://github.com/Nolonia/Nolonia.git
```
After cloning, run an
```
npm install aoi.js
```
to snag all of the dependencies. Of course, you need [node](https://nodejs.org/en/) installed. I also strongly recommend [aoi.js](https://www.npmjs.com/package/aoi.js) as it makes testing *much* easier.

## Setting Up

You have to edit a `nolonia.js` file in order to run the bot. Your file should look something like this:
```
const Aoijs = require("aoi.js")
 
const bot = new Aoijs.Bot({
  mobile: false,
  token: "TOKEN", //Add here your bot token!
  prefix: ["PREFIX"] //Type your prefix here
  autoUpdate: true, 
  
})
```
Visit the Discord [developer portal](https://discordapp.com/developers/applications/) to create an app and use the client token you are given for the `token` option.

After your `nolonia.js` file is built, you have enable `Privileged Intents` on your Discord [developer portal](https://discordapp.com/developers/applications/). You can find these intents under the "Bot" section, and there are two ticks you have to switch on. For more information on Gateway Intents, check out [this](https://discordjs.guide/popular-topics/intents.html#the-intents-bit-field-wrapper) link.

Once done, feel free to launch Nolonia using the command `node nolonia.js`. If on Linux, you can also kick off using the `start.sh` script. If you need additional help setting up, join the [Nolonia Support Server](https://discord.gg/7CgzRGCUvC)!


## To-Do

Nolonia is in a continuous state of development. New features/updates may come at any time. Some pending ideas are:

  * Music
  * Stream alerts

## License

Released under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html) license.

## Credits

* [Calypso Bot](https://github.com/sabattle/CalypsoBot)
