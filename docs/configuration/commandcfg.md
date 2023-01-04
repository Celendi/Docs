---
description: How to configure Celendi's Command Channel Feature
---
# Command Configuration

Configure how commands behave.
!!! warning ""
    These commands require you to have the `MANAGE_GUILD` permission
!!! danger ""
    These commands will be eventually dropped in favor of slash commands & their configuration menu in the future

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| commandcfg allow-role &lt;command&gt; &lt;add\|remove&gt; &lt;&#64;role\|id&gt; | ?commandcfg allow-role ban add &#64;staff | Allow a specific role to use the command. |
| commandcfg disallow-role &lt;command&gt; &lt;add\|remove&gt; &lt;&#64;role\|id&gt; | ?commandcfg allow-role ban add &#64;staff | Disable a command for a role. |
| commandcfg permissions &lt;command&gt; &lt;add\|remove&gt; &lt;permission&gt; | ?commandcfg permissions ban add KICK_MEMBERS | Set custom required permissions for a command. |
| commandcfg view &lt;command&gt; | ?commandcfg view ban | View the config for a specific command. |
| commandcfg disable &lt;command&gt; &lt;true\|false&gt; | ?comandcfg disable ban true | Disable/re-enable a command. |
