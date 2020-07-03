# A Discord Music Bot written in JavaScript, the discord.js library and discord.js-commando framework

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

### Installing the dependencies

`npm i`

### Setup

Make a config.json file in the root directory of the project and add:

```
{
  "prefix": "!",
  "discord_owner_id": "Your-Discord-ID",
  "token": "Your-Bot-Token",
  "youtubeAPI": "youtube-api-key",
  "geniusLyricsAPI": "genius-api-key"
}
```

Open index.js and change the ID in line 30 to your discord user ID

Also, no matter what operating system you have, make sure [ffmpeg](https://www.ffmpeg.org/download.html) and [python 2.7](https://www.python.org/downloads/) are installed. **Discord.js now requires Node version greater than or equal to 12.0.0** .

If you are not cloning this repo, make sure your dependencies versions are the same as this repo's.

### Commands

- Music

| Command      | Description                                                                                                       | Usage                  |
| ------------ | ----------------------------------------------------------------------------------------------------------------- | ---------------------- |
| !play        | Play any song or playlist from youtube, you can do it by searching for a song by name or song url or playlist url | !play darude sandstorm |
| !pause       | Pause the current playing song                                                                                    | !pause                 |
| !resume      | Resume the current paused song                                                                                    | !resume                |
| !leave       | Leaves voice channel if in one                                                                                    | !leave                 |
| !remove      | Remove a specific song from queue by its number in queue                                                          | !remove 4              |
| !queue       | Display the song queue                                                                                            | !queue                 |
| !shuffle     | Shuffle the song queue                                                                                            | !shuffle               |
| !skip        | Skip the current playing song                                                                                     | !skip                  |
| !skipall     | Skip all songs in queue                                                                                           | !skipall               |
| !skipto      | Skip to a specific song in the queue, provide the song number as an argument                                      | !skipto 5              |
| !volume      | Adjust song volume                                                                                                | !volume 80             |
| !loop        | Loop the currently playing song                                                                                   | !loop 5                |
| !lyrics      | Get lyrics of any song or the lyrics of the currently playing song                                                | !lyrics song-name      |
| !now-playing | Display the current playing song with a playback bar                                                              | !now-playing           |

- Misc

| Command | Description                         | Usage   |
| ------- | ----------------------------------- | ------- |
| !uptime | Replies with the bot's total uptime | !uptime |

### Resources

[How to get a Youtube API key](https://developers.google.com/youtube/v3/getting-started)

[Get a Genius API key here](https://genius.com/api-clients/new)

[Installing node.js on debian](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-node-js-application-for-production-on-debian-9)

[Installing node.js on Windows](https://treehouse.github.io/installation-guides/windows/node-windows.html)

### Contributing

Fork it and submit a pull request!
Anyone is welcome to suggest new features and improve code quality!

## Contributors

[encoder-glitch](https://github.com/encoder-glitch) - uptime command

[chimaerra](https://github.com/chimaerra) - minor command tweaks

## This is a forked project

The project I used to created this is [Master-bot](https://github.com/galnir/Master-Bot)
