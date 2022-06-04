# IronBeers

## Pages

1. Home page with three different options:

- All Beers are displayed
- Random Beer is displayed
- New Beer is displayed

  1.1. List Beers page - All Beers are displayed
  1.2. Single Beer page - Single Beer details of selected Beer is displayed
  1.3. Random Beer page - Random Beer is displayed
  1.4. New Beer page - Form where user can create new beers is displayed

## REST API

Origin: https://ih-beers-api2.herokuapp.com/beers

Endpoints:

Method - Endpoint - Response (200) - Action
GET - / - [beers] - Get all the beers from the DB
GET - /:id - { beer } - Get the a single/specific beer
GET - /random - { beer } - Get a random beer from the DB
POST - /new - { message: "New beer successfully saved to database!"} - Create a new beer (the fields are specified in the instructions)
GET - /search?q={query} - [beers] - Get beers from the DB whose name contains the search term. For example /search?q=lager searches for all beers with lager in the name.
