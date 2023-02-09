## magic gif generator

#### By _Ashe Urban,_ _Mitchell Gantz,_ & _Jackson Levine_

## Technologies Used

* _HTML_
* _CSS_
* _JS_

## Description

_Create a webpage where a user can select the name of a movie, the time of day that they would like to see the movie and their age. The webpage should let them know how much their movie ticket will cost, based on those three factors. Consider that non-"first-release" movies, matinee, and senior tickets tend to be cheaper than the regular priced ticket._

_Your constructor and prototype could be called Ticket and you can come up with the formula for determining how the price is calculated depending on the input from the user._

_Start by completing your business logic, and then move onto your user interface logic. Use test-driven development to complete your business logic and add your pseudocode tests to your project's README.md. After every passing test, make sure to commit your code._

_Link to Lesson:_ https://www.learnhowtoprogram.com/intermediate-javascript/object-oriented-javascript/address-book-movie-tickets-bank-account

## Setup/Installation Requirements
* _Clone or download this repository to your local._
* _Navigate to the top level of the directory and launch live server._

## Known Bugs

* _none_

## License
* MIT

## Contact Information
_If you run into any issues or have any concerns, feel free to [Contact me: ashe@goldentounge.com](mailto:ashe@goldentongue.com), or request to make any contributions to my code._

Copyright (c) _February 2023_ _Ashe Urban_

## Manual Tests
### Describe: Ticket()

Test: it should create a ticket object.
Code: new Ticket("Movie Name", "Movie Time", "Special")
Expected Result: ticket with moviename = "Movie Name" movietime = "Movie Time" and special = "special"

Test: it should return ticket object.
code: return this.movieName + this.movieTime + this.special
Expected Result: "movieName + movieTime + special"