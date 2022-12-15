---
description: How to configure Celendi's DMs
ᴴₒᴴₒᴴₒ: true
---
# DMs Configuration

Toggle whether to send direct messages when someone is kicked/banned/warned or muted or change the message the should be sent to the user.
!!! warning ""
    These commands require you to have the `MANAGE_GUILD` permission

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| dms bans &lt;enable\|disable&gt; | ?dms ban enable | Toggle whether to send dms to the target when a user is banned. |
| dms unbans &lt;enable\|disable&gt; | ?dms unban disable  | Toggle whether to send dms to the target when a user is unbanned. |
| dms kicks &lt;enable\|disable&gt; | ?dms kicks enable | Toggle whether to send dms to the target when a user is kicked. |
| dms mutes &lt;enable\|disable&gt; | ?dms mutes disable | Toggle whether to send dms to the target when a user is muted. |
| dms unmutes &lt;enable\|disable&gt; | ?dms unmutes enable | Toggle whether to send dms to the target when a user is unmuted. |
| dms warns &lt;enable\|disable&gt; | ?dms warns disable | Toggle whether to send dms to the target when a user is warned. |
| dms message &lt;bans\|kicks\|mutes\|warns&gt; &lt;dm message...&gt; | ?dms message bans You have been yeeted from &#123;server.name&#125; for &#123;reason&#125; | Customize the message of what a specific action should send. |
| dms message-reset &lt;bans\|kicks\|mutes\|warns&gt; | ?dms message-reset mutes | Reset the message of the action. |
| dms panel | ?dms panel | View the dms panel. |
| dms tags | ?dms tags | View the tags that you can use in the action messages. |

## Tags

These are the tags that can be used in the DMs messages

!!! info
    These are only for the DMs messages, they dont work anywhere else in the bot

### Target Tags

| Tag      | Description | Output |
| :------- | :---------- | :------- |
| &#123;target&#125; | Mention of the target. | &#64;Iliannnn |
| &#123;target.id&#125; | ID of the target. | 597445640129085440 |
| &#123;target.username&#125; | Username of the target. | Iliannnn |
| &#123;target.discriminator&#125; | Discriminator of the target. | 0001 |
| &#123;target.tag&#125; | Tag of the target. | Iliannnn#0001 |
| &#123;target.avatar&#125; | Hash of the target's avatar. | a_c92deb6c3f7558f62caf2ba485c42087 |
| &#123;target.avatarURL&#125; | Image URL of the target's avatar. | <https://cdn.discordapp.com/avatars/597445640129085440/a_c92deb6c3f7558f62caf2ba485c42087.gif> |

### Moderator Tags

| Tag      | Description | Output |
| :------- | :---------- | :------- |
| &#123;moderator&#125; | Mention of the moderator. | &#64;Iliannnn |
| &#123;target.id&#125; | ID of the moderator. | 597445640129085440 |
| &#123;target.username&#125; | Username of the moderator. | Iliannnn |
| &#123;target.discriminator&#125; | Discriminator of the moderator. | 0001 |
| &#123;target.tag&#125; | Tag of the moderator. | Iliannnn#0001 |
| &#123;target.avatar&#125; | Hash of the moderators's avatar. | a_c92deb6c3f7558f62caf2ba485c42087 |
| &#123;target.avatarURL&#125; | Image URL of the moderator's avatar. | <https://cdn.discordapp.com/avatars/597445640129085440/a_c92deb6c3f7558f62caf2ba485c42087.gif> |

### Server Tags

| Tag      | Description | Output |
| :------- | :---------- | :------- |
| &#123;server.id&#125; | ID of the server. | 837028015706996806 |
| &#123;server.name&#125; | Name of the server. | Celendi Support |
| &#123;server.icon&#125; | Icon hash of the server. | a_50611c4d825a46db3195224498757205 |
| &#123;server.iconURL&#125; | Image URL of the server's icon. | <https://cdn.discordapp.com/icons/837028015706996806/a_50611c4d825a46db3195224498757205.gif> |
| &#123;server.verificationLevel&#125; | Level of the server. | HIGH |
| &#123;server.owner&#125; | Mention of the server's owner. | &#64;Zyztem |
| &#123;server.ownerId&#125; | Id of the server's owner. | 785276955645313035 |
| &#123;server.ownerName&#125; | Name of the server's owner. | Zyztem |
| &#123;server.ownerDiscriminator&#125; | Discriminator of the server's owner. | 1992 |
| &#123;server.ownerTag&#125; | Tag of the server's owner. | Zyztem#1992 |
| &#123;server.ownerAvatar&#125; | Avatar hash of the server's owner. | 7db60decd3a6109f48715a448639c6a6 |
| &#123;server.ownerAvatarURL&#125; | Image URL of the avatar of the server's owner. | <https://cdn.discordapp.com/avatars/785276955645313035/7db60decd3a6109f48715a448639c6a6.png> |
| &#123;server.memberCount&#125; | The amount of members in the server. | 39 |

### Action Tags

| Tag     | Description | Output |
| :------ | :---------- | :------- |
| &#123;action.name&#125; | The name of the action. | ban |
| &#123;action.namePast&#125; | The name of the action in the past. | banned |
| &#123;action.duration&#125; | How long the user is/was muted. | 1 hour |
| &#123;action.reason&#125; | The reason of the action. | spamming |
| &#123;action.timestamp&#125; | Timestamp of the time the action happened. | 1577836800 |
| &#123;action.at&#125; | Time the action happened. | Jan 1, 2020, 12:00:00 AM |
