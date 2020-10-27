# PyroGramUserBot 🔥🤖

A Telegram User / Bot based on [Pyrogram](https://github.com/pyrogram/pyrogram)

## installing

#### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

#### The Legacy Way
Simply clone the repository and run the main file:

```sh
git clone https://github.com/SpEcHiDe/PyroGramBot.git
cd PyroGramUserBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create config.py with variables as given below>
python3 -m pyrobot
```


## Getting config.py values

An example `config.py` file could be:

**Not All of the variables are mandatory**

__The UserBot should work by setting only these variables__

```python3
from pyrobot.sample_config import Config

class Development(Config):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
  HU_STRING_SESSION = ""
```

`HU_STRING_SESSION` can be generated by running `python3 GenerateStringSession.py` in any GNU/Linux system, with Python3 and the requirements installed.


## [@SpEcHlDe](https://telegram.dog/ThankTelegram)

- Only three of the configuration / environment variables are mandatory.
- This is because of `pyrogram.errors.API_ID_PUBLISHED_FLOOD`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot should work without setting the non-mandatory environment variables.
- Please report any issues to the support group: [@SpEcHlDe](https://t.me/ThankTelegram)


## Credits, and Thanks to

* [Dan Tès](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [Colin Shark](https://telegram.dog/ColinShark) for his [PyroBot](https://git.colinshark.de/PyroBot/PyroBot)
* [![CopyLeft](https://telegra.ph/file/b514ed14d994557a724cb.jpg)](https://telegra.ph/file/fab1017e21c42a5c1e613.mp4 "CopyLeft Credit Video")
