---
title: "Home Server and Spare Parts"
date: 2026-09-28
---

Answer me this, dear reader: Do you have an old computer laying around? Perhaps one or two old Hard drivers? What about an old laptop, perhaps? How wonderful would it be if we could use those spare old parts for something greater and useful in this day and age. 

Now, what if I tell you there is something. A home server. A machine capable of replacing Google Driver, Docs, Sheets. Replace the greedy media providers like Netflix and Spotify. Your own VPN.  

That is what I started a few months ago, and that is what I'd like to share now

# The Machine

It all started with a bunch of Hard drivers. Random HDDs and SSDs of varying sizes, surely we can put those to good use. For the server itself, my options were a 4GB memory laptop or a 6GB mini PC. The rest of the specs do no matter, these are crappy machines for today's standards of usage. But for a server, that is plenty. We don't have much, but those services do not need much so they work very well together.

I'd love to have picked the laptop, only because of the battery. Having that life support is huge to keep services up. But my old laptop didnt have a working one, so I went with the mini PC just because it was smaller.

Now, how do you connect 4 Hard Drivers to a mini pc? It only have 1 Hard driver slot!

The answer: **USB adpters**

This might be the worst way to connect a hard driver, I hear you say. A bulkier and slower Flash drive. 

YES! You are 100% correct. It is a terrible idea for a server, but it works.

> Perfect is the enemy of the good - Voltaire (?)

I don't need the perfect machine with the perfect connections and perfect solution. I need a solution that works, and, more importantly, a solution that works for me! And so far, it has been working wonders.

The computer runs, it is connected to the Network and the 4 Hard drivers work, reaching a wopping 1.67Tb. 

Now here is another question: If a scrappy computer can become a decent server why can't a phone, which is way more powerful, become one. Wait a minute...

# The Phone

We all hear that a smartphone today is way more powerful than the computers that sent people to the moon, but until a few months ago, I've never fully internalized this. Take Google's OnePlus 8 PRO from 2020: 12GB of RAM, 8 cores processor, 200GB of Disk. HOLY MOLLY that is Huge! PLUS! Has Wifi AND SIM Card (Internet Redundancy) a battery that lasts HOURS and a Screen. All fitting in the palm of your hand! 

I'm not ashamed that this realization blew my mind.

But in order to make a server out of it, we have to get rid of that pesky Android OS and unfortunally we have to make some decisions. Going full linux, and you lose some of the Phone Perks like graphics card, camera and other stuff. Going on a Open source OS *may* allow them to be available, but at cost of the services you can install (No Docker for example). So, for this, you have to be trully aware of what purpose this server will be.

Also, 200GB is respectable, but that is it. Expasion is nearly impossible nowadays with phones not allowing for SSD cards and you only have 1 USB entry port to work with. A USB Hub can solve this, but right now, it is serving its purpose.


Alright, now that we have this amazing machines running, Let me tell you the perks!

# The Perks
I don't want to make it too much of a service marketing, so I'm gonna briefly describe the service and my review. But if you need some inspiration, do checkout [this repo for some Awesome Self Hosted services](https://github.com/awesome-selfhosted/awesome-selfhosted).

## Nextcloud
Starting with the main one: [Nextcloud](https://nextcloud.com/). The core usage of this is Google Drive, but this is selling it short. It is basically a google suite, where you can install many different apps that replace tools like Google Docs, Sheets, Productivity, Accounting, Management, but again, Google Drive is the main thing we want to kill here.

You can install on your phone or computer. It automatically syncs the files and upload to your many Hard Drives.

Quick tangent: This does NOT replace a proper backup. I'm not discussing IT stuff here, so please do some reasearch on the topic if you feel interested :)

## Jellyfin
The second thing I wanted was a way to watch movies and animes on the fly, be able to download them and all the good stuff. I went with the [Jellyfin](https://jellyfin.org/) option, mostly because of the open source nature, but Plex was also an alternative. 

Just like, Netflix, you can install on your phone or pc, or straight up access it on the browser and watch whatever **you own**. You do have to populate with shows and movies that you have, which is understandable, but it is demotivating, when you compare with the paid services that already a gigantic catalog of slop to watch.

But with some determination, and the help of the *arr family, mostly [sonarr](https://sonarr.tv/) and [radarr](https://radarr.video/), you can get some momentum on the shows that trully matter to you.

## Misc Services

Rapid fire on other tools I have

- Telegram bot: A very lovely addition. I added commands to check on the server, report status and respond to small requests.
- Cyberfoil: I've been playing of modding my nitendo switch and wanted to have a quick way to manage and download my flashed games
- Forgeja: Why not have your own Git server, so you can version things all those small projects without making them public
- Ad Guard: a network wide ad blocker. Amazing! but still testing it
- Zigbee2MQTT: Smart home hub, but this is a conversation for another day.

# Endcard

I started this project 5 months ago, and I'm still tinkering with it. Fixing things and installing new stuff has been pretty fun and you can also share with family and friends. Of course, this is not a guide and I don't want you bore you to death with the thrills of spending hours Configuring DNS. But hey, if you do wanna talk about it, get away from me. Fuck that shit. Hours spent just to make a ping work.

**Yours truly**
