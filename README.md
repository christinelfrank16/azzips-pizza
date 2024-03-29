# Azzip's Pizza Parlor

#### An application where one can order pizza from Azzip's Pizza Parlor, 30-Aug-2019

#### By Christine Frank

## Description

This application provides the user fields to create their own pizza by selecting size and pizza toppings. Throughout the order process, the order selections and cost are updated and shown to the user. Once the order is submitted, the user can then see their order status as the pizza is made by Azzip's Pizza Parlor and ready for virtual pick-up.

## Setup/Installation Requirements

#### View Hosted Site
* Go to: https://christinelfrank16.github.io/azzips-pizza/

#### View a local version of this Site
* Clone this repository
* At the local repository, copy the full path of the index.html file
* Open a new web browser
* Paste the copied path into the browser

## Known Bugs

* No known bugs at this time

## Support and contact details

* Email: christine.braun13@gmail.com
* LinkedIn: https://www.linkedin.com/in/christine-frank/

## Application Specifications

#### General

| Behavior | Input | Output|
|:-------|:------:|:------:|
| The application displays the submitted pizza order details when the user to adds a pizza to their order | Submit Pizza | Order displays committed pizza selections (size, sauce, toppings)|
| The application displays the pizza cost when the user to adds a pizza to their order | Submit Pizza | Order displays committed pizza selections and pizza cost|
| The application displays the order total when the user to adds a pizza to their order | Submit Pizza | Order displays pizza selections, pizza cost and order total|
| The application calculates pizza cost based on pizza size, topping type and count | Submit Pizza (small, 3 toppings and 1 premium topping) | Order displays cost based on pizza selections |
| The application displays subsequent pizza selections and pizza cost when the user adds additional pizzas to their order | Submit nth Pizza | Order displays all pizza selections, cost breakdown per pizza|
| The application updates the total order cost when the user adds additional pizzas to their order | Submit nth Pizza | Order displays updated order total, and all pizza selections and cost breakdown per pizza|
| The application displays order status when the user commits their order | Submit Order | Order status displays and updates over time |
| The application refreshes the  page when the order has been submitted and the user closes out of the status window| Close status modal| Page refreshes|

#### Cost Behavior

| Behavior | Input | Output|
|:-------|:------:|:------:|
| The application allows the user to select a small size pizza | "Small, 10"" | Adds $2 to breakdown|
| The application allows the user to select a medium size pizza | "Medium, 16"" | Adds $3 to breakdown|
| The application allows the user to select a large size pizza | "Large, 24"" | Adds $5 to breakdown|
| The application allows the user to select a 'no sauce' option for their pizza | "No Sauce" | Adds $0 to breakdown|
| The application allows the user to select a sauce option for their pizza | "White Sauce" | Adds $1 to breakdown|
| The application allows the user to add "extra" sauce for their pizza | "Extra White Sauce" | Adds $2 to breakdown|
| The application allows the user to add no toppings to their pizza | No toppings selected | Adds $0 to breakdown|
| The application allows the user to add up to 4 toppings to their pizza at a low price rate| 4 toppings selected | Adds $0.50 per topping to breakdown|
| The application allows the user to add up to 8 toppings to their pizza at a moderate price rate| 6 toppings selected | Adds $0.75 per topping to breakdown|
| The application allows the user to add more than 8 toppings to their pizza at a higher price rate| 10 toppings selected | Adds $0.75 per topping for first 8 toppings, and adds $1 per additional topping to breakdown|
| The application allows the user to add premium toppings to their pizza | 2 premium toppings selected | Adds $1 per premium topping to breakdown|
| The application uses the sum of the cost breakdown to calculate the total cost of a pizza | small, normal sauce pizza with  2 toppings | Displays cost $4 |


#### Display Behavior - HTML
| Behavior | Input | Output|
|:-------|:------:|:------:|
| The application displays pizza size and topping options to user after the user clicks on 'Make a Pizza' button | Click 'Make a Pizza'| Order displays pizza options |
| The application defaults to a large pizza size selection, no sauce and no toppings | Open Website | Pizza options displayed with default values selected |
| The application prevents multiple pizza size selections for a single pizza and updates to latest size selection | Select other pizza size | Selection from previous size removed and displays latest selection |
| The application prevents multiple pizza sauce selections for a single pizza and updates to latest size selection | Select other pizza sauce | Selection from previous sauce removed and displays latest selection |
| The application allows one pizza topping selection for a single pizza | Select topping | Topping selection displayed |
| The application allows multiple pizza topping selections for a single pizza | Select new topping | Previous topping selections maintained, latest selection displayed |



## Technologies Used

* JavaScript
  * jQuery

### License

*This application is licensed under the MIT license*

Copyright (c) 2019 **Christine Frank**
