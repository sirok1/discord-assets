# discord-assets
<div align = "center">
  <p>
    <a href="https://github.com/sirok1">
      <img src="https://res.cloudinary.com/hxsqjtxdf/image/upload/v1655210108/watermark_poeyn7.png">
    </a>
  </p>
  </div>
<div align="left">
  <p>
   discord public bot Memories
 </p>
</div>
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
