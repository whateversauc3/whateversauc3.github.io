---
layout: post
title: "Some stuff I've learned about Jekyll in a few days of mucking around"
date: 2019-05-08 23:42:55 -0700
---

Greetz!

It's your pal sauc3, back again for the third day in a row. I wanted to share with you a little bit of the stuff I've learned about Jekyll in the first few days of messing around. I was going to share some stuff I've learned about git as well but I'm going to save that for a future post when I've got a bit more confidence in what I'm doing. Anyway, here are a few things I've learned about Jekyll, in no particular order.


#### Themes are a bit of a hassle

One of the first things I thought I read about Jekyll was that it was difficult to set up. I was feeling pretty smart when I had managed to get a basic site up and running in my first day, while at the same time learning git. I became much more frustrated when I tried to change the default theme and the page broke. I had (what I thought was) a smart though this morning, to clone the repo for a theme I like (hacker) and then add my changes to that. This worked out pretty nicely, but I still have a few tweaks to the theme I want to sort out before I'm totally happy though.

#### Write a bash alias for annoying tasks

Something that quickly got on my nerves when I was making a bunch of commits was typing the phrase "git push -u origin master" over and over again. So I added a quick line to my ~/.bashrc profile to make an alias such that whenever I type gp it executes the command for me. Below is a sample of what that code looks like, if you've never updated your .bashrc file just type the following

`bash
vim ~/.bashrc`

Once inside the file, add the following line:

`alias gp='git push -u origin master'`

then all you'll need to do to update your repo is type gp. I'm planning on having more extensive tips and tricks for GNU/Linux later, so keep an eye out for that.

#### Now for something completely different

I'm splitting up my vacation time between this blog and porting an exploit to Metasploit. I hope to have a blog post on that subject as well.

For now, I'm going to leave it here. It's dinner time and I'm going to go wolf down some food.

Cheers and HACK THE PLANET!
