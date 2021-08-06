# Configuration

A detailed walkthrough of everything in the Lilith 0.3.1 config file. The default config for the latest version can be found [here](https://apiv2.lilithmod.xyz/assets/lilith-0-3-0.toml).

---

### config_version
Don't ever touch this. Ever.

### hypixel_api_key
Doing /api new while ingame using Lilith will save the api key, but if you already have one and don't want to regenerate, you can put it here.

---
## deobfuscate

### chat
This lets you enable or disable names being shown in chat during a duels queue.

### tablist_and_nametags
This lets you enable or disable names being shown in tablist and nametags during a duels queue.

---
## queuestats

### current_nickname
The nickname you're currently using. Use `/lnick` ingame to set or reset it; see [Commands](commands.md).

### overall
Whether you'd like queuestats to just show overall stats instead of gamemode-specific stats.

### modes_overall
Whether you'd like modes with multiple variations to use the overall stats or specific stats. For example, overall bridge stats vs bridge solo stats.

### whitelisted
A list of usernames you never want queuestats to check. This will be removed in 0.4.0. Players on this list can be temporarily modified using the `/whitelist` command; see [Commands](commands.md).

### queuestats.aliases
A key/value list of aliases for the `/sc` command. The raw gamemodes are visible from the default aliases.

---
## server

### remote_ip
The ip of the server to which you'd like to connect.

### remote_port
The port of the server to which you'd like to connect.

### folder
Your .minecraft folder. If you use the default .minecraft folder, leave this blank. Otherwise, add the full folder path.

### server.authentication
A key/value list of username to credentials. If you're getting SocketClosed or a yggdrasil error, you can try adding your account to this list. To add an account, create a new line `Username = ['email', 'password']` for Mojang or `Username = ['email', '', 'microsoft']` for Microsoft; replacing Username, email, and password with the details for your account.

---
## local

### server_ip
The ip on which Lilith's local server will be hosted. Leave this as "127.0.0.1" unless you really know what you're doing.

### motd
The message of the day seen on the server list for Lilith's local server.

---
## commands.aliases
A key/value list of aliases for commands. The default commands can be seen below. To add an alias create a new line of the form `alias = 'command'`. To disable a command entirely you can delete or comment out with `#` all of the aliases for that command.

---
## fast_lobby

### enabled
Whether to enable fast lobby. I recommend to turn this on, as leaving a duels game will magically get noticeably faster.

### mode
The lobby you'd like to be taken to for fast lobby to work. For redirection to work, keep this as "blitz".

### gametypes
A list of gametypes that fast lobby should work in. For example, DUELS, BEDWARS, or SKYWARS.

---
## debug

### log_chat_messages
Whether or not to log incoming chat messages to the terminal.