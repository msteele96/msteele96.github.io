---
layout: post
title:      "Rails Ancestry"
date:       2021-04-14 15:17:29 +0000
permalink:  rails_ancestry
---


The Rails project gave us the challenge of making many different types of objects that all interact with each other. Setting up the relationships has been something that has given me a little bit of trouble throughout the curriculum, but this experience has definitely made me feel a lot better about attempting to do this in the future. It really can be as simple as thinking about what types of objects belong to one another in real life. For example, my idea was to recreate something like ancestry.com where there are many users and families. In this model I did not go so far to include the idea of families being combined through marriage and childbirth. Simply put, a user can belong to only one family. That family is the one that defines where their relatives come from. And I worked my way out from there saying that users can have many relationships through their family and continued to build those relationships in both directions. Even at some points when I was not sure how to effectively set up the relationships, I found that playing with the different methods that you get from the relationships in the rails console helped me to figure out what got everything to work the way that I needed it. If anyone is having any trouble with relationships, I hope this inspired you to look at things in a way that you had not before. 
