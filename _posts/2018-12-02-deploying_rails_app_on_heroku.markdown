---
layout: post
title:      "Deploying Rails App On Heroku"
date:       2018-12-02 01:42:30 +0000
permalink:  deploying_rails_app_on_heroku
---


Deploying my rails app that I created to Heroku could be a little tricky so I thought I would jot down some things to not forget to make sure there are no errors. 

1. Make sure you install the gem 'pg'. This gem installs postgreSQL. Heroku will use this as the database instead of SQLite. This gem needs to be put in a production group namespace in your gemfile. 

2. Another gem that needs to be installed in this group is 'rails_12factor'.

3. There are two ways to push your application to Heroku. You can download the Heroku CLI, 'heroku create' a new app, and push your code in the git. The other way, which I found easier, but only if you use Github, is to connect the github repo to Heroku, click deploy, and that's it. 

4. Lastly, after the app is deployed you may still see an error message instead of your app. The best way to see what is causing this error is to run 'heroku run rails console'. 

For more information Flatiron has a great resource here: https://learn.co/lessons/rails-heroku-deployment


