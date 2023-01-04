---
description: How to configure Celendi's Command Channel Feature
---
# Command Channel Configuration

Setup channels where commands can be used.
!!! warning ""
    These commands require you to have the `MANAGE_GUILD` permission

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| command-channel add &lt;#channel\|id&gt;| ?command-channel add #commands | Add a blacklist/whitelist channel. |
| command-channel remove &lt;#channel\|id&gt; | ?command-channel remove #commands | Remove a blacklisted/whitelisted channel. |
| command-channel panel | ?command-channel panel | View information about current mode and channels affected. |
| command-channel mode &lt;whitelist\|blacklist&gt; | ?command-channel mode whitelist | Change the mode of this module. <br>Whitelist - will only work in specific channels. <br>Blacklist - will work in any non-blacklisted channel. |
