---
layout: post
title: Rails Reseed Gem
date: '2015-06-11 22:11:16'
excerpt: "My first gem, and my first open sourced gem to help you with your rails projects"
---

Recently I read an [article by Nithin Bekal](http://nithinbekal.com/posts/rake-db-reseed/) describing a nice rake task to setup which will allow you to test your seeds file and also give your projects a nice fresh start or clean point.
I found this very useful and thought, I don't really want to copy this code into every project, why not turn it into a gem. So I did.

And thus the Rails Reseed gem was born.
Simply add it to your gemfile under the development group and you will now have access to a new rake command `rake db:reseed` which will drop the database, create a new database, run your migrations and run your seeds file.

It is very simple but extremely useful. You can check it out on [rubygems](https://rubygems.org/gems/rails_reseed) or on [github](https://github.com/pixelstack/reseed).
Feel free to create an issue and request anything, suggestions or even make a PR with anything helpful.

Listen to the coder catchup podcast to get an early overview of the gem.

<iframe frameborder='0' height='36px' scrolling='no' seamless src='https://simplecast.fm/e/12691?style=light' width='100%'></iframe>
