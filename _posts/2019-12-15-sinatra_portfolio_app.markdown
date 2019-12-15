---
layout: post
title:      "Sinatra Portfolio App"
date:       2019-12-15 23:04:23 +0000
permalink:  sinatra_portfolio_app
---

For my Sinatra Portfolio project I chose to do an app that creates pantries and inventories the items in those pantries. This is the first step in a much larger app that I want to create, but I digress.

The first thing I tried to do was review everything that we had covered and make sure that I understood all of the different requirements of the project and understood those concepts. The thing that I struggled with most was my routes and determining how they needed to interact with one another to get where I wanted to go.

I started by creating my 3 models and deciding how they related to each other. Obviously a user is going to have many of something, and in the case of my app that would be the pantries. Those pantries belong to users and they also have many items. Finally the items belong to pantries.

I then created my migrations for all of my tables. I quickly realized I didn't create anyway for me to attach my foreign keys, so I added in ways to map my users to pantries and pantries to items by adding a user_id column to pantries and pantry_id coulmn to items. This ensured that my items would belong to the correct objects.

I then started with my routes. I had a hard getting anything to appear on my page besides my login or signup options and then I realized I forgot to add my yield to my layout page. After this I was off to the races. I was very methodical about making sure each page worked before moving onto the next. Creating my route for what action I wanted to perform and then creating the view for that page and how I wanted it to be layed out.

Layout of the page is still something that I am trying grasp but the example page provided me enough of a road-map that I was able to get it all figured out. 

Overall I found that it was hardest targeting the objects that I wanted to manipulate or create. I do think that with more practice this will almost become second nature when creating things in the future. I hope you enjoy my app and please feel free to clone and commit as you want.
