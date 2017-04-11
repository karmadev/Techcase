# The case
Your assignment is to create a simple web application that lists the items (and locations if you are ambitious) available.
* It should be clear which items belong to which location and how much they cost (prices are in Swedish öre).
* Present the items in a way that you believe makes the most sense for a user looking for something to purchase.
* It should be possible to filter on locations and ingredients by text search.
* It should be possible to sort items by name, price and location.

You are free to setup the project in any way you see fit but the requirements are as follows:

* Use React (and Redux if you want to)
* Use a modern version of JavaScript (ECMAScript 6 at least)
* Add docs so we know how to run the example
* Add comments whenever you're making an assumption 

Whenever something is unclear, make assumptions. How you deal with those are also part of the challenge :).

# Delivery

There is no deadline but the sooner the better. Once you are done, put the code in a git repo and send a mail to *mattis@karma.life* with a link to the repo or the repo tar ball.

### Base url [*http://case.karma.life/viewer*](http://case.karma.life/viewer)

## GET /items
Returns all items

## GET /items/:id
Returns one item

## GET /locations
Returns all locations

## GET /locations/:id
Returns one location

## GET /locations/:id/items
Returns all items for one location
