# 🤖 DeejayBot (Discord Music Bot)
> DeejayBot is a Discord Music Bot built with discord.js & uses Command Handler from [discordjs.guide](https://discordjs.guide)


## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v14.0.0 or newer

## 🚀 Getting Started

```
git clone https://github.com/l0ser8228/deejaybot.git
cd deejaybot
npm install
```

After installation finishes you can use `node index.js` to start the bot.

## ⚙️ Configuration

Copy or Rename `config.json.example` to `config.json` and fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "OWNER_ID": ""
}
```

## 📝 Features & Commands

> Note: The default prefix is '!'

* 🎶 Play music from YouTube via url

`!play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎 Play music from YouTube via search query

`!play under the bridge red hot chili peppers`

* 🎶 Play music from Soundcloud via url

`!play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎 Search and select music to play

`!search Pearl Jam`

* 📃 Play youtube playlists via url

`!playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Play youtube playlists via search query

* Now Playing (!np)
* Queue system (!queue, !q)
* Loop / Repeat (!loop)
* Shuffle (!shuffle)
* Volume control (!volume, !v)
* Lyircs (!lyrics, !ly)
* Pause (!pause)
* Resume (!resume, !r)
* Skip (!skip, !s)
* Skip to song # in queue (!skipto, !st)
* Toggle pruning of bot messages (!pruning)
* Help (!help, !h)
* Command Handler from [discordjs.guide](https://discordjs.guide/)
* Media Controls via Reactions
![reactions](https://i.imgur.com/j7CevsH.png)

## 🤝 Contributing

1. [Fork the repository](https://github.com/L0SER8228/DeejayBot/fork)
2. Clone your fork: `git clone https://github.com/your-username/DeejayBot.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -am 'Add some feature'`
5. Push to the branch: `git push origin my-new-feature`
6. Submit a pull request

[![Run on Repl.it](https://repl.it/badge/github/L0SER8228/DeejayBot)](https://repl.it/github/L0SER8228/DeejayBot)
