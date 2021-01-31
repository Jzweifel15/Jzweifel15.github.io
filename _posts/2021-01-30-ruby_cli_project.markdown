---
layout: post
title:      "Ruby CLI Project"
date:       2021-01-31 00:31:05 +0000
permalink:  ruby_cli_project
---

The first portfolio project that is due for the first module when participating in the Flatiron School's Software Engineering
program is building a command line interface Ruby gem that scrapes data from a webpage and allows any user to interact with
that data in some way. I decided to create a gem that would allow any user to see the top grossing movies of all time. This gem
would scrape data from the Rotten Tomatoes webpage where they have a list of 50 movies in order starting from the #1 top grossing
movie and working its way down. 

When I first started this project, I had a small idea of where to start, so what I did was first look for a website that my gem
was to scrape data from and after about 10-15 minutes of searching, I came across the Rotten Tomatoes webpage, which is where
my gem scrapes from. I played around with the website for a while, finding the data I needed and how I was going to go about
getting that data and displaying it in a nice, organized manner to the user. When it comes to working on any project, I have learned
that just playing around with code can go a long way. I probably spent a good, 4-5 hours just messing with the Nokogiri and 
Open-URI modules to scrape different data from the website, then another couple of hours iterating through that data to display
it how I wanted it to be layed out to the user. 

Next, was actually starting to build the project and this was where I was stumped because I had never actually built my own Ruby
gem and had no idea where to start. Thankfully, Flatiron provides some very helpful resources that allowed me to get a small
blueprint (or, rough draft) of my project formed. This blueprint consisted of hardcoding some of the data, but it was to get my
project off the ground and into the air. I knew that later down the road major changes were going to be made, but I felt much
better than before knowing that I at least had a baby project started.

As of Tuesday, June 23rd of 20202, I have officially completed my first portfolio project for the part-time online software engineering program at Flatiron. 
We were required to build a ruby gem that allowed any user to interact with an interface of data using the command line. This data had to come from a webpage of 
our choice, but we were not allowed to hardcode this data. We had to either scrape this data from the website or request this data from the websites API. For my
project, I decided to scrape my data. 

My project, called Top_Movies_Cli scrapes data from the Rotten Tomatoes webpage on the top 50 highest grossing (most money made) movies of all time, turns each 
movie into a Movie object using some corresponding information that can be found for each movie on the webpage, like the movie's title, value, release date, and 
a description of the movie. Anyone who uses this gem will have access to seeing the list of movies and can interact with this data by choosing and typing a number
one through fifty to select a movie, which the gem will spit back out the corresponding information for that movie. 

Although my project is plain and simple, and the project does not do very much, I am still very proud of my project. It was a giant headache in the making, but it
always feels so good when it finally works and does what you're expecting of it to do. Hopefully, this small little project is just the first step to something
much, much bigger in the future.



