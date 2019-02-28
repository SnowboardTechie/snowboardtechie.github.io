---
layout: post
title:  "Built my first CLI Gem!!!"
date:   2016-08-11
categories: code update life
---
Today I created a CLI gem that can provide ski reports directly to your terminal. [Ski-Reports](https://github.com/SnowboardTechie/ski-report-cli-gem) is now a published CLI gem on [RubyGems](https://rubygems.org/) and can be installed using ```gem install ski-report-cli-gem```. Once installed it can be accessed anytime by entering ```ski-report``` into your terminal.

When launched the gem will ask you to select a state. Once you have selected a state the gem scrapes data from [OnTheSnow.com](http://www.onthesnow.com) to provide an up to date report on recent snowfall and base totals in your state.

In its current state the gem is very simple, but I am hoping to expand it with more information and even better user interaction in the future (i.e. being able to pick states by abbreviation like 'CA' for California). If anyone would like to look at the source code it can be found at [https://github.com/SnowboardTechie/ski-report-cli-gem](https://github.com/SnowboardTechie/ski-report-cli-gem) and I am always open to constructive feedback or pull requests.
