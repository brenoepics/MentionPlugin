# MentionPlugin 2.0

Working with Arcturus Morningstar 3.0.0

if you want a more simple version, here is the link: https://git.krews.org/brenoepic/mentionplugin

if you want a pre-compiled version here is the link: https://github.com/brenoepics/MentionPlugin/raw/master/target/MentionPlugin-2.0.jar
## How to use?
you just need to send 
```@username or @friends or @everyone```
with a message and your friend will receive it.
- Mention with @username at the beginning of the message [x] 
- Mention in anywhere in the message [x]
- Mention all friends with @friends [x] 
- Mention everyone with @everyone [x] 
- BlockMention Command [ ]

<b>with this mention plugin, you can mention anyone without putting the @ at the beginning of the message, the @ can be anywhere</b>

## Translation and configuration
Emulator_texts:
| Key | Default Value |
| ------ | ------ |
| commands.error.cmd_mention.not_self | You cannot mention yourself |
| commands.cmd_mention.message | %SENDER% said: %MESSAGE% |
| commands.cmd_mention.message.sent | You mentioned %RECEIVER% successfully! |
| commands.error.cmd_mention.user_not_found | Sorry, I could not find the mentioned user. |
| commands.cmd_mention.allfriends | all friends |
| commands.cmd_mention_everyone.message | %SENDER% said: %MESSAGE% |
| commands.cmd_mention_everyone.look | ${image.library.url}notifications/fig/%LOOK%.png |
| commands.cmd_mention.look | ${image.library.url}notifications/fig/%LOOK%.png |

 Emulator_settings:
 | Key | Default Value |
| ------ | ------ |
| commands.cmd_mention_friends.prefix | friends |
| commands.cmd_mention.message.delete | 0 |
| commands.cmd_mention.follow.enabled | 1 |
| commands.cmd_mention.message.show_username.enabled | 1 |
| commands.cmd_mention_everyone.follow.enabled | 1 |
| commands.cmd_mention.installed | NEVER CHANGE THIS |

 Permissions:
  | Key | Default Value |
| ------ | ------ |
| acc_mention | 0 |
| acc_mention_friends | 0 |
| acc_mention_everyone | 0 |

<b>How can i install it?<b/>
if you are new and do not know how to compile a plugin, this github comes with a pre-compiled version, [MentionPlugin.jar](https://github.com/brenoepics/MentionPlugin/raw/master/target/MentionPlugin-2.0.jar)
then paste the MentionPlugin.jar file into your emulator's plugins folder (only tested on version 3.0.0) and start the emulator.
to be able to use the commands you need to give permission to the ranks of your hotel, open your database in the permissions table, and change the acc_mention, acc_mention_everyone and acc_mention_friends then type: update_permissions or restart your emulator and that's it, now you have a plugin @ mentions working at your hotel ;)
        
        
Discord: BrenoEpic#9671
