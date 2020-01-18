---
layout: post
title:      "My Dinosaur CLI"
date:       2020-01-18 00:41:43 +0000
permalink:  my_dinosaur_cli
---


         The hardest thing I have had to do so far is make a CLI Data Gem Project Portfolio of my own. It wasn't the concept of how it would work because I had the idea drawn all out. It was more or less the fact of getting it all out on the learn Sandbox (that was the easiest part). So how about this, it might be easier if I just start from the beginning (finding out we get to make a CLI project).

        I was so excited to be able to make my own CLI (Command-line interface, also known as a command-line user inferace). I had been drawing out plans on what I wanted It to be able to do. I used the inspiration from my son who absolutely loves dinosaurs. So, I made a plan to make a Dinosaur CLI. I wanted it to start out on a menu page saying "Welcome to Dinosaur-aus".  I wanted the user to be able to start out with three main menu options ( 1.- What dinosaur would you like to research?, 2.- Would you like to know what species of dinosaur were found in a certain era?, 3.- What dinosaur belong to a species?). Option 1 on the main menu, would take you to a place where you put in the name of a dinosaur in the command-line and be able to recieve information on that dinosaur (specifically it's "name", "species", "era it lived", and a "description of the dinosaur"). Option 2, would take you to  a place where you would place in what era of dinosaur and recieve a list of a dinosaurs that lived in that era. Option 3 would take you to a level where you could place what species (like "herbivore", ect.) and you would revieve a list of dinosaurs that belonged to that species. It was a great idea, or maybe not. I started feeling frustrated wondering if I should use an API or scraper. I asked other coders in my cohort if the knew of any good API's. Luckily, there was an Api  that I could use, but it gave a dinosaur name and a one line description. So I had to dull down my idea for my Dinosaur CLI.
 
        The next step of the phase was to start writing the rest of my code for my cli. At this point, I had most of my "api.rb" file coded out and most of my "cli.rb" file as well. I only say most for my cli.rb because I didn't realize I had missed some parts. I, now, could finish my API by placing the right url's in there places.  Then, it was back to the cli.rb file. I had to rewrite my main menu and my secondary menu (along with both of their inputs). Shortly after that, I had to finish my dinosaur.rb. That was the easy part. I had to ask for a lot of help, which I have never been one for asking for help. I just knew I had no choice or my Project would never have been done on time. 
				
         The next step in my code was making sure that I could use bin/run to be able to have my interactive feature. Oh boy was there a lot of errors. The biggest error I had come across was in my api.rb file. I came accross an error that I had never had before or have ever hear of before. It was with my: 
 
         ** `*dinosaurarray = JSON.parse(response.body) ["result"]`* **
					
         It turned out that even though my API was in a has there was no "result" to be located. So, I had to remove the ["results"] part all together. After I had fixed this with the help of my cohort leads, I then ran into a new error but that was a new issue. It involved my :

				** * self.send("#{key.downcase}=", value) if self.respondto?("#{key.downcase}=")***


         It was frustrating to think that I wasn't cut out for any of this because I always had errors in my code. The issue was it was looking for my " attr_accessor :name, :description ", but in their hash the Key was in a first letter uppercase form with is why I had to add ".downcase". After that everything went amazing. There were a few other errors, but it wasn't anything that I couldn't handle on my own.  I have learned that never have doubt in yourself, because you can do  what you put your mind to.
				 
				 [](http://https://github.com/secretartist272/CLI_Dinosaur)

