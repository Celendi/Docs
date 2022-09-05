---
title: Home
description: How to get started with Celendi, learn about Celendi commands and get an overview about the bot!
---
# Welcome to Celendi

Celendi is a multi-functional discord bot designed to be the only bot you need in your server, containing a wide selection of commands from fun to moderation, we have it all!

**Useful links**

[Website](https://celendi.xyz) | [Invite link](https://celendi.xyz/invite) | [Donate](https://celendi.xyz/donate) | [Support server](https://celendi.xyz/discord)

## How do I read the documentation?

Each category of commands has their own page which can be found on the sidebar.  

### Understanding arguments

!!! danger ""
    Do not literally type out &lt;   &gt; [   ] \| etc

**Optional**: \[foo\] means that this argument can be ignored \(this is usually for clearing settings or for using yourself/the current channel\).      
**Optional with default**: \[foo='muted'\] means that it will default to the value if you don't specify anything else.     
**Required**: &lt;foo&gt; means that you _must_ use this argument for the command to work.    
**Many**: &lt;foos...&gt; or \[foos...\] means that you can specify more than one. The reason argument in the ban command is an example of an argument that uses this.   
**Options**: \[foo\|bar\] or &lt;foo\|bar&gt; means that you have different possibilities and you need to choose what one you will use based on what you want to do      
**Mentions:** When there is a @ or # before the argument it means that you need to specify the argument as a **mention**. `@` means that you need to specify a **user mention** and `#` as a **channel mention**.   

Additionally, the bot uses what are called _converters_ which makes specifying roles, members, channels etc easy and fool-proof. When asked to specify a member, you can provide it as mention \(pinging the person\) or as ID. This principle works for every single command where applicable.
