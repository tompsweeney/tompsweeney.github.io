---
title: Projects
---

## [MTG Remote](https://mtgremote.tomsweeney.ca)

My friends and I started playing Magic: The Gathering over webcam using Google Hangouts. We needed a way to easily display life totals and cards on the hangout stream so I developed a tool to do just that. It allows 

## Tetra Master DS

I developed a Nintendo DS homebrew version of the Tetra Master card game from Final Fantasy IX. The card art was pulled right out of the original game, so this may have been in a legal grey area. I released several versions of this game and posted them on the gbadev forums. 

## Spelunky DS

I'm a huge fan of [Spelunky](http://spelunkyworld.com). Before the HD version came out, I attempted to port the original from GameMaker to the Nintendo DS. During development I ran into a crash bug that I must have spent a whole month trying to debug. Eventually I gave up and moved on. 

## Packer Scripts

For a while I was really into the idea of provisioning a super lightweight Linux virtual machine using packer/vagrant. It was a basic LAMP stack using the PHP FastCGI Process Manager. I disabled any apache modules that weren't needed, locked the system down using SELinux policies (this was an absolute nightmare), set up mod_security to enforce owasp rules (another giant nightmare) and set up mod_evasive to ban any IPs that tried to DDOS the server. I'm actually very happy with my results on this project. I deployed the resulting virtual machine on AWS and ran my previous blog on it.

