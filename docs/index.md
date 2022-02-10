# Home

**Useful links**

| [Homepage](https://celendi.me) | [Invite link](https://celendi.me/invite) | [Support server](https://celendi.me/discord) |

### How do I read the documentation?

!!! danger
    Do not literally type out &lt;   &gt; [   ] \| etc

!!! info
    When referencing commands, Mod commands are in **bold**.

Each category of commands has their own page which can be found on the sidebar.  
**Aliases**: \[foo\|bar\] means that you can use either foo or bar  
**Optional**: \[foo\] means that this argument can be ignored \(this is usually for clearing settings or for using yourself/the current channel\)  
**Optional with default**: \[foo='muted'\] means that it will default to the value if you don't specify anything else  
**Required**: &lt;foo&gt; means that you _must_ use this argument for the command to work  
**Many**: &lt;foos...&gt; or \[foos...\] means that you can specify more than one. Massban is an example of a command that uses this. If you wish you use an argument with more than one word, use "double quotes" to let the bot you know what you want.

Additionally, the bot uses what are called _converters_ which makes specifying roles, members, channels etc easy and fool-proof. When asked to specify a member, you can provide it a mention \(pinging the person\) or an id. This principle works for every single command where applicable.
