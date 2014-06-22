---
layout: post
title: NetCat Setup Guide for Twitch IRC
description: "Connecting to anything is really hard with netcat, but for all your plebs that want to become elite hackers! I got your back!"
tags: [twitch,netcat,irc,twitch,chat,oauth]
comments: true
get-started: true
---

Connecting to anything is really hard with netcat, but for all you plebs that want to become elite hackers! I got your back!

#Connecting to the network
Open up your CLI (Terminal/CMD) > "nc"

<figure>
    <a href="/images/netcat_guide/nc.png"><img src="/images/netcat_guide/nc.png"></a>
</figure>

Type in "irc.twitch.tv 6667" telling it to connect to irc.twitch.tv on port 6667

<figure>
    <a href="/images/netcat_guide/connect.png"><img src="/images/netcat_guide/connect.png"></a>
</figure>

We need to send our password first like "PASS oauth:youroauth" or for example "PASS oauth:aheznwk3x9a6k7qasdsdu6y2g1vms"
Then type in "NICK yourusername" or for example what I would do: "NICK obnoxious" then hit enter.

<figure>
    <a href="/images/netcat_guide/login.png"><img src="/images/netcat_guide/login.png"></a>
</figure>

If you're banned, or the username doesn't exist you'll immediately get a Login Unsuccessful.
If it was successful you'll be greated with ":tmi.twitch.tv 001 plaugingtg :Welcome, GLHF!" or similar.

<figure>
    <a href="/images/netcat_guide/success.png"><img src="/images/netcat_guide/success.png"></a>
</figure>

**Note:**If you were logged in successfully you should have been sent "PING :0x923ff90" or similar a bit after, send back "PONG :0x923ff90"
**You must do this everytime you're sent a PING (remember elite hackers have no problem with this!)

#Joining a channel
Put in "JOIN #lowercasechannelhere" or for example: "JOIN #obnoxious"
You should within the next 10 seconds be in a channel.

<figure>
    <a href="/images/netcat_guide/channel.png"><img src="/images/netcat_guide/channel.png"></a>
</figure>


#Messaging a channel
Send the data "PRIVMSG #lowercasechannelhere :message you want to send" or for example "PRIVMSG #obnoxious :Hello I use netcat because I like to think I'm an elite hacker!"
**Note:** Elite hackers do use netcat, contrary to popular belief.
**Note:** You must first join a channel before you're able to send it messages.

<figure>
    <a href="/images/netcat_guide/message.png"><img src="/images/netcat_guide/message.png"></a>
</figure>