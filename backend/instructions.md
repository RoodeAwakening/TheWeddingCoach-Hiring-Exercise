# Welcome Backend Product Exercise


```
TIMEBOX:    2-3 hours max. We mean it!
LANGUAGES:  Java, Python, or Node.js
FRAMEWORKS: Spring Boot, Flask, or Express.js
DATABASE:   MySQL or PostgreSQL
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

# Overview
This exercise is to implement the best possible solution to one of the exercises below in the time alloted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates craftsmanship, thoughtfulness and attention to data integrity. This is NOT a test of how well you know Spring Boot, Flask, or Express.js, nor should you try to impress us with overly clever and obtuse solutions. If you want to impress us, build something that is secure, efficient, and easy to understand.

There is starter data provided.

# Choose One Of the following

## Exercise A: Managing Bookings
### As a DJ company administrator I want to
* Create a new DJ booking
  * Specify the date, time, and location of the event
  * Specify the customer's name and contact information
  * Specify the DJ assigned to the booking
* See a list of all DJ bookings
  * Be able to search and filter by date, customer name, DJ name, and location
* Update an existing booking
  * Change the date, time, and/or location of the event
  * Assign a different DJ to the booking
* Cancel an existing booking
  * Allow for a reason to be provided for cancellation

### As a customer I want to
* See a list of all my bookings
  * Be able to search and filter by date, DJ name, and location
* Cancel an existing booking
  * Allow for a reason to be provided for cancellation
  * Prevent cancellation if the booking is less than 24 hours away

## Exercise B: Payment Management
### As a DJ company administrator I want to
* Store customer payment information securely
* Associate payments with a booking
* Retrieve a customer's payment information when needed

### As a customer I want to
* Store my payment information securely
* Retrieve my payment information when needed
* Update my payment information when needed