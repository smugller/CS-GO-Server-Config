# Welcome!

Hi! I'm here to help people to organise and sorted CS:GO client and server config for best performance and set it up for classic rules.

# 1. CS:GO Server Config

MetaMod and SourceMod is really not necessary but is a stable version for a long time, it's really easy and nice to use it. Also it doesn't affect your FPS on server until you know and control what plugins are you using. Installation is simple, is limited to copying files to the appropriate directories and thats it!

## A) Requirements and use

Requirements on Server-Side:

- [x] **MetaMod** _Stable_ version or _Latest_ is required:
- Link: [https://www.sourcemm.net/downloads.php?branch=stable](https://www.sourcemm.net/downloads.php?branch=stable)
- Repo: [https://github.com/alliedmodders/metamod-source](https://github.com/alliedmodders/metamod-source)

- [x] **SourceMod** _Stable_ version or _Latest_ is required:
- Link: [https://www.sourcemod.net/downloads.php?branch=stable](https://www.sourcemod.net/downloads.php?branch=stable)
- Repo: [https://github.com/alliedmodders/sourcemod](https://github.com/alliedmodders/sourcemod)

If you have SourceMod installed you can use SourceMod special admin commands. List with all commands you can find here: [Admin Commands (SourceMod)](<https://wiki.alliedmods.net/Admin_Commands_(SourceMod)>)

## B) How to install server config from this repo

1. In CS:GO server directory make a folder in **`../csgo/cfg/`** and name this folder **`superconfig`**

   ( _The correct path should be look like this:_ **`../csgo/cfg/superconfig/`** )
2. Copy all files from this repository to **`../csgo/cfg/superconfig/`** directory.
3. If you have LGSM installed, open the configuration file in **`../csgo/cfg/csgoserver.cfg`** and add at the end of this file a new line:

   > **`exec "superconfig/main.cfg"`**

   This simply link our **`main.cfg`** file from **`../csgo/cfg/superconfig/`** directory and execute rest config files.

4. Save and exit from **`../csgo/cfg/csgoserver.cfg`** file.
5. You can use commands that are include in **`../csgo/cfg/superconfig/alias.cfg`** file. Have fun!

# Customize

If you wanna help or customize my project easily, you can use some of my tips.

## Syntax highlighting for VSCode with .cfg file support

You can use my syntax highlighting plugin and make .cfg files easy to read. Check it now!

> Source: [cfg-syntax-highlighting](https://github.com/smugller/cfg-syntax-highlighting)

## How to get all latest cvars from source engine?

Maybe you didn't know, but it's almost 5000 commands and cvars in CS:GO. This is really huge list that should be sorted with a modern way!

Here yo have plugin to reveal all console variables/commands that are marked as hidden/development-only. It's nice to check time to time for deprecated or new cvar commands.

> Source: [csgo-cvar-unhide](https://github.com/saul/csgo-cvar-unhide)

Ready to view all cvar commands directly from GitHub (check the date and time, because I'm not guaranteed that these repo will be always updated). You can easily look for all CS:GO cvars alongside ones marked as hidden/development-only. Repo is contributed by ArminC.

> Source: [ArminC-CSGO-Cvars](https://github.com/ArmynC/ArminC-CSGO-Cvars)

# CS:GO Client Config

Here are the best client config that i found on the whole internet.

## Client Config

ArminC's configuration for CS:GO Client - well documented, analysed and no misconceptions.

> Source: [ArminC-AutoExec](https://github.com/ArmynC/ArminC-AutoExec)

# TODO

- [ ] Add reset.cfg file to set all commands to default values (Only commands that we use on this repo, maybe not all)
- [ ] Add config for warmup and trening mode
- [ ] Add missing descriptions for commands
- [ ] Translate description from Polish to English
- [ ] Sort network commands in server.cfg for better optimizations
- [ ] Sort commands in bots.cfg file
- [ ] Sort commands for gotv
- [x] Fix commands from alias.cfg

# Contact

If you have any ideas or questions please contact with me somehow.

```

```
