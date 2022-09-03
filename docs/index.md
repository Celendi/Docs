---
title: Home
description: How to get started with Celendi, learn about Celendi commands and get an overview about the bot!
---
# Welcome to Celendi

Celendi is a multi-functional discord bot designed to be the only bot you need in your server, containing a wide selection of commands from fun to moderation, we have it all!

**Useful links**

[Homepage](https://celendi.me) | [Invite link](https://celendi.me/invite) | [Support server](https://celendi.me/discord)

## How do I read the documentation?

### Understanding arguments

!!! danger ""
    Do not literally type out &lt;   &gt; [   ] \| etc

Each category of commands has their own page which can be found on the sidebar.  
**Optional**: \[foo\] means that this argument can be ignored \(this is usually for clearing settings or for using yourself/the current channel\).      
**Optional with default**: \[foo='muted'\] means that it will default to the value if you don't specify anything else.     
**Required**: &lt;foo&gt; means that you _must_ use this argument for the command to work.    
**Many**: &lt;foos...&gt; or \[foos...\] means that you can specify more than one. Massban is an example of a command that uses this.   
**Options**: \[foo\|bar\] or &lt;foo\|bar&gt; means that you have different possibilities and you need to choose what one you will use based on what you want to do      
**Mentions:** When there is a @ or # before the argument it means that you need to specify the argument as a **mention**. `@` means that you need to specify a **user mention** and `#` as a **channel mention**.   

Additionally, the bot uses what are called _converters_ which makes specifying roles, members, channels etc easy and fool-proof. When asked to specify a member, you can provide it a mention \(pinging the person\) or an id. This principle works for every single command where applicable.