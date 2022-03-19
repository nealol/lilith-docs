# Ingame Commands

Lilith features several ingame commands to better your experience. To customize or disable commands, see the [Configuration](configuration.md) page.

## /sc
`/sc <gamemode> <target>`

The statcheck command allows you to check the stats of any Minecraft player for any duels gamemode. Abreviations (aliases) for gamemodes can be found in your toml file. If you are unsure about a gamemode's alias simply type its notation for the gamemode like you would if you were typing out a /play command. For example, if you wanted to see someone's OP stats but didn't know its alias was op1, you could use OP_duel instead. Any aliases or gamemodes from the Lilith queuestats config will work.

## /rq
`/rq`

This command is one of the most useful in Lilith. It will simply run the play command for the game you are in/were just in and elimiate the need for you to memorize several long commands and have them copied to your clipboard.

## /nh
`/nh <target>`
This command allows you to see the namehistory of the targetted player; this includes all of their previous igns as well as the dates they were changed on.

## /lreload
`/lreload`

Use this command to reload the Lilith config file while ingame so you don't have to relaunch Lilith every time you change it.

## /lnick
`/lnick [nick]`

If you're playing nicked, you don't need Lilith to yell at you that you're nicked. This command can be used to change the `current_nickname` in config to let Lilith know you are nicked with a certain nickname. To reset the nickname to nothing, run it without an argument.

## /whitelist
`/whitelist add|remove <player>`

The whitelist command can be used to temporarily add players to a queueustats ignore list. It is most commonly used in team modes where you don't want to be seeing your teamate's stats constantly. Modifications to the whitelist done using this command will reset on config reload or Lilith restart.

## /fakechat
`/fakechat <message>`

This is a simple command that will echo back any message you write including color codes. If you want to forge a fake freind request message from your favorite youtuber, this is the command for you.