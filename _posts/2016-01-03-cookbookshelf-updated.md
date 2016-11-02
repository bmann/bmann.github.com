---
title: Cookbook Shelf Updated
date: 2016-01-03 00:00:00 Z
categories:
- CookbookShelf
layout: post
---

I finally got back to properly generating [bmann/cookbookshelf](http://github.com/bmann/cookbookshelf), now that I blew the dust off my Jekyll coding. See it at [projects.bmannconsulting.com/cookbookshelf](http://projects.bmannconsulting.com/cookbookshelf/)

Of course, the very very funky way I am playing with [trimming ingredients for the archive page](https://github.com/bmann/cookbookshelf/blob/gh-pages/archive.html) just goes to show that Liquid Template / static sites are a bit funky for this sort of thing.

The [category index on my bmannconsulting.com site](http://www.bmannconsulting.com/categories/) kind of does this, but my challenge is parsing down ingredients into "base" elements, so that "1 garlic clove, minced" knows that it is just "garlic".

Probably an easier way to do this would be to make a list of canonical ingredients, and if an ingredient line item contains one of them, it gets added.

More thinking about this in the [colophon for the site](http://projects.bmannconsulting.com/cookbookshelf/colophon).