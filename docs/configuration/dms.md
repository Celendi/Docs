---
description: How to configure Celendi's DMs
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
