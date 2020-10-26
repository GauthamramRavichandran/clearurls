# ClearURLs BOT

A (_minimalist_) telegram bot to provide clean urls (i.e., removes any tracking info on the url (looking at you, **Facebook** and **Google** 😉))

[DEMO](https://t.me/ClearURLs_Bot "ClearURLs BOT")

This bot utilises two libraries (credits to the creators)
    
    1. Telethon
    2. Unalix

#### Usage,
1. Send a link, bot will reply with a clearURL
2. Add the bot in a group, bot will reply with clearURLs there

#####Deploy your own bot,
1. Follow this [guide](https://docs.telethon.dev/en/latest/basic/signing-in.html "setup guide") to get `api_id`, `api_hash` and `bot_token`
2. Replace those values in `CONFIG.py`
3. Create a virtualenv and install the `requirements.txt`
4. Start the bot, `python main_file.py`

#### Disclaimer

    Copyright (C) 2020  Gauthamram Ravichandran

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.