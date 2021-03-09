---
layout: post
title:      "Sinatra Project"
date:       2021-03-09 17:15:08 +0000
permalink:  sinatra_project
---


This project was much more straightforward for me than the last one. The corneal gem was a great tool for setup and it gave me a strong starting point. Having done so many partial setups in the labs leading up to the project gave me enough confidence to be able to start to put the pieces together without a lot of extra research in the beginning. Eventually I turned to some external resources when my patch and delete requests were not working properly and saw that I did not have the "use Rack::MethodOverride" line in my project. I originally set up my project with every accessory type having its own model and table in the database but realized that things would become much too complicated trying to create new objects for every user so eventually I turned every accessory into an attribute and went from there. 

One thing that I did get stuck on for a while was the idea of making radio buttons for common attributes. Originally, I wanted to supply the user with 3 or 4 choices for each type of accessory and then give the user the option of a last radio button titled "other" and also include a text box associated with the "other" button and let the user put in a their own text if they desired. I could not get that portion working so I eventually reverted to text only inputs because that is what I decided was more important than limiting the user to options that weren't relevant to them. If anyone has some sample code or ideas to share about how to create a working controller and view with radio buttons that includes an "other" option please let me know! I would love to hear what others have come up with for solutions. 
