# Discord-Music-Bot
Music bot for discord with everything working 09/16/21

The code was written using [python](https://www.python.org/) 3.5+, it is not guaranteed to work with any version of python prior to this one.

You can use these files to make a music bot for your Discord server

# How to configure:

## Requirements:
* [Python](https://www.python.org/): code programming language;
* [Discord.py](https://discordpy.readthedocs.io/en/latest/): discord.py library;
* [FFmpeg](https://ffmpeg.org/download.html): FFmpeg download

You need to put FFmpeg in your system path

To install the necessary dependencies you need to open your cmd and type:
```py
pip install discord.py[voice]
pip install youtube_dl
```

To bring the bot online, open 'config.json' file and in the code location where it says:
```py
"token":"TOKEN HERE"
```
you replace the TOKEN HERE with your bot's token.

Now if you did everything correctly just run main.py and have fun with the bot!
