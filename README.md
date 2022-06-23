# Discord Youtube Player

## Setup

Join Bot at [link](https://discord.com/api/oauth2/authorize?client_id=989447523204755476&permissions=8&scope=bot)
> established on [Heroku](https://dashboard.heroku.com/)

## !help

```
A Native YT Player Bot(not support playlist currently)

Music:
  join    Joins a voice channel.
  leave   Clears the queue and leaves the voice channel.
  loop    Loops the currently playing song.
  now     Displays the currently playing song.
  pause   Pauses the currently playing song.
  play    Plays a song.
  queue   Shows the player's queue.
  remove  Removes a song from the queue at a given index. (arg: index of the ...
  resume  Resumes a currently paused song.
  search  Searches youtube.
  shuffle Shuffles the queue.
  skip    Vote to skip a song. The requester can automatically skip.
  stop    Stops playing song and clears the queue.
  summon  Summons the bot to a voice channel.
  volume  Sets the volume of the player. (arg: int, 0 ~ 100)
No Category:
  botstop
  help    Shows this message

Type !help command for more info on a command.
You can also type !help category for more info on a category.
```

## Create your own bot locally

1. Go to [discord application](https://discord.com/developers/applications/) and create your application with bot
2. In Bot
   - Privileged Gateway Intents: turn on `Presence Intent`, `Server Members Intent`
   - write your token in [dc_token.txt](./dc_token.txt)
3. In Oauth2
   - `bot` > `Administrator` to get your bot's join link

### Requirements

- Python 3.5+

```.sh
pip install -r requirements.txt
```

### Run

```.sh
python main.py
```

## Clone from

[gist.guac420/music_bot_example.py](https://gist.github.com/guac420/bc612fd3a35cd00ddc1c221c560daa01)

## TODO

- [ ] add support for playlist
