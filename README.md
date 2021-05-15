# MentionPlugin
Arcturus-Morningstar MentionPlugin

if you want a more simple version, here is the link: https://git.krews.org/brenoepic/mentionplugin

if you want a pre-compiled version here is the link: 
## How to use?
you just need to send 
```@username or @friends or @everyone```
with a message and your friend will receive it.
@username mention someone
@friends mentions all your friends
@everyone mentions all users online.

<b>with this mention plugin, you can mention anyone without putting the @ at the beginning of the message, the @ can be anywhere</b>

## Translation and configuration
Emulator_texts:
```txt
        "commands.error.cmd_mention.not_self" = "You cannot mention yourself"
        "commands.cmd_mention.message" = "%SENDER% said: %MESSAGE%"
        "commands.cmd_mention.message.sent" = "You mentioned %RECEIVER% successfully!"
        "commands.error.cmd_mention.user_not_found" = "Sorry, I could not find the mentioned user."
        "commands.cmd_mention_everyone.message" = "%SENDER% said: %MESSAGE%"
        "commands.cmd_mention.allfriends" = "all friends"
 ```
 Emulator_settings:
 ```txt
    "commands.cmd_mention_friends.prefix" = "friends"
    "commands.cmd_mention.message.delete" = "1"
    "commands.cmd_mention.follow.enabled" = "1"
    "commands.cmd_mention.installed" = "1"
    "commands.cmd_mention.message.show_username.enabled" = "0"
    "commands.cmd_mention.look" = "${image.library.url}notifications/fig/%LOOK%.png"
    "commands.cmd_mention_everyone.look" = "${image.library.url}notifications/fig/%LOOK%.png"
    "commands.cmd_mention_everyone.follow.enabled" = "1"
```
 Permissions:
 ```txt
    acc_mention", "acc_mention_friends", "acc_mention_everyone"
```

<b>How can i install it?<b/>
if you are new and do not know how to compile a plugin, this github comes with a pre-compiled version, [MentionPlugin.jar](https://breno.com)
then paste the MentionPlugin.jar file into your emulator's plugins folder (only tested on version 3.0.0) and start the emulator.
to be able to use the commands you need to give permission to the ranks of your hotel, open your database in the permissions table, and change the acc_mention, acc_mention_everyone and acc_mention_friends then type: update_permissions or restart your emulator and that's it, now you have a plugin @ mentions working at your hotel ;)
