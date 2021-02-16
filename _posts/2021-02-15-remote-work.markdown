---
layout: post
title:      "Remote-Work"
date:       2021-02-16 02:43:09 +0000
permalink:  remote-work
---

Working remotely is becoming more and more popular. Most work from home, but would they if more options existed? Obviously, working from home offers many dependable resources like bathrooms, peace and quiet and a neccessity, internet. This application was developed in the belief that the sharing of unique work from "home" locations would be an attraction to many, especially during this pandemic. 
Remote-Work utilizes a rails api with postgres as a backend and a javascript frontend.
Currently there is no user registration and hence no user-names or passwords, but ultimately prior to a release, a goal would be impliment one. As it stands now a visitor is greeted with an index page of sorts with cards describing remote work offices. Cards contain several metrics that rate and describe each office. Internet availibility(cell signal, hotspot signal quality), restroom facilities, quality of overall working environment and a short description are contained on each card, the first three scored with a value 1 through 10. A final project would want to distill these metrics and produce a final scoring, something similar to a star rating. Additionally, each card has a comment section and a button that reveals a form where a visitor of a particular office could leave a comment. Without a user registration currently anyone can leave a comment on any office card without validating their identity or if they actually did indeed visit, a re-tooling would need to take this into account. As far as the code structure, there many places that could be simplified and cleaned up, this is strictly an MVP. In production one would want more classes for segmentation and easier debugging, a more efficient use of HTML and a straightforward CSS with more thought paid to design. As it stands now one can get a good feel for the application as a strictly MVP and hopefully see beyond to the possibilities of a future deployment.

