---
layout: post
title:      "My Sinatra App"
date:       2020-01-30 09:37:48 -0500
permalink:  my_sinatra_app
---

  For the second project, I was required to build a Sinatra MVC (Model View Controller) application by using Active Record. I would have an opportunity to apply all concepts I have learned like Ruby, ORMs, Sinatra, Active Record.  Indeed, I decided to build a simple web app that users can keep track, edit, delete their favorites that they would be capable to create, read, update, delete them. 

  In order to start, I created file structure for this app. I felt that is a good practice to generate it without the help of bundler as this improved my comprehension for the structure of my project.



  Next, I updated all gem files necessarily for running my application before starting coding. I chose to code from the bottom up that started with DB-migration where I created Users, Favorites tables.  
* Users have username, email, password,
* Favorites have names, user_id 


•	Controllers: I have a user controller, a favorite controller and an application controller where both user and favorite controller are inherited from application controller. 

•	Models: In user and favorite models, I decided the users has many favorites, and favorites belong to a user. And, they both were inherited from ActiveRecord::Base.

•	Views: I would initially have a landing page with “Sign up” and “Log in” options and a layout.erb template of html to prevent copying over basic html to all erb files.  There would have to be views for Favorites-create, edit, ad show, and Users-signup, login, logout. 


  Furthermore, I added  MethodOverride Sinatra middleware in order to user Patch, Put, and Delete requests.   Fortunately, Corneal helped to set up database for config directory and rakefile configuration.  In addition, to keep my app safe I use authentication for both “Sign up” and “Login”.  I also added some validation to users, so users are only allowed to create, edit, and save once passing validation. 

  Altogether, this project was an enormous learning experiences for me that I could apply all concepts I have learned up to day to satisfy all requirements for my Sinatra Project.


