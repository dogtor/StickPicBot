# MyOwnerBot

[Developer] (https://telegram.me/Dogtor)

# 🔹🔹Commands🔹🔹

 **Sticker😊 to Photo🌄**

`Just send a sticker`

 **Photo🌄 to Sticker😊**

`Just send a photo`

 🔰 **Bold Text** 🔰

`/bold text`

 🔰 **Italic Text** 🔰

`/italic text`

 🔰 **Markdown Link** 🔰

`/link url text`

 🔰 **Code Text** 🔰

`/code text`

# Channel 🔊

  ➿ **Send Bold Text to a Channel** ➿

`/boldch @yourchannel text`

  ➿ **Send Italic Text to a Channel** ➿

`/italicch @yourchannel text`

  ➿ **Send Markdown Link to a Channel** ➿

`/linkch @yourchannel url text`

  ➿ **Send Code Text to a Channel** ➿

`/codech @yourchannel text`

# Installation 🚩

1⃣-- Write>>
`sudo apt-get update`
1⃣-- Write>>
`sudo apt-get upgrade`

2⃣-- Write>> ⏬⏬
```bash
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```
3⃣-- Write>>
`sudo apt-get install lua-socket` 
4⃣-- Write>>
`sudo apt-get install lua-sec`

1⃣-- Write>>
`cd $HOME`

5⃣-- Write>> Clone the bot Write ⏬⏬
```
git clone https://github.com/dogtor/MyOwnerBot.git
```

1⃣-- Write>>
`cd MyOwnerBot`

🚸Then install bot using✅
`lua bot.lua`
👮bot token in bot.lua (config part)✔️

```lua

local bot_api_key = "" -- token
local BASE_URL = "https://api.telegram.org/bot"..bot_api_key
local BASE_FOLDER = "" -- do not set this
```
🔰And enter your telegram-id in admins table in [bot.lua](https://github.com/Imandaneshi/file-manager-bot/blob/master/bot.lua#L19) 💠

```lua
local var = false
  local admins = {140629197,987654321}-- put your id here
  for k,v in pairs(admins) do

```
Save bot.lua Ⓜ️

Start the bot 👁

`lua bot.lua`
