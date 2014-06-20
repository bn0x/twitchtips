---
layout: post
title: HexChat Setup for Twitch Chat
description: "Connecting to Twitch IRC can be quite the task for those not knowledgeable with IRC client, check out how you can set yourself up connecting to Twitch chats using HexChat."
tags: [twitch,hexchat,irc,twitch,chat,oauth]
draft: true
comments: true
get-started: true
---

Connecting to Twitch IRC can be quite the task for those not knowledgeable with IRC client, check out how you can set yourself up connecting to Twitch chats using HexChat.

#Adding a Network
Navigate to HexChat > Network List (or press ctrl+s)
 
<figure>
    <a href="/images/hexchat_guide/settings.png"><img src="/images/hexchat_guide/settings.png"></a>
</figure>
 
Click **Add** to add a new network. Name it whatever you desire.
 
<figure>
    <a href="/images/hexchat_guide/networklist.png"><img src="/images/hexchat_guide/networklist.png"></a>
</figure>
 
Double-click **newserver/6667** and change it to read **irc.twitch.tv/6667**
 
<figure>
    <a href="/images/hexchat_guide/edit1.png"><img src="/images/hexchat_guide/edit1.png"></a>
</figure>
 
Untick **Use global user information** (if it's ticked) and enter your Twitch user name in the **Nick name** field and your OAUTH token in the **Password** field and click **OK**

>Not sure how to get an OAuth token? Check out this [token generator](http://twitchapps.com/tmi/) created by [@bGeorge](http://www.twitter.com/bgeorge).
 
<figure>
    <a href="/images/hexchat_guide/edit2.png"><img src="/images/hexchat_guide/edit2.png"></a>
</figure>
 
*Note* - You may tick **Connect to this network automatically** to join twitch chat automatically when you start HexChat.
 
<figure>
    <a href="/images/hexchat_guide/autoconnect.png"><img src="/images/hexchat_guide/autoconnect.png"></a>
</figure>
 
Now close the edit network window, select your newly created network and click **Connect**.
 
<figure>
    <a href="/images/hexchat_guide/connect.png"><img src="/images/hexchat_guide/connect.png"></a>
</figure>
 
 
#Joining Channels
Standard IRC context applies here as above.  To join a channel simply type */join #channelname* in the dialogue box.
 
<br>HexChat can be configured to join channels automatically as well.  To do this simply right click an already joined channel and tick **Autojoin**.
 
<figure>
    <a href="/images/hexchat_guide/autojoin.png"><img src="/images/hexchat_guide/autojoin.png"></a>
</figure>

Written by [@GUIpsp](http://www.twitter.com/GUIpsp) based on the [KVIRC setup guide](http://twitchtips.com/kvirc-guide/) by [@Izlsnizzt](http://www.twitter.com/Izlsnizzt).
