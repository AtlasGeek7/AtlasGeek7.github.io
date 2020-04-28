---
layout: post
title:      "My first Ruby on Rails App"
date:       2020-04-28 15:30:19 -0400
permalink:  my_first_ruby_on_rails_app
---

Today I learned Ruby and had quite some time to experiment with Ruby on Rails. As I am already familiar with back-end programming and this is mainly a server-side project , I decided to create a simple CRUD application with RoR and just some basic HTML.
So, if you want to learn how to use React with RoR, then follow along...

**rails new**
Almost all Rails applications start by running rails new command. This handy command creates a skeleton Rails application in a directory we choose.
As we can see rails new automatically runs the bundle install command after the file creation is done. Notice that the rails command creates numerous files and directories.

**Gemfile**
After creating a new Rails application, Bundler is run automatically (via bundle install) by the rails command. Unless we specify a version number to the gem command, Bundler will automatically install the latest version of the gem.
We can specify each version of gem as done in Bundler to force Bundler to install specified version.

**Rails Server**
By running rails new and bundle install, we already have an application we can run since Rails comes with a command-line program, or script, that runs a local web server, visible only from our development machine.

![](https://drive.google.com/uc?export=view&id=1G2cnxiJqXQuI_QyfAn_xYag441h7z433)

The output shows that the application is running on port number 3000. This address tells the computer to listen on every available IP address configured on that specific machine; in particular, we can view the application using the special address 127.0.0.1 (localhost).

That's about it for now... Happy coding !!!
