---
layout:     post
title:      "Config of Personal Blog-Yifan"
date:       2022-07-01 12:00:00
author:     "Yifan"
catalog: true
tags: [blog]
---

# 1. Configure the local environment

``` shell
# install homebrew on mac
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
# install ruby on mac
brew install ruby 
# resolve writing permission issue; following the instruction of this command
brew info ruby
#install required jekyll and bundler
gem install jekyll
gem install bundler
# entring the project dir
cd desktop/skytruine.github.io
# config
bundle install
bundle add webrick
bundle exec jekyll serve
# now we can see the website through localhost:4000
```


