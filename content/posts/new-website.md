---
title: "New Website!"
date: 2021-06-19T22:01:33-05:00
draft: false
toc: false
images:
tags:
  - nginx
  - hugo
  - digitalocean
---
Hello!

I just made a website. This is the first website that I’ve hosted on the internet, very exciting! I decided to do it by renting a virtual machine from Digital Ocean and installing Nginx on it. I’m using go’s Hugo static site generator because I found a nice [theme](https://github.com/rhazdon/hugo-theme-hello-friend-ng) that I wanted to use, and I didn’t need this site to be too complex.


Because I now have a server and a site, I’m planning on making a websocket using Elixir and Cowboy, then serve the data to the front and verify a game like chess or checkers. I’ll probably use a genserver to maintain state; then, I won’t have to worry about setting up a database. I think it will be cool if I can get it working.
