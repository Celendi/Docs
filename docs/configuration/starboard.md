---
description: How to configure Celendi's Starboard
ᴴₒᴴₒᴴₒ: true
---
# Starboard Configuration

Set up, remove or manage the starboard in this server.
!!! warning ""
    These commands require you to have the `MANAGE_GUILD` permission

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| starboard &lt;#channel\|id&gt; | ?starboard #starboard | Set the channel where the starboard will be. |
| starboard limit &lt;number&gt; | ?starboard limit 3 | Set the limit of stars needed to be added to the starboard. |
| starboard nsfw &lt;true\|false&gt; | ?starboard nsfw false | Toggle wether messages marked as NFSW can be added to the starboard. |
| starboard bots &lt;true\|false&gt; | ?starboard bots false | Toggle wether bots reactions count for the star count. |
| starboard self &lt;true\|false&gt; | ?starboard self true | Toggle wether the user who added the reaction can star their own messages. |
| starboard stats &#91;&#64;user\|id&#93; | ?starboard stats &#64;Zyztem | Show the starboard stats of a user. |
| starboard show &lt;message_id&gt; | ?starboard show 1027759604622434324 | Show a message that was added to the starboard. |
| starboard jump &lt;true\|false&gt; | ?starboard jump true | Toggle wether the bot will add a button to jump to the original message. |
| starboard emoji &lt;emoji&gt; | ?starboard emoji ⭐ | Set the emoji that will be used to star messages. |
| starboard panel | ?starboard panel | View the starboard panel. |
| starboard blacklist add &lt;#channel\|id&gt; | ?starboard blacklist add #commands | Blacklist a channel from having their messages starred. |
| starboard blacklist remove &lt;#channel\|id&gt; |?starboard blacklist remove #commands | Unblacklist a channel from having their messages starred. |
| starboard remove | ?starboard remove | Remove the starboard from the server. |
