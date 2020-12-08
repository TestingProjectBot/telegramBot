#  𝗞𝗔𝗥𝗠𝗔 𝗕𝗢𝗧 
[![For You](https://forthebadge.com/images/badges/for-you.svg)](https://github.com/Karma-goku/KarmaBot)

<p align="center">
<img src="logo.jpg" alt="KarmaBot">

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

![Build Status](https://img.shields.io/badge/Build%20-Passing-brightgreen) ![Python Version](https://img.shields.io/badge/Python-3.7%2F3.8-lightgrey) ![Release](https://img.shields.io/badge/Release-v0.1.0-blue)  [![Plugins Repo!](https://img.shields.io/badge/Plugins%20Repo-!-orange)](https://github.com/Karmaboii/KarmaBot/tree/master/userbot/plugins) [![License](https://img.shields.io/badge/License-MIT%20License-orange)](https://github.com/Karmaboii/KarmaBot/blob/master/LICENSE) ![Bot Size](https://img.shields.io/badge/Bot%20Size-253.2mb-blue) [![Bot Creator](https://img.shields.io/badge/Bot%20Creater-%40Karmaboii-red)](https://t.me/Karmaboii)
## Installing Heroku
[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Karmaboii/KarmaBot)
## GET STRING SESSION FROM REPL RUN 
### The Easiest Way
[![Repl.it](https://img.shields.io/badge/STRING%20SESSION-Make%20Online-brightgreen)](https://Karmaboii.karmabot.repl.run)
...With The Help Of This U can Skip Termux Part And Make String Sessions Easily

### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/Karma-goku/KarmaBot
cd Karmabot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

## Most PowerFul And Better And Secure !

## By KarmaBot

For any query or want to know how it works contact 👇👇
### <a href="https://t.me/Karmaboii"><img src="https://telegra.ph/file/a4bd6dacac3846fc8b428.jpg"></a>



## FORK AT YOUR OWN RISK !
## Don't Forget To Give A Star ⭐

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### UniBorg Configuration

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.
