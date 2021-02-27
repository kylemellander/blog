---
layout: post
title:  "Starting a New Rails App in Docker"
date:   2021-02-26 19:49:25 -0800
categories: rails docker
---
I was recently wanting to find an easy way to build an project app and be able to distribute it to various services.  I want to be able to both run this in my dev environment and on a production environment without having to fuss over everything. So, I chose Docker.

# Why Docker?

Docker creates containers which allow you create a consistent environment that will run your app.  No matter where that app is deployed, it will run with the same conditions, so you can know that it will run consistently whereever you deploy it!

# How am I going to format this?

I have worked with Docker before, but I haven't set up a container from start to finish, so I'm going to be logging what I'm doing in these posts. I might clean things up to a better format once I have finished, but for now, this is my process!
