---
title: Mardi Gras
category: challenge
date: 2018-02-10
---
In Nashville you don't hear about it as much but when BJ was living in New Orleans Mardi Gras was the big holiday. Mardi Gras is the culmination of the celebration of Carnival which begins 12 days after Christmas and ends 46 days before Easter when Lent begins. There's parades, beads, and king cake everywhere along with lots and lots of tourists.

## The Challenge

For this challenge we've been asked by the city of New Orleans to write a few apps to help tourists enjoy their time in New Orleans at Mardi Gras. Each level is a different challenge and they do not build on each other this time. Some are games for the tourists while others are tools to help them better use the time they have.

### Creating a Test Case

A Unit Test looks at and tests a specific unit of code to see if it is returning what is expected. No matter the level you choose to work with write a test case before you start your code. Then write just enough code to pass the test. Once you have passing code refactor to pass other test cases.

## Level 1

One of the more delicious parts of Mardi Gras is the King Cake. It is tradition to bake a plastic baby in the cake. Whoever finds the baby in their slice of the cake is said to have good luck for the year. Some families have a tradition where the person that finds the baby brings the King Cake the next year, others have them be the king or queen for the day.

We're going to create a little game for our tourists to play while they are waiting on their King Cake at the bakery. Have them enter the names of their friends and family then randomly select one of the names to receive the baby.

### A Step Further

Presentation is the key to making this a fun game to play. Going a step further add graphics to your game with a King Cake that gets sliced into the number of pieces matching the number of names entered. You can have each player find out if their slice of cake contains the baby then refer the winner as king or queen and their name.

## Level 2

A huge New Orleans tradition around Mardi Gras and almost every other holiday is lots of parades. Though Mardi Gras is the biggest time for parades. Different Krewes put together floats to travel in their parades. Each one is unique and lots of fun to watch.

We've been tasked by the city of New Orleans with building an application to assist tourists in knowing when and where to attend parades. They should be able to keep track of which parades to attend. The city of New Orleans wants tourists to be able to organize the parades in order of when they occur so that tourists can map out a route to see as many as possible. Tourist should be able to select a location and see when the next parade will be or find all parade locations at a certain time.

| Parade | Location | Date | Start |
| ------ | -------- | ---- | ----- |
| Krewe of Iris | Uptown | 2/10/18 | 10:00am |
| Krewe of Tucks | Uptown | 2/10/18 | 11:00am |
| Krewe of NOMTOC | Westbank | 2/10/18 | 10:45am |
| Krewe of Endymnion | Midtown | 2/10/18 | 4:15pm |
| Krewe of Isis | Metairie | 2/10/18 | 6:30pm |
| Krewe of Okeanos | Uptown | 2/11/18 | 11:00am |
| Krewe of Mid-City | Uptown | 2/11/18 | 11:45am |
| Krewe of Thoth | Uptown | 2/11/18 | 12:00pm |
| Krewe of Bacchus | Uptown | 2/11/18 | 5:15pm |
| Corps de Napoleon | Metairie | 2/11/18 | 5:00pm |
| Krewe of Athena | Metairie | 2/11/18 | 5:30pm |
| Krewe of Pandora | Metairie | 2/11/18 | 6:30pm |
| Krewe of Proteus | Uptown | 2/12/18 | 5:15pm |
| Krewe of Orpheus | Uptown | 2/12/18 | 6:00pm |
| Krewe of Zulu | Uptown| 2/13/18 | 8:00am |
| Krewe of Rex | Uptown| 2/13/18 | 10:00am |
| Krewe of Elks Orleans | Uptown| 2/13/18 | 12:00pm |
| Krewe of Crescent City | Uptown| 2/13/18 | 2:00pm |
| Krewe of Argus | Metairie | 2/13/18 | 10:00am |
| Krewe of Elks Jefferson | Metairie | 2/13/18 | 12:00pm |
| Krewe of Jefferson | Metairie | 2/13/18 | 2:00pm |
| Krewe of Lyra | Covington | 2/13/18 | 10:00am |

These are actual times from http://www.mardigrasneworleans.com/schedule.html

### A Step Further

Going a step furhter add distances and travel times between locations so when a tourist selects a location they are provided a list of the nearest parades going on right now or the time and location of the next parade. Going all out link to something like Google maps for directions to that location.


| Location | Uptown | Midtown | Westbank | Metairie | Covington |
| -------- | ------ | ------- | -------- | -------- | --------- |
| Uptown | | 3.5mi 10min | 8.3mi 20min | 5.2mi 15min | 41.1mi 50min |
| Midtown | 3.5mi 10min | | 11.9mi 25min | 4mi 10min | 39.3mi 45min |
| Westbank | 4.4mi 15min | 11.9mi 25min | | 12.5mi 25min | 49.9mi 60min |
| Metairie | 5.2mi 20min | 4mi 10min | 12.5mi 25min | | 35.5mi 40min |
| Covington | 41.1mi 50min | 39.3mi 45min | 49.9mi 60min | 35.5mi 40min | |

## Level 3

The tradition of throwing beads to the crowd began in the late 1800's and by the 1900's became a staple of the Carnival celebration. Traditional Mardi Gras beads are purple, green, and gold colors. The purple symbolizes justice, the green faith, and the gold power.

The city has asked us to build a simple game that tourists can play while they are waiting on the next parade to start. In this game the player will be a Knight of Endymnion (One of the most popular Krewes) on a mission to give out as many Endymnion beads as possible. As the player sees people on the screen they will need to throw beads to them. The city has left it up to the developers to determine how complicated this game will be but has asked us to add some fun graphics to increase enjoyment of the game.

### A Step Further

Going a step further make your game even more involved by creating moving targets to toss your beads. In addition you can have you knight be on a float travelling along the parade route tossing beads to those in the crowd watching. 

Add a points system so tourists can compare scores and challenge each other to see who makes the best Knight of Endymnion.
