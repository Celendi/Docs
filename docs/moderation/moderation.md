---
description: How to use Celendi's Moderation Commands
---
# Moderation Commands

Ban your friends for no reason at all!

!!! warning ""
    These commands require you to have the appropiate permissions

## Commands

| Usage | Example | Description |
| :--- | :--- | :--- |
| ban &lt;&#64;user\|id&gt; &#91;reason&#93; [delete days=0] | ?ban Justinn bonk delete days=7 | Bans the user |
| cases list | ?cases list | Lists all cases in the server |
| cases &lt;&#64;user&gt; | ?cases &#64;Zyztem  | Shows the cases of a user |
| cases clear &lt;&#64;user\|id&gt; | ?cases clear 785276955645313035 | Clears the cases of a user |
| cases remove &lt;case id&gt; | ?cases remove 1 | Removes a case |
| cases view &lt;case id&gt; | ?cases view 1 | Views a case |
| kick &lt;&#64;user\|id&gt; &#91;reason&#93; | ?kick &#64;Justinnn Decided Celendi Wasnt Cool Enough | Kicks the user |
| lockdown &#91;#channel\|id&#93; | ?lockdown #general | Locks the current or given channel down. |
| lockdown all | ?lockdown all| Locks all channels down. |
| mute &lt;&#64;user\|id&gt; &lt;duration &#91;s, m, d, h&#93;&gt; &#91;reason...&#93; | ?mute &#64;Justinnn 1d Boop | Mutes the user |
| purge &lt;amount\|filter&gt; | ?purge 100 | Purge messages with optional filters |
| purge user &lt;&#64;user\|id&gt; &lt;amount&gt; | ?purge user &#64;Zyztem 100 | Purge messages of a specific member |
| purge bots &lt;amount&gt; | ?purge bots 10 | Purge messages sent by bots |
| purge humans &lt;amount&gt; | ?purge humans 10 | Purge messages sent by humans |
| purge includes &lt;amount&gt; &lt;text&gt; | ?purge includes 100 Dyno | Purge messages that include a specific text |
| purge equals &lt;amount&gt; &lt;text&gt; | ?purge equals 100 Dyno | Purge messages that are exactly equal to a specific text |
| purge starts &lt;amount&gt; &lt;text&gt; | ?purge starts 100 Dyno | Purge messages that start with a specific text |
| purge ends &lt;amount&gt; &lt;text&gt; | ?purge ends 100 Dyno | Purge messages that end with a specific text |
| purge emojis &lt;amount&gt;  | ?purge emojis 69 | Purge messages that have a emojis |
| purge attachments &lt;amount&gt; | ?purge attachments 1 | Purge messages that have attachments |
| purge links &lt;amount&gt; | ?purge links 100 | Purge messages that have links  |
| slowmode &lt;interval &#91;s, m, h&#93;&gt; &#91;channel&#93; | slowmode 6h | Puts the channel in slowmode |
| unban &lt;&#64;user\|id&gt; &#91;reason&#93; | ?unban Justin <3 | Unbans the user |
| unlockdown &#91;#channel\|id&#93; | ?unlockdown #general | Unlocks the current or given channel down. |
| unlockdown all | ?unlockdown all| Unlocks all channels down. |
| unmute &lt;&#64;user\|id&gt; &#91;reason...&#93; | ?unmute &#64;Justinnn Beep | Unmutes the user |
| warn  &lt;&#64;user\|id&gt; &#91;reason...&#93; | ?warn &#64;Justinnn Too cool for school | Warns the user with the given reason |
| warn remove &lt;warn id&gt; | ?warn remove 1 | Removes the warn with the given id |
