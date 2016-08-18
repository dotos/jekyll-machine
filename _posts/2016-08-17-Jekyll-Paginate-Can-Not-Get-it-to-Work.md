---
layout: post
title:  "Jekyll Paginate - Can’t Get it to Work"
date:   2016-08-17 15:48:44
categories: [jekyll update]
tags: [Gemfile,Bundler]
---
Try using Bundler to manage gem dependencies instead of vanilla `jekyll serve`. You probably have multiple versions of the gems installed and that could be causing you issues.

Create a `Gemfile` with the following

``` bash
source "https://rubygems.org"

gem "jekyll"
gem "jekyll-paginate"
```
<!--more-->
Run `bundle install`

Then `bundle exec jekyll serve` or `bundle exec jekyll build`

You could also try `gem uninstall jekyll-paginate` and remove all but the latest version.