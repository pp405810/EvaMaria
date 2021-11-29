<p align="center">
  <img src="https://telegra.ph/file/57ce0dd15051ce7b06ed6.jpg" alt="MALAYALAM MOVIES LOGO">
</p>
<h1 align="center">
  <b>Malayalam movies Bot</b>
</h1>


[![Stars](https://img.shields.io/github/stars/pp405810/EvaMaria?style=flat-square&color=yellow)](https://github.com/pp405810/EvaMaria/stargazers)
[![Forks](https://img.shields.io/github/forks/pp405810/EvaMaria?style=flat-square&color=orange)](https://github.com/pp405810/EvaMaria/fork)
[![Size](https://img.shields.io/github/repo-size/pp405810/EvaMaria?style=flat-square&color=green)](https://github.com/pp405810/EvaMaria/)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/EvamariaTG/EvaMaria)   
[![Contributors](https://img.shields.io/github/contributors/pp405810/EvaMaria?style=flat-square&color=green)](https://github.com/pp405810/EvaMaria/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/pp405810/EvaMaria/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/pp405810/EvaMaria.svg)](https://stars.medv.io/pp405810/EvaMaria)


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more


## Deploy
You can deploy this bot anywhere.

<i>**[Watch Deploying Tutorial...](https://youtu.be/1G1XwEOnxxo)**</i>

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/pp405810/EvaMaria">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/EvamariaTG/evamaria
# Install Packages
pip3 install -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>



## Raiway deploy 

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Fpp405810%2FEvaMaria&envs=ADMINS%2CAPI_HASH%2CAPI_ID%2CAUTH_CHANNEL%2CAUTH_USERS%2CBOT_TOKEN%2CCACHE_TIME%2CCHANNELS%2CCOLLECTION_NAME%2CCUSTOM_FILE_CAPTION%2CDATABASE_NAME%2CDATABASE_URI%2CIMDB%2CLOG_CHANNEL%2CP_TTI_SHOW_OFF%2CPICS%2CSINGLE_BUTTON%2CSUPPORT_CHAT%2CUSE_CAPTION_FILTER%2CIMDB_TEMPLATE%2CIMDB&optionalEnvs=AUTH_USERS%2CP_TTI_SHOW_OFF&CACHE_TIMEDefault=300&COLLECTION_NAMEDefault=Telegram_files&IMDBDefault=True&IMDB_TEMPLATEDefault=Hey+%F0%9F%91%8B+%7Bmessage.from_user.mention%7D%2C++%F0%9F%8E%83I+FIND+OUT+WHAT+DO+YOU+WANT%F0%9F%A4%A0++%7Bquery%7D++%3Cb%3E%F0%9F%8F%B7+Title%3C%2Fb%3E%3A+%3Ca+href%3D%7Burl%7D%3E%7Btitle%7D%3C%2Fa%3E+%F0%9F%8E%AD+Genres%3A+%7Bgenres%7D+%F0%9F%93%86+Year%3A+%3Ca+href%3D%7Burl%7D%2Freleaseinfo%3E%7Byear%7D%3C%2Fa%3E+%F0%9F%8C%9F+Rating%3A+%3Ca+href%3D%7Burl%7D%2Fratings%3E%7Brating%7D%3C%2Fa%3E+%2F+10+%28based+on+%7Bvotes%7D+user+ratings.%29+%E2%98%80%EF%B8%8F+Languages+%3A+%3Ccode%3E%7Blanguages%7D%3C%2Fcode%3E+%F0%9F%93%80+RunTime%3A+%7Bruntime%7D+Minutes+%F0%9F%93%86+Release+Info+%3A+%7Brelease_date%7D+%F0%9F%8E%9B+Countries+%3A+%3Ccode%3E%7Bcountries%7D%3C%2Fcode%3E+%F0%9F%91%80+Plot+%3A+%3Ccode%3E%7Bplot%7D%3C%2Fcode%3E+Powered+By+%F0%9F%98%8E+%7Bmessage.chat.title%7D&referralCode=DBBOTZ)


## Commands
```
• /logs - to get the rescent errors
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
• /leave  - to leave from a chat.
• /disable  -  do disable a chat.
* /enable - re-enable chat.
• /ban  - to ban a user.
• /unban  - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://telegram.dog/EvaMariaSupport)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://telegram.dog/EvaMariaUpdates)

## Credits 
* [![EvaMaria-Devs](https://img.shields.io/static/v1?label=EvaMaria&message=devs&color=critical)](https://telegram.dog/EvaMariaDevs)


## Thanks to 
 - Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
 - Thanks To Mahesh For His Awesome [Media-Search-bot](https://github.com/Mahesh0253/Media-Search-bot)
 - Thanks To [Trojanz](https://github.com/trojanzhex) for Their Awesome [Unlimited Filter Bot](https://github.com/TroJanzHEX/Unlimited-Filter-Bot) And [AutoFilterBoT](https://github.com/trojanzhex/auto-filter-bot)
 - Thanks To All Everyone In This Journey

### Note

[Note To A So Called Dev](https://telegram.dog/subin_works/203): 

Kanging this codes and and editing a few lines and releasing a V.x  or an [alpha](https://telegram.dog/subin_works/204), beta , gama branches of your repo wont make you a Developer.
Fork the repo and edit as per your needs.

## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 2.0.](https://github.com/EvamariaTG/evamaria/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.

## Inspiration
This is an attempt to create a clone of a BOAT made out of [banana trees 🌳](https://telegram.dog/GetTGLink/4187)

[![For Vaza](https://telegra.ph/file/e743b0c8a04252774bac2.jpg)](https://telegra.ph/file/98342dc186fd7484cba91.mp4 "Oru Kootam Vazhakalk samarpikkunnu")
