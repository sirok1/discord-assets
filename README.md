# Discord-assets
 a module which provide an assets for discord bot
# Installing
```bash
npm i discord-assets
```
# Methods
- deadinsidenick
- drain
- nozhki
- wallpaper
- tired
- eball (8ball)
- cats
- suicide
- spit
- smug
- smoke
- sleep
- slap
- shy
- shock
- shiz
- sex
- sad
- run
- poke
- pat
- marry
- love
- lick
- kiss
- kill
- hug
- fucku
- eat
- drink
- dance
- cry
- avatar

# Example
```js
const Discord = require("discord.js");
const ASSETS = require("discord-assets");
const asset = new ASSETS();
const image = asset.sad();
const embed = new Discord.MessageEmbed()
    .setTitle(`Sad gif`)
    .setColor("GREEN")
    .setImage(image);
message.channel.send(embed);
```
