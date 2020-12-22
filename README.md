<p align="center"><img src="https://i.imgur.com/FiLr3O3.png"></p>
<h1 align="center">Cyclops: A general purpose discord bots to hopefully fufill all your needs</h1>
<div align="center">

[![forthebadge](https://forthebadge.com/images/badges/made-with-typescript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-badges.svg)](https://forthebadge.com)
[![Codacy Badge](https://img.shields.io/codacy/grade/93dbe215b3dc462495511975bfc7fafb?style=for-the-badge)](https://www.codacy.com/gh/CyclopsBot/bot/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=CyclopsBot/bot&amp;utm_campaign=Badge_Grade)
</div>

<h1 align="center"style="font-weight: bold">Getting started</h1>

<h2 style="font-weight: bold">Prerequisites</h2>

- [Yarn](https://classic.yarnpkg.com/en/)
- [Node](https://nodejs.org/en/)
- [MongDB](https://docs.mongodb.com/manual/administration/install-community/)
- [A discord bot token](https://discord.com/developers/applications)
<br></br>

<h2 style="font-weight: bold">Initlializing your project</h2>
First input your credentials and bot options in there respective files
<br></br>

`<>` required `[]` optional

botoptions.ts
```
export const prefix: String = '<prefix>' // this will be replace by the database later on
export const prefix: String | String[] = '<array or string of owner(s)>'

// any other hard coded bot options , etc you need will be put here
```
credentials.ts
```
export const token: String = '<token>'

// any other api keys, etc you need will be put here
```
<br></br>

<h1 align="center"style="font-weight: bold">Commands</h1>

| commands | usage | description |
|----------|-------|-------------|
| soon™    | soon™ | soon™     |


<h1 align="center"style="font-weight: bold">Contributing</h1>

You can find the full contributer guidelines and steps [here](https://github.com/CyclopsBot/bot/blob/master/CONTRIBUTING.md).
<br> </br>
If you require further help please create an [issue](https://github.com/CyclopsBot/bot/issues) on the github we are glad to help you.

<h1 align="center"style="font-weight: bold">Resources we use</h1>

[discord.js](https://discord.js.org/#/) : We use discord.js for interactiing with the discord api

[discord.js-akairo](https://discord-akairo.github.io/#/): We use discord.js akairo for handing commands and events from discord.js to make our lives easier

You can also find other dependancies that are not listed [here](https://github.com/CyclopsBot/bot/blob/master/package.json)

