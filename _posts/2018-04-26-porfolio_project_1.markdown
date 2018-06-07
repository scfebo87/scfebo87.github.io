---
layout: post
title:      "Project #1"
date:       2018-04-26 05:49:50 -0400
permalink:  porfolio_project_1
---


For our first project, we had to create a CLI-Data gem/app. Up to now I have learned procedural and 
object-oriented ruby and this project would integrate what I have learned so far. 

I decided that I was going to create a gem based on the fictional school 'Hogwarts' from the 
books/movies of 'Harry Potter.' This gem will provide a list of textbooks that students at Hogwarts use 
and an atlas of the school. When you select to see the list of books, you then can select a specific one for the URL, which will provide detailed information about the textbook. This is the same for the atlas. I made sure the interface knew what to do when someone entered an incorrect response and gave options to go back to the main menu and exit the program. 

The way I approached building this gem was to watch the video tutorial 'Daily-Deal' and by looking at examples from other students on github and youtube. When it was time to code, I started by using 'bundler' to create my file structure. From there, I created the files for my classes (cli, textbooks, and atlas). Instead of making a separate class for the Scraper methods, I decided to put them in with 'textbooks' and 'atlas.' I decided to do this so I wouldn't have so many files to go back and forth. The 'textbooks' and 'atlas' files did not have much in them anyway. Besides the scraping methods, they included the initializer for new objects and reader/writer methods for 'name', 'url', and the class variable 'all'. 

Building the CLI interface was the heart of the project. They way I approached it was by coding in the order that I wanted the gem to function. For example, I knew the program needed to start, so I built a start method. The start method had my welcome message and defined some class variables. I then coded the methods for what the class variables had equaled. And I just moved along in this pattern. When I saw what needed to happen in the program next, I coded it. 

Lastly, I want to mention that if you are someone who gets frustrated when things fail or break, then coding is not for you. The majority of my time on the project was reading errors and trying to figure out what needed to be fixed. I also spent a good amount of time googling when an error didn't make sense. However, when the program finally runs the way you want it to, the feeling of accomplishment is totally worth it!
