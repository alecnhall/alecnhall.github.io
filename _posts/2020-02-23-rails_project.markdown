---
layout: post
title:      "Rails Project "
date:       2020-02-24 04:15:40 +0000
permalink:  rails_project
---

This project has felt like the best and most straightforward yet. 

I decided that for this project that I wanted to continue around the same concept that I used in my first project. 

My first project I made an app that inventories food items that you have in your pantry. I wanted to do this same thing in my application for this project but this time around I wanted to give the user the ability to add in recipes and view all recipes created by other users.

When we get to the home page of the application, we get taken to a welcome page that gives a brief description of what the application does. This page is unique because it is the only page that is being accesed on this controller and is the root for the page.

Users have a nav bar at the top of the page that changes what is being displayed based upon if a user is currently loged in or not. 

When a user logs in they get almost a dashboard view of what items are in their pantry and the recipes that they themselves have created. If a user has no items or no recipes there will be options to add items ort recipes. I am displaying these two sections on the users homepage through partials that are rendering form other areas in my file tree. This was one of my favorite things that I implemented in this project.

Being able to display this information to a user without them having to navigate all over the place is something that I think can be very valuable for user experience. They also help lock things down and inaccessible. For example, every time I instantiate a new user class a pantry object is instantiated that belongs to that user. This is where they are given the option to add and view items. I didn't want to give the user the ability to have full CRUD actions when it came to the pantry though, but I wanted the user to be able to see what was in it, basically just a show view for their pantry. I did want to give full CRUD for my items though with that being linked through the `_pantry.html.erb` view. Not only does this work but it makes for a nice feeling when navigating through page.

I feel like I was much more methodical when it came to the way that I was learning in this section so the struggles that I experienced during this project were few and far between. The concept that I struggled with the most during the learning process was nested forms and when it came time to implement this into my project It seemed to be something that almost came to me naturally when I started building it. 

I went with a custom user class instead of using the devise gem. This decision was based more upon how I learned and how I imagined the appplication being built rather than any type of functional reasoning. I know that devise is the better way to build out a user authentication and authorization system but I just didn't want to use it at this time.

I really enjoyed building this projecta nd I think it's my best project yet. The further and further we move into the program the more and more confident I feel in my ability to digest and implement the things we are being taught and that's exactly the way I think I should feel at this point. I hope you enjoy my project!

