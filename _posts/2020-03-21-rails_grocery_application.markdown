---
layout: post
title:      "Rails Grocery Application "
date:       2020-03-21 18:15:49 +0000
permalink:  rails_grocery_application
---


One Important thing I had on mind before starting my project is how cool rails was and I was looking forward to using the

tool and the amazing command availabe. Make sure to think about what you want to build as this is very important (this 

actually got me worked up). I'm going to take you through how I prepared and got my project started .

*** Model, Association & Validations
 
 I built out how I wanted my models to relate , attributes, the relationship needed, validations and how the join table will 
 
 function between the models . Here is  what the table looked like :
 
 [![pushing the files to guthub](https://imgur.com/a/cEmidWk](https://imgur.com/a/cEmidWk)
 ![](http://https://imgur.com/a/cEmidWk)
 
 
 
 * Started with my Signin, Login  and Logout 
 
 Using devise is actually amazing , I didn't spend alot of time here because devise help generate all of  Signin, Login  and 
 
 Log_out. Here is a link to  sheetcheat for your set up :
	
	
	[](https://docs.google.com/document/d/1KzCLajCVBAVZYh2dgS5WMpZ6AuzASHEupQwqK48A9HM/edit#)
	
	The third-party sign up was quite intersting and you could goggle search the omniauth you want to work with your app.
	

*** Rails Generators

Using the generator is awesome, one advise is for you to use make use of each generators according to how it's needed 

but the most helpful to me is the  rails resource
```
rails g resource Account name:string payment_status:string --no-test-framework
```
the  resource genarator will help generate all the files/folders needed and you could take out the --no-test-framework if 

you would like to create test in your application. 

*** Crontrollers, Views, Routes, Model 

 I would say this gave me alot of issues. I spent many days figuring out the logic between my forms  associations. 
 
 Understanding what is available to use because of my validations, had issues merging my models together in a way that 
 
 made sense to me. I struggled between my MVC, hopefully I get better by spending alot of time on rails , for the sake of 
 
 my project and timining - I had top get them all done and meet all necessary requirememts. Rails is awesome when you
 
 understand the concept. Your view and creating nesting will be easier if you take your time to understand them . I actually 
 
 don't have alot of time because project are due and reviews are up next . For the  most part project time actually help me
 
 learn and it gives me a feel of real world and I'm also able to determine where my focus should be on . Hopefully you 
 
 understand my struggles and you are able to pick one or two things from the above !
 



