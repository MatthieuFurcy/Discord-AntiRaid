# Discord AntiRaid Protection
> *A protection system against "RAID", a very widespread threat on Discord.*
---
<br />

-💻 **Technologies** : JavaScript, Node.JS, Quick.DB <br />
-👨‍💻 **Author** : [MF](https://github.com/MatthieuFurcy) <br />
-🌍 **Main Language** : English <br />
-🕓 **Uploaded since** : 5 May 2022 (Reupload because of new Github acc) <br />
-🤖 **Required packages** : ``node.js, npm, discord.js, fs, quick.db, colors``

<br />
<br />

> ⚠️ **READ THIS : It works only for Discord Bots, this is a system that, when turned "on", Prevents a user from creating a new channel, deleting a channel, editing a channel, creating a role, deleting a role, editing a role or even sending a link such as discord.gg or https://arandomlink.com and which prevents webhook creation from every users that are not whitelisted of the bot by deleting all his roles so he can't do it again without your permission.** ⚠️
<br />

---

## __How to use it ❓__

### It's really that easy, first you go to config.json
```json
{
    "TOKEN": "",
    "DEFAULT_COLOR": "",
    "DEFAULT_PREFIX": "",
    "OWNER_ID": ""
}
```
``If there is no problem, you'll see this, then you replace "TOKEN" by your bot token that you generated, "DEFAULT_COLOR" by the color you want (example: #ffffff => white) and "DEFAULT_PREFIX" the prefix you want, don't forget those details : ``
- The token is required for your bot in order to make him log in and works
- The color is required for embed
- The prefix is required for your bot in order to make him work
- You need to give the bot your id 

### Then if everything is ok, you can run packages.bat to install all the required packages if you haven't installed them yet and then you can start the bot by using start.bat
<br />
<br />

---

##### READ THIS : The code is opensource, you can do whatever you want with it. Don't forget that the db system is very basic because of quick.db. I also have a version with MySQL that is better, you can dm me if you wanna this one.

---
<br />

> ##### Last edit : 07/05/2022

> ##### Made with ❤️ by MF
