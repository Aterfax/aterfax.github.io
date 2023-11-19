---
layout: post
title:  "Testing Urbackup image restoration"
date:   2023-11-19 17:21:59 +0000
categories: backups urbackup blog
---

# Testing Urbackup image restoration

Having backups is important. Testing that your backups actually work is even more important! This was something I did this weekend in my homelab with a temporary Windows 11 VM. 
Having created it, destroyed it and restored it with Urbackup I am happy things are working nicely. That said, in the process of testing I use the Urbackup ISO and mounted it since there was no immediately available Netboot.xyz config to boot it over the network.

So I fixed that by making one. This can be seen below in the Gist I wrote to document the process: 

{% gist f2d42ba55b08a3868cfe7cd05ff9c244 %}
