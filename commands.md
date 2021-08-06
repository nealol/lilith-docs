# Ingame Commands

Lilith features several ingame commands to better your experience. To customize or disable commands, see the [Configuration](configuration.md) page.

## /sc
`/sc <gamemode> <target>`

The statcheck command allows you to check the stats of any Minecraft player for any duels gamemode (more gamemodes coming soon). Any aliases or gamemodes from the Lilith queuestats config will work.

## /rq
`/rq`

This command is one of the most useful in Lilith. It will simply run the play command for the game you are in/were just in.

## /lreload
`/lreload`

Use this command to reload the Lilith config file while ingame.

## /lnick
`/lnick [nick]`

If you're playing nicked, you don't need Lilith to yell at you that you're nicked. This command can be used to change the `current_nickname` in config. To reset the nickname to nothing, run it without an argument.

## /whitelist
`/whitelist add|remove <player>`

The whitelist command can be used to temporarily add players to a queueustats ignore list. Modifications to the whitelist done using this command will reset on config reload or Lilith restart.

## /fakechat
`/fakechat <message>`

This is a simple command that will echo back any message you write including color codes.