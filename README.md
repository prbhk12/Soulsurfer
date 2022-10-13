<p align="center"><a href="https://t.me/TeleStream_herobot"><img src="https://github.com/TeamShizu/KingdomMusic/raw/main/etc/kingdom.jpg"></a></p>
<p align="center">
    <br><b>Kingdom Music is an advance telegram bot project that's allow you to play music and videos on telegram voice chat group</b><br>
</p>

<h1> Demo Bot <a href="https://t.me/TeleStream_herobot"> TeleStream_herobot</a> </h1><br><br>
       
<p align="center">
    <a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-black.svg?style=flat-square&logo=python&logoColor=blue&color=red" /></a>
    <a href="https://github.com/TeamShizu/KingdomMusic/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-red.svg?style=flat-square" /></a>
    <a href="https://app.codacy.com/gh/TeamShizu/KingdomMusic/dashboard"> <img src="https://img.shields.io/codacy/grade/a723cb464d5a4d25be3152b5d71de82d?color=red&logo=codacy&style=flat-square" alt="Codacy" /></a><br>
    <a href="https://github.com/TeamShizu/KingdomMusic"> <img src="https://img.shields.io/github/repo-size/TeamShizu/KingdomMusic?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/TeamShizu/KingdomMusic/commits/main"> <img src="https://img.shields.io/github/last-commit/TeamShizu/KingdomMusic?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/TeamShizu/KingdomMusic/issues"> <img src="https://img.shields.io/github/issues/TeamShizu/KingdomMusic?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/TeamShizu/KingdomMusic/network/members"> <img src="https://img.shields.io/github/forks/TeamShizu/KingdomMusic?color=red&logo=github&logoColor=blue&style=flat-square" /></a>  
    <a href="https://github.com/TeamShizu/KingdomMusic/network/members"> <img src="https://img.shields.io/github/stars/TeamShizu/KingdomMusic?color=red&logo=github&logoColor=blue&style=flat-square" /></a>  
</p>

<h3>Requirements 📝</h3>

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7 or higher
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
- [MongoDB](https://cloud.mongodb.com/)
- [2nd Telegram Account](https://telegram.org/blog/themes-accounts#multiple-accounts) (needed for userbot)


### Video Tutorial:
Complete guide on deploying clone on Heroku.



☆ Video by [Mr RG YT](https://youtube.com/c/MrRGYT) ☆
[![YouTube](https://img.shields.io/badge/YouTube-Video%20Tutorial-red?logo=youtube)](https://youtu.be/h-80yFy5zcU)

### 🧪 Get `SESSION_NAME` from below:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@TeamShizuX/Session-String-Generator#main.py) ``Pyrogram``

### 📌 Vars For `Okteto.com`:
    API_ID 
    API_HASH
    BOT_USERNAME
    ASSISTANT_NAME
    GROUP_SUPPORT 
    UPDATES_CHANNEL
    OWNER_NAME 
    ALIVE_NAME
    OWNER_ID
    SUDO_USERS
    DATABASE_URL 
    LOG_CHANNEL
    SESSION_NAME 
    BOT_TOKEN 
    BOT_NAME


### 🎖 History

[![Mentioned in Awesome Python](https://awesome.re/mentioned-badge.svg)](https://github.com/TeamShizu/KingdomMusic)

## Features 🔮

- Thumbnail Support
- Playlist Support
- Youtube, Local playback support
- Settings panel
- Control with buttons
- Userbot auto join
- Keyboard selection support for youtube play
- Lyrics Scrapper
- Unlimited Queue
- Broadcast Bot
- Statistic Collector
- Block / Unblock (restrict user for using your bot)

## Commands 🛠

- `/cplay <song name>` - play song you requested in channels
- `/cstream <song name>` - play music stream you requested in channels
- `/play <song name>` - play song you requested in groups
- `/vplay <song name>` - play song you requested with video in groups
- `/vstream <song name>` - play video stream you requested in groups
- `/playlist` - Show now playing list
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/vsong <song name>` - download videos you want quickly
- `/lyric <song name>` - lyrics scrapper

#### Admins Only 👷‍♂️
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/music on` - to disable music player in your group
- `/music off` - to enable music player in your group
- `/join` - invite assistant to your chat
- `/leave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status
- `/auth` - authorized people to access the admin commands
- `/unauth` - deauthorized people to access the admin commands
- `/control` - open the music player control panel

### Sudo User 🧙‍♂️
- `/stats` - see the bot statistic
- `/leaveall` - order the assistant to leave all groups
- `/eval (query)` - execute any code
- `/sh (query)` - run any code

### Owner Only 👨🏻‍✈️
- `/broadcast` - send a broadcast message from the bot
- `/block` - block people for using your bot
- `/unblock` - unblock people you blocked for using your bot
- `/blocklist` - show the list of all people who's blocked for using your bot

## 🔎 Inline Search Support
- just type the bot username in any chat, example: "`@TeleStream_herobot Faded Alan Walker`", then bot will give you a results of the query you search in inline mode.

## Heroku Deployment <img src="./etc/Kenpurple.gif" width="40px">
The easy way to host this bot, deploy to Heroku, Change the app country to Europe (it will help to make the bot stable).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/prbhk12/Soulsurfer)

## Okteto Deployment 📌


## VPS Deployment 📡

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/TeamShizu/KingdomMusic.git # clone the repo.
cd KingdomMusic
pip3 install -U -r requirements.txt
cp example.env .env # use vim to edit ENVs
vim .env # fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
python3 main.py # run the bot.
```

### Special Credits 💖
- [Levina](https://github.com/levina-lab): Dev
- [Tofik](https://github.com/tofikdn): Dev
- [Zxce3](https://github.com/Zxce3): Dev
- [Hyoka-XD](https://github.com/PratheekXD) Contributor
- [Rajkumar](https://github.com/Awesome-RJ) Contributor
- [Laky](https://github.com/Laky-64) & [Andrew](https://github.com/AndrewLaneX): PyTgCalls
- [Original Repo](https://github.com/callsmusic/callsmusic) CallsMusic
- [Veez Music Bot](https://t.me/veezmusicbot) Our Music Bot
- [RojSerBest](https://github.com/rojserbest) CallsMusic Developer
- [Levina](https://github.com/levina-lab) for base code

### Support & Updates 🎑
<a href="https://t.me/kingdom_family_support"><img src="https://img.shields.io/badge/Join-Group%20Support-blue.svg?style=for-the-badge&logo=Telegram"></a> <a href="https://t.me/levinachannel"><img src="https://img.shields.io/badge/Join-Updates%20Channel-blue.svg?style=for-the-badge&logo=Telegram"></a>
