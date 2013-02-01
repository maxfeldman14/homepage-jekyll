---
layout: post
category: blog
title: "An Actual Update"
description: "A more detailed recap of my first few weeks in Costa Rica"
---
{% include JB/setup %}
###Costa Rica
Costa Rica is going well.
The farthest I've travelled so far is to Manuel Antonio National park, a great beach that has monkeys.
I've also been able to visit the Irazu volcano. Although it was cloudy when we visited, it was very pretty.
The day after visiting Irazu I went with my host family to a coffee fair (I forget exactly where).
The drive there was beautiful, and we were able to see all of San Jose from the hills.
The fair itself was also fun.
I purchased a few kilograms of coffee, which I will be sending to the US as soon as I actually visit the post office.

I've gotten lost in the city several times now, either while running or while searching for one of the rock climbing gyms. On the bright side, I have successfully located one of the gyms.
The other day some friends from class and I found the basketball court on UCR's campus.
It was a bit up a hill, but the location is great.
We saw several colorful birds while playing.

Last night I went to Escazu, which had a very nice shopping center with restaurants and shops.
We went to a happy-hour-type place, and then a sushi restaurant, both of which were tasty and fun.

Other than Spanish, I've been playing guitar (I bought a cheap one at the mall), practicing Russian, and finishing this site so I can move on to other projects.

###Technical stuff
I've switched my site from Rails to [jekyll](http://jekyllrb.com), so posting blog updates will be easier. 
My site uses Twitter Bootstrap for styling now, but there are still some things I would like to change.
It seems like overflow isn't handled quite like I would prefer.
There are also a few changes I'm going to make so that pictures will be easier to include and display.
Additionally, unicode characters don't display properly, so for the time being I am not using them (Irazu and Escazu should have acute accent makrs over their 'u's).

Also, for some reason Heroku stopped properly parsing the HAML I used in this website.
I attempted to update with new content, but Ruby application updates were disabled due to a rubygems vulnerability (more details [here](https://status.heroku.com/incidents/489).
When I was finally able to push the new post, HAML was no longer parsed, leaving things looking very ugly.
For the time being I've stopped using HAML.

The site should have support for OpenGraph now, though, hooray!
