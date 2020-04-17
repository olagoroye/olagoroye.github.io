---
layout: post
title:      "JavaScript and Rails Project "
date:       2020-04-16 23:37:14 -0400
permalink:  javascript_and_rails_project
---


This project came right after the ruby on rails project . Pretty much the project is about making sure  Rails (backend ) communicate with JavaScript(frontend).

My app was about Shopping List (this is just an extension of what i had done with my rails project ).  Let  me take you through, how I started off from beginning to the end . I created two branches under my grocery List App (Backend-Api and the Grocery-frontend )

BACKEND (RAILS)

The first thing you want to do  run `rails new backend-api --api`  this will generate your app file, dont forget to go in the gemfile to uncomment the "rack cors " and run bundle install .With my knowledge of ruby on rails just coming together, the backend didn' t seem too difficult  and since I had an idea of what i wanted the relationships and association to look like , it was a little easier to bring my thought to life -

the rails generators came in handy -- you probably want to use that , since these generotors work like magic and you don't have to worry about most of the files as it will authomatically be generated, one of the most amazing genertors is the :
                                `rails generate scaffold list title --no-test-framework`
The scaffold generator is associated with JSON which is important for your file rendering in the browser . It is also one of the requirement .  I use --no-test-framework because I would not be needing it but you can include test if you would be permitting or doing any test in your project.  Also seed your database , this is helpful  to test codes to see if it working and if no error.  Check and confirm  that all files is generated accordly and make sure to include all of your validations and associations in your model. 


FRONTEND (JAVASCRIPT)

JavaScript is someworth interesting! What then is Front-End Web Programming?  It is creating documents with HTML and styling /positioning the document's content with CSS stylying. It also  uses JavaScript to provide interactinity and notify remote servers . There is actually the three pillar of web programming , If you can take your time to learn this communication , you will always get the eureka moment of JavaScipt and Rails . I haven't experienced this though , has this is my very first time getting to ever work on JavaScript . Here is the three pillar of web-programming:
                1.                      Recognize Events
                2.                      Manipulate the DOM
                3.                      Communicate with the Server
                     
											
Understanding the above is very much important towards your sucess in this module .  You also want to pay close attention to the object orientation, as you will be needing it to write your codes , which wil make it easy to read and resuable . My project isn't close to perfect but  I got all the necessary functionality working to meet the requirement , looking forward to being a better developer . I will be dropping a link to my project here later .. I hope you got a hint here for your project has well.


