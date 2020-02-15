---
layout: post
title:      "Sinatra Application  "
date:       2020-02-15 23:44:26 +0000
permalink:  sinatra_application
---



Prior to starting this project , I had this feeling of excitement about creating an app for the first time although this feeling didn't last too long but I am glad I made it through .  I had ideas of what I wanted my app to look like and it felt really good knowing what you wanted to see and the result. So I will breakdown each moment of this project, just before i forget,I asked for help as much as I needed and I also got confused alot of time because due date was coming up and I was getting nervous .

**** Creating and Populating Database

With the help of corneal it was easy to start up, as I didn't have to start building from the scratch and incoporating all of the gems needed , all I needed to run was just bundle install  and shotgun - just to make sure all of my gem was working accordingly.

Getting my migration table right seems pretty easy but I had a hard time getting it together , but along the way I learnt about various command I could use , at first I was adding to my table just to get the migration to work, all together I had alot of unnecessay table, this made my migration folder look a little  busy and I was getting confused btween 
Here are some of the command that were helpful and handy 
         rake db:drop  this help drop my database completely and I could just make changes manually and continue (but this isn't a good practice).  and run my rake db:migrate
				    rake db:reset 
						rake db:migrate VERSION=0
All these are good but I just advise to be patient when building your app , don't try to over do it, you may end up getting stuck and having to change your mind (this happened to me while working this project . I lost my train of thought and wasn't sure what I wanted . I was too scared ! and each time I ran my localhost I didn't want to see errors) .

Finally, I aso seeded my database , this helped alot with testing my app.  I got this going and I moved on to creating my models and the associations , with the validations and uniqueness just has the project requirement specified .

**** Controllers & Views

The controllers and View I taught okay Olusola you got this , since I had just learnt the conventions of the Route(what  I needed to feed my block to make it  render or redirect ) I was certain this shouldn't take alot of time but at last ,I spent days trying to figure alot of things (this is also because I have to care for my three babies , I had to divide my time inbetween ).

The route didn't give me alot of issue but I had alot of syntax error in my views. Specifically my show.erb and edit.erb.
show.erb looks like this now 

                   <h3><%= @report.date %></h3>

                  <ul class="list-group list-group-flush">

                <li class="list-group-item">Comments: <%= @report.comment %></li>
  
 
               <li class="list-group-item">Due_date: <%= @report.due_date %></li>

 
              <li class="list-group-item">User_id: <%= @report.user_id %></li>
							
              <li class="list-group-item">subjects: <%= @report.subjects %></li>


              </ul>
On this render page I had to add the class variable infront @report to my attribute before i was able to get the create report to display.

I had to do the same thing calling class variable on the attribute again for my edit page . One interesting thing I learnt about was this method my cohort lead(Howard)showed me , the date on my edit page wasn't populating , I was going to leave it as that because I was tired but this method fixed the worry

 <input type="date" name="report[date]" value="<%= @report.date.strftime("%Y-%m-%d") %>">
 
 so .strftime  was callded on @report.date and this was helpful , that way the user don't have to keep track / make mistake on the actaul date report was created, and can just edit report. 
 
I finally wrapped it up with the the delete route and got my delete form working and other user will not be able to able to edit/delete report that doesn't belong to them.
 
All of this I wouldn't say I am confident yet , I am just learning as this is my first attempt at logical thinking and creating a web application, but I am excited to know you could give computer command and it would listen to you .

I will be posting a link to the video walkthrough of my code , hopefully you can get something out of it. I am just a work in progress hoping to be the best as time goes on .
 
 
