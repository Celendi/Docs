---
description: How to use Celendi's welcomer
---
# Welcomer

## Commands

| Name | Example | Usage |
| :--- | :--- | :--- |
| welcome channel &lt;set\|remove&gt; <#channel\|id> | ?welcome channel set #general | Set/remove the welcome/leave channel. |
| welcome message set <#channel\|id> &lt;message...&gt; | ?welcome message set 890590927171764235 Hello! Welcome to Celendi! | Set the welcome/leave message. | 
| welcome message remove <#channel\|id> | ?welcome message remove #general | Remove the welcome/leave message. |
| welcome embed set <#channel\|id> &lt;embed object&gt; | ?welcome embed set 890590927171764235 <br>{title: '{user} joined the server!'} | Set the welcome/leave embed by specifying a raw embed object. |
| welcome embed remove <#channel\|id> | ?welcome embed remove #general | Remove the welcome/leave embed. |
| welcome tags | ?welcome tags | List all the tags you can use in the welcome/leave message/embed. |
| welcome role &lt;set\|remove&gt; <&#64;role\|id> | ?welcome role remove 840320567893688400 | Set/remove the welcome/leave role. |
| welcome panel | ?welcome panel | Open the welcome/leave panel. |

## Tags
These are the tags that can be used in the welcomer

!!! info
    These are only for the welcomer, they dont work anywhere else in the bot

#### Target Tags   
`{target}` - Mention of the target.  
`{target.id}` - Id of the target.  
`{target.username}` - Username of the target.  
`{target.discriminator}` - Discriminator of the target.  
`{target.tag}` - Tag of the target.  
`{target.avatar}` - Hash of the target's avatar.  
`{target.avatarURL}` - Image URL of the target's avatar.
<br>

#### Server Tags  
`{server.id}` - Id of the server.  
`{server.name}` - Name of the server where the actions came from.  
`{server.icon}` - Icon hash of the server.  
`{server.iconURL} `- Image URL of the server's icon.  
`{server.verificationLevel}` - Level of the server.  
`{server.owner}` - Mention of the server's owner.  
`{server.ownerId}` - Id of the server's owner.  
`{server.ownerName}` - Name of the server's owner.  
`{server.ownerDiscriminator}` - Discriminator of the server's owner.  
`{server.ownerTag}` - Tag of the server's owner.  
`{server.ownerAvatar}` - Avatar hash of the server's owner.  
`{server.ownerAvatarURL}` - Image URL of the avatar of the server's owner.  
`{server.memberCount}` - The amount of members in the server.  
<br>

####  Action Tags
`{action.name}`  - The name of the action.  
`{action.namePast}` - The name of the action in the past.  
`{action.timestamp}` - Timestamp of the time the user joined/left.  
`{action.at}` - Time the user joined/left.  
