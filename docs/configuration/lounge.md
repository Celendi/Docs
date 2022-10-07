---
description: How to configure Celendi's Lounge feature
---
# Lounge Configuration

Create or configure lounge channels.
!!! warning ""
    These commands require you to have the `MANAGE_CHANNELS` permission

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| lounge create &lt;#channel\|id&gt; &lt;id&gt; &#91;name...&#93; | ?lounge create 1017876201181806772 Create A Lounge | Create a lounge channel. |
| lounge delete &lt;#channel\|id&gt; | ?lounge delete #Create Your Lounge | Delete a lounge channel. |
| lounge maxusers &lt;#channel\|id&gt; &lt;number&lt; | ?lounge maxusers 1017876201181806772 3 | Set the maximum number of users a lounge channel can have. |
| lounge name &lt;#channel\|id> &lt;name...&gt; | ?lounge name #Create your lounge {target.username}'s Lounge | Set the name of a lounge channel. |
| lounge tags | ?lounge tags | List all tags that can be used in the lounge channel names. |
| lounge list | ?lounge tags | List all lounge channels. |

## Tags

These are the tags that can be used in the lounge

!!! info
    These are only for the lounge feature, they dont work anywhere else in the bot

### Category Tags

| Tag      | Description | Output |
| :------- | :---------- | :------- |
| {category.id} | ID of the lounge category. | 882288400323981433 |
| {category.name} | Name of the lounge category. | Voice And Video |

### Target Tags

| Tag      | Description | Output |
| :------- | :---------- | :------- |
| {target.id} | ID of the target. | 785276955645313035 |
| {target.username} | Username of the target. | Zyztem |
| {target.discriminator} | Discriminator of the target. | #1992 |
| {target.tag} | Tag of the target. | Zyztem#1992 |
