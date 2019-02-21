# Eat Da Burger
## What is it?
### This is an app to allow clients of the site to access a mySQL database of burgers and select one to consume.  
### Burgers are arranged in two categories on the page, one of burgers eaten and one not yet eaten.  When a user selects the "Munch" button next to a burger's name they will devour it and the name of the burger will be moved to the list of eaten sandwiches, highlighting their gluttonous sins.
### Clients can also name their own burgers and add it to the list of ones to be eaten.
## How it works
### A SQL database is created from a schema and is populated employing handlebars to quickly generate data in the fields of that table.  The server is accessed and uses Express create functions for the user to read the burgers on the table divided by their devoured state, to create burgers of their own device, or change the status of each entry from eaten to uneaten.  
## The future.
### It would be feasible to make a button to reverse the consumed status of the burger, but this was not included in this particular app as that would be just disgusting no matter which way you go.