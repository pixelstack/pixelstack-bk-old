---
layout: post
title: 'State of the Dev Setup: 2014'
date: '2014-12-02 08:47:15'
excerpt: "My web development setup for 2014 saw some massive changes, from text editors, applications, terminal clients and more"
---

I thought I would write a short article based on this years development environment.
It seems that, as web developers, our stack goes through changes, sometimes very small over time, sometimes not much for a long time, then spikes of new, then back to being the same for a while again. So why not publish my current dev stack that I have been using for the year of 2014.

2014 has been an amazing year, working for [Copirite](http://copirite.com.au] a design, web and print company on the Gold Coast in Australia.
My role has required me to build many web apps/website hybrids, these are sites that require a bit more than your standard WordPress/Drupal/Other Out of/Semi out of the box CMS. Rails has been the choice since I started working there for a majority of the projects, and I can't see many if any that I would change after the projects have been completed.

My stack is as follows:

## Hardware
- Retina MPB
- Dual Monitor Setup with laptop in clamshell mode (24inch screens)
- Blue Yeti microphone (fairly recent)
- Misc Apple devices (yea its a give in, I love Apple products)

## Software
- Vim
- Tmux
- iTerm
- Google Chrome
- Firefox
- Safari
- Paw HTTP Rest Client
- Adobe Creative Cloud
- Sketch
- Skype
- Screenhero
- Airmail
- Dropbox
- Alfred
- Dash
- Evernote
- Hazel
- Screenflow
- Monosnap

## Services
- Github
- Codeship
- CodeClimate
- devbase.io
- Egghead.io
- Feedly
- Twitter
- Slack
- Digital Ocean

## Technologies
- Ruby on Rails
- WordPress
- Drupal (small amount)
- Jekyll
- Bower
- Grunt
- Gulp
- Sass
- Ruby
- chruby
- Ruby Install

## Workflow
Generally my workflow is with rails applications. While I started out using pow for nearly every project, I have gone back to good old rails s.

I have been using a terminal based workflow, using tmux sessions with Tmuxinator and vim as my editor of choice. This leaves me in the terminal most of the time (at least one monitor making up the terminal, another for web browsers etc).

I have used atom on the rare occassion as well (without the vim bindings), which is a nice editor, but I still feel at home in vim.

I have changed from using RVM as my ruby version manager/switcher, to using chruby and ruby install. I love RVM, and it solved a lot of issues, but after switching to chruby, it feels a lot lighter and a lot nicer. RVM 2 is in the works, I may look at it again, but for a simple ruby switcher, chruby covers everything I need.

I have been dabbling in Chef to automate some infrastructure but have found myself now really loving ansible, its just much more digestible and less of a learning curve.
While I am not using any of them in production I will be in 2015, hopefully along with docker (at least for my local dev environments for new projects).

All projects are still kept in git, most being hosted on GitHub, but some through gitlab on a private server I have. Which reminds me, Digital Ocean is my current server provider of choice, they have been fantastic and have suited every project I have had to work on.

Anyway that is it for now, I may do a revised post of this at the end of the year / start of 2015 just incase anything changes.
