---
layout: post
title:      "My First Feel of Programming CLI PROJECT"
date:       2020-01-15 23:38:13 -0500
permalink:  my_first_feel_programming_cli_project
---


The is my first major test of knoweledge to programming and I can say without a doubt that it was exhausting , because it entails putting in all I have learnt  in the last 4-5 weeks together into a readable program .  
Just before starting  I realise I would need to set up my local enviroment (this took a while before I could get it working ). One major issue I had was understanding my commands , which i am not confident about yet but I'm getting there. Starting up my project I ran into major issues like making a repo on my github account linking it to my project on the text editor work around  was an hassle , had several meltdown but I kept on trying, till I was able fix it , this gave me a certain level of joy and confident of the ability to read error and work my way through.

I started with creating my repo , I moved on to starting my project(which is based on DOG BREED) starting with setting all of my bin (executable file), then the enviroment.rb(this is where I require all of the  classes  built in my directory) and it looks like this  => 

                        require "nokogiri"
                        require "open-uri"
                        require "pry"


                       require_relative "./breed_dogs/version"
                       require_relative "./breed_dogs/cli"
                       require_relative "./breed_dogs/scraper"
                       require_relative "./breed_dogs/dogbreed"
											 
All of the information provided in the block above came after each of the classes was define . I got stuck several times , at a point i didn't understand what my error was wanting me todo , but i knew error was coming  from my gemSpec which i had to comment out with the help of my Cohort lead (Mr Howard)but he said I could still work it out but for the sake of my project and time - i decided to keep that out .


Scraping was another thing that gave me alot of issues. This took alot of video watching and lab but then-- hmmm!!!

what then is Scraping : scraping is a technique used to grab data out of the HTML that makes up a web page. So I scraped a dogbreed website (I got alot of help from my cohort professor learning this - I am not all round confident just yet but I am getting there. For the sake of my project didn't want to play around too much) using the nokogiri and open- uri to get data from the website I choose (dogtime.com). which I was able to convert to object which enable me start working on my CLI class . 
This Cli  may not interest everyone has it just a method calling different dog bred name with their url and user is also able to read the information about the dogs . This took me about 24 hours to figure it out and to get it working and making sure my codes was responding to command and not breaking.
my CLI class looks has this =>
                                class Cli 
                                         def call
                                          start
                                         information
                                         end
																 end
Inside the Cli classes is instace method start and information which is called and it also collaborate with another class from my program to output all the information..


 These project gave me alot of  meltdown but i am glad I pulled through . I hope  you enjoy reading this.  
