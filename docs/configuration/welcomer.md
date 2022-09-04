---
description: How to configure Celendi's Welcomer
---
# Welcomer Module
Manage the welcome/leave channel, message and role
!!! warning ""
    These commands require you to have the `MANAGE_GUILD` permission

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| welcome channel &lt;set\|remove&gt; &lt;#channel\|id&gt; | ?welcome channel set #general | Set/remove the welcome/leave channel. |
| welcome message set &lt;#channel\|id&gt; &lt;message...&gt; | ?welcome message set 890590927171764235 Hello! Welcome to Celendi! | Set the welcome/leave message. | 
| welcome message remove &lt;#channel\|id&gt; | ?welcome message remove #general | Remove the welcome/leave message. |
| welcome embed set &lt;#channel\|id&gt; &lt;embed object&gt; | ?welcome embed set 890590927171764235 <br>{title: '{user} joined the server!'} | Set the welcome/leave embed by specifying a raw embed object. |
| welcome embed remove &lt;#channel\|id&gt; | ?welcome embed remove #general | Remove the welcome/leave embed. |
| welcome tags | ?welcome tags | List all the tags you can use in the welcome/leave message/embed. |
| welcome role &lt;set\|remove&gt; &lt;&#64;role\|id&gt;| ?welcome role remove 840320567893688400 | Set/remove the welcome/leave role. |
| welcome panel | ?welcome panel | Open the welcome/leave panel. |

## Tags
These are the tags that can be used in the welcomer

!!! info
    These are only for the welcomer, they dont work anywhere else in the bot

#### **Target Tags**   
| Tag      | Description | Output |
| :------- | :---------- | :------- |
| {target} | Mention of the target. | &#64;Iliannnn |
| {target.id} | ID of the target. | 597445640129085440 |
| {target.username} | Username of the target. | Iliannnn |
| {target.discriminator} | Discriminator of the target. | 0001 |
| {target.tag} | Tag of the target. | Iliannnn#0001 |
| {target.avatar} | Hash of the target's avatar. | a_c92deb6c3f7558f62caf2ba485c42087 |
| {target.avatarURL} | Image URL of the target's avatar. | https://cdn.discordapp.com/avatars/597445640129085440/a_c92deb6c3f7558f62caf2ba485c42087.gif |

#### **Server Tags**
| Tag      | Description | Output |
| :------- | :---------- | :------- |
| {server.id} | ID of the server. | 837028015706996806 |
| {server.name} | Name of the server. | Celendi Support |
| {server.icon} | Icon hash of the server. | a_50611c4d825a46db3195224498757205 |
| {server.iconURL} | Image URL of the server's icon. | https://cdn.discordapp.com/icons/837028015706996806/a_50611c4d825a46db3195224498757205.gif |
| {server.verificationLevel} | Level of the server. | HIGH |
| {server.owner} | Mention of the server's owner. | &#64;Zyztem |
| {server.ownerId} | Id of the server's owner. | 785276955645313035 |
| {server.ownerName} | Name of the server's owner. | Zyztem |
| {server.ownerDiscriminator} | Discriminator of the server's owner. | 1992 |
| {server.ownerTag} | Tag of the server's owner. | Zyztem#1992 |
| {server.ownerAvatar} | Avatar hash of the server's owner. | 7db60decd3a6109f48715a448639c6a6 |
| {server.ownerAvatarURL} | Image URL of the avatar of the server's owner. | https://cdn.discordapp.com/avatars/785276955645313035/7db60decd3a6109f48715a448639c6a6.png |
| {server.memberCount} | The amount of members in the server. | 39 |

####  Action Tags
| Tag     | Description | Output |
| :------ | :---------- | :------- |
| {action.name} | The name of the action. | join |
| {action.namePast} | The name of the action in the past. | joined |
| {action.timestamp} | Timestamp of the time the user joined/left. | 1577836800 |
| {action.at} | Time the user joined/left. | Jan 1, 2020, 12:00:00 AM |
