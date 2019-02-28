---
layout: post
title:  "Built my first CLI Gem!!!"
date:   2016-08-11
categories: code update life
---
Today I created a CLI gem that can provide ski reports directly to your terminal. <a href="https://github.com/SnowboardTechie/ski-report-cli-gem" target="_blank">Ski-Reports</a> is now a published CLI gem on <a href="https://rubygems.org/" target="_blank">RubyGems</a> and can be installed using ```gem install ski-report-cli-gem```. Once installed it can be accessed anytime by entering ```ski-report``` into your terminal.

When launched the gem will ask you to select a state. Once you have selected a state the gem scrapes data from <a href="http://www.onthesnow.com" target="_blank">OnTheSnow.com</a> to provide an up to date report on recent snowfall and base totals in your state.

In its current state the gem is very simple, but I am hoping to expand it with more information and even better user interaction in the future (i.e. being able to pick states by abbreviation like 'CA' for California). If anyone would like to look at the source code it can be found at <a href="https://github.com/SnowboardTechie/ski-report-cli-gem" target="_blank">https://github.com/SnowboardTechie/ski-report-cli-gem</a> and I am always open to constructive feedback or pull requests.
