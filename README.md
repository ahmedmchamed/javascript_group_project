# JS Group Project - Monopoly CodeClan Edition

## Web App
![homepage_screenshot](/client/public/homepage_screenshot.png?raw=true "Homepage Screenshot")

## Brief

The CodeClan Edition of Monopoly. We included a lot of the main elements of the original game, such as moving across the board, chance cards, and buying and selling property between players. We also decided to utilise a backend with an `express` server and a `mongodb` database, fetching updated player details as needed.

## Starting the app

`cd` into the `client` directory and run: `npm install` followed by `npm run serve`

`cd` into the `server` directory and run: `npm install` followed by `npm run server:dev`

Then go to the browser and navigate to `http://localhost:8080/`

## Learning Objectives
* General consolidation and CSS Practice
* Git branching and merging
---
## MVP
* Each player should have a minimum wallet amount (e.g. £1500?)
* Each player should have an empty array of stations and properties (squares)
* Each player should be able to pick an icon or colour
* Player should be able to ‘throw’ dice to get a number between 2 and 12
* Player icon should move an amount of squares equal to the amount given in dice throw.
* Player has to buy squares if they land on a square not owned by another player
* If player lands on a square owned by someone else they pay rent (10% of the value of the property)
* All squares to all have the same value.
* When a player passes GO they will collect £500
* Jack as the Monopoly man
---
## Extensions
* Chance Cards with functionality more like Monopoly game (i.e. pay other players)
* When a player goes to jail they have to pay £50 to get out
* Chance Cards with Quotes from https://themindofbaz.co.uk/
---
