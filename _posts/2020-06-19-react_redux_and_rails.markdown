---
layout: post
title:      "React Redux and Rails"
date:       2020-06-20 00:29:23 +0000
permalink:  react_redux_and_rails
---


Seeing everything come together in Flatiron Journey has been amazing, and I have finally reached the culmination of it with React, Redux, and Rails.

At the start of the section, I was excited and ready. React came to me very easily and I was able to work through sections with relative ease and then I hit Redux. I wanted to make Redux the bulk of this blog post and my experience using and learning it.

Redux is a tool that allows you to have global state, and pass down that state to individual components with a mapStateToProps function. At first it may seem like an extra step even for a small app but overall it provides a better way of interacting with state. Instead of passing props from component to component you simply map state to whichever component you choose. This helps with simplifying how you interact with state.

Redux is made up of a store, action, and reducers. The store which is initialized at the root of the app holds all state in the program. Actions are what you want to do with the information, get, post, patch, etc...., and reducers determine which action you want to call.

When I first began with redux it seemed like a terrifying concept that would take me forever to learn, but as I used it more and more in my project the more I became comfortable with the pattern of how it works and how to implement it. So, my word of advice for anyone who is looking at working with redux is to stay persistent and practice it as much as possible. It's intimidating, but staying with it will reap you many rewards and help simplify how your app interacts with state.
