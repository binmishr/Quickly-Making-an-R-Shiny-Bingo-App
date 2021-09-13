# Quickly-Making-an-R-Shiny-Bingo-App

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

Introduction
=============

During the lockdown of the city, game nights are happening on Zoom a lot. I was asked if I could code up a bingo game—about an hour and a half before game time. I’m sure there’s probably some type of bingo game programmed in Shiny already, but I wanted to see what I could do under crunch from scratch. Here’s what I’ve got.

Using the rules from Wikipedia[https://en.wikipedia.org/wiki/Bingo_(American_version)#Bingo_cards], Two apps are here with the code as attached in this repository: 
One for the bingo master (who shares their screen) and one for each person playing bingo. 

The bingo master app is for drawing a new letter-number combination, keeping a record of what has been called, and then starting a new game when necessary.

The bingo player app is a grid of checkboxes that someone can check whenever that letter-number combination has been called. I remember getting creative with using tagList and lapply statements, which would be handy for generating a grid of checkboxes in less code, but I can’t remember how to do that at the moment, so you’ll see some copy-pasted stanza code in the player script. I know this would offend my statistical programming professor from grad school, but ¯\_(ツ)_/¯
