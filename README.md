# [Tabchi](https://telegram.me/iTeam_ir)

* **An advanced and powerful broadcasting bot based on [SeedTeam/TeleSeed](https://github.com/SeedTeam/TeleSeed)**

# Features

* **Auto join groups**
* **Auto savings links**
* **Auto saving contacts**
* **Exporting links**
* **Broadcast and forward to all users,groups and supergroups**
* **Powerfull stats**
* **Contact managing**
* **And more!**


* * *

## Sudo Commands 

| Command | About |
|:--------|:-------------------------------------------|
| [#!/]pm id text | Send a messafe to id with text |
| [#!/]block id | Block a user from bot's private |
| [#!/]ulock id | Unblock a user from bot's private |
| [#!/]markread on/off | Set markread status on or off |
| [#!/]setphoto (on reply) | Set bot profile photo |
| [#!/]contactlist | Get contact list in json and txt format |
| [#!/]stats | Get bot stats |
| [#!/]echo text | Echo a text |
| [#!/]export links | Export saved links in txt format |
| [#!/]bc text | Broadcast text to all chats |
| [#!/]fwdall (on reply) | Forward a message to all chats |
| [#!/]lua str | Load and run str as lua script|
| $cmd | run cmd in ssh terminal |

* **You can use "#", "!", or "/" to begin all commands**

* * *

# Installation

```sh
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev

# Let's install the bot.
cd $HOME
git clone https://github.com/iTeam-co/Tabchi
cd Tabchi
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command (useful for VPS deployment) on Debian-based distros, use:
```sh
#https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev libjansson* libpython-dev make unzip git redis-server g++ autoconf -y --force-yes && git clone https://github.com/iTeam-co/Tabchi && cd Tabchi && chmod +x launch.sh && ./launch.sh install && ./launch.sh
```

* * *

### Bot configuration

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:
```
  sudo_users = {
  122774063,
  122443587,
  0,
  Your ID
  }
```
Then restart the bot.

### Powered by iTeam!

English Channel: [@iTeam_en](https://telegram.me/iTeam_en)

Persian Channel: [@iTeam_ir](https://telegram.me/iTeam_ir)
