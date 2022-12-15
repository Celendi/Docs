---
description: How to configure Celendi's Welcomer
ᴴₒᴴₒᴴₒ: true
---
# Welcomer Configuration

Manage the welcome/leave channel, message and role
!!! warning ""
    These commands require you to have the `MANAGE_GUILD` permission

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| welcome channel &lt;set\|remove&gt; &lt;#channel\|id&gt; | ?welcome channel set #general | Set/remove the welcome/leave channel. |
| welcome message set &lt;#channel\|id&gt; &lt;message...&gt; | ?welcome message set 890590927171764235 Hello! Welcome to Celendi! | Set the welcome/leave message. |
| welcome message remove &lt;#channel\|id&gt; | ?welcome message remove #general | Remove the welcome/leave message. |
| welcome embed set &lt;#channel\|id&gt; &lt;embed object&gt; | ?welcome embed set 890590927171764235 &#123;title: '&#123;user&#125; joined the server!'&#125; | Set the welcome/leave embed by specifying a raw embed object. |
| welcome embed remove &lt;#channel\|id&gt; | ?welcome embed remove #general | Remove the welcome/leave embed. |
| welcome card set &lt;#channel\|id&gt; | ?welcome card set #general | Set the welcome/leave card to be sent in the welcome message's attachments.|
| welcome card remove &lt;#channel\|id&gt; | ?welcome card remove #general | Remove the welcome/leave card from the welcome message's attachments. |
| welcome card background set &lt;image url&gt; | ?welcome card background set <https://i.imgur.com/zzspCRJ.png> | Set the welcome/leave card's background image. |
| welcome card background set + attachment | welcome card background set UPLOADEDIMAGE | Set the welcome/leave card's background image by attaching an image. |
| welcome card background remove | ?welcome card background remove | Remove the welcome/leave card's background image. |
| welcome card background view | ?welcome card background view | View the welcome/leave card. |
| welcome tags | ?welcome tags | List all the tags you can use in the welcome/leave message/embed. |
| welcome role &lt;set\|remove&gt; &lt;&#64;role\|id&gt;| ?welcome role remove 840320567893688400 | Set/remove the welcome/leave role. |
| welcome panel | ?welcome panel | Open the welcome/leave panel. |

!!! info
    The recommended background image size is 1024x500. The image will be resized to fit the background.

## Tags

These are the tags that can be used in the welcomer

!!! info
    These are only for the welcomer, they dont work anywhere else in the bot

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
| &#123;action.name&#125; | The name of the action. | join |
| &#123;action.namePast&#125; | The name of the action in the past. | joined |
| &#123;action.timestamp&#125; | Timestamp of the time the user joined/left. | 1577836800 |
| &#123;action.at&#125; | Time the user joined/left. | Jan 1, 2020, 12:00:00 AM |

### Welcome Card Tags

| Tag     | Description | Output |
| :------ | :---------- | :------- |
| {card.url} | URL of the welcome card. | <https://media.tenor.com/8qTl-eokkR4AAAAC/uwu-smug.gif> |
