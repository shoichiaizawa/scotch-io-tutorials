Learn Meteor.js From Scratch: Build a Polling App
=================================================

Code for the scotch.io tutorial by [@sevilayha](https://github.com/sevilayha)

https://scotch.io/tutorials/learn-meteor-js-from-scratch-build-a-polling-app

What is Meteor?
---------------

Meteor.js is:

- an open-source platform built on Node and MongoDB

Is it comparable to Angular?

- Angular handles just the frontend parts of application
- Meteor handles:
  - both server and client-side code and;
  - a lot of the parts of applications that need to be created manually in Angular

Important Things to Know
------------------------

- **Real time built into its core:** Meteor handles all of the real-time components so that as soon as you update something in your database, that change is made to all other connected users. Out of the box and very easy to use.
- **Full Stack Reactivity.** In Meteor, realtime is the default. All layers, from database to template, update themselves automatically when necessary.
- Built-in build system Meteor believes that we spend too much time packaging our applications together and getting all the dependencies working together nicely. You don’t have to fiddle with a Gulp configuration anymore. Meteor handles it all for you out of the box.
- Great for single page apps and mobile
- **Packages** are handled through Meteor’s pacakage management site: atmosphere.js (can also use npm and cordova packages)
- Connecting to external services and APIs is possible using ddp: DDP, the Distributed Data Protocol, is a simple protocol for fetching structured data from a server, and receiving live updates when that data changes. We won’t deal with this in our application today, but it’s good to know.

Getting Started
---------------

### Install Meteor

- download for windows: https://install.meteor.com/windows
- install for osx/linux: `curl https://install.meteor.com/ | sh`

### Create a New Application

```sh
meteor create scotch-meteor-polling
```
