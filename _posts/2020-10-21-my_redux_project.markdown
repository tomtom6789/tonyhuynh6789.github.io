---
layout: post
title:      "My Redux Project"
date:       2020-10-21 18:17:08 -0400
permalink:  my_redux_project
---


   For my redux project. I decided to create simple web application for selling computer where the user can list laptop for sale.  I will add functionality over time, but for right now I just allow user to add computer to list for sale. The users can see the content of each computer in their show pages. 

   With this project, we were required to use React and Redux for the front-end and rails API back-end . React is an open-sourced Javascript library(not a framework), maintained by Facebook. It is used for building user interfaces and UI components. Redux is another Javascript library used to manage state. 

   Initially, I started off with building rails API that I used “rails g scaffold” to create model, controller, and routers, and cors. I also changed the port number for rails server to 3001 to not overlap frontend port. Indeed, I initially set up a reducer and action for frontend to fetch all data from the backend to redux store and show to the Dom. Once “Get” request to the backend was successful I continued create another fetch that send “POST” to backend to create the form. My fetch to create the new computer was successful fired and created a new laptop on the backend, but it was not displaying on the list instantly after created. However, I was able to work around to fixed it that I discovered I mistakenly did not return the added laptop to current list of laptops in reducer.
	
   Overall, I was struggle with this project more than my previous ones. I am interested to learn more and improve my knowledge with redux and react as I would like to improve this application to much further. 



