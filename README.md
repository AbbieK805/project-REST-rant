# Project REST-Rant

REST-Rant is an app where users can review restaurants.

Routes for site

Method | Path | Purpose
:---: | :---: | :---:
GET | / | Home Page
GET | /places | Places index page
POST | /places | Create new place
GET | /places/new | Form page for creating a new place
GET | /places/:id | Details about a particular place
PUT | /places/:id | Update a particular place
GET | /places/:id/edit | Form page for editing an existing place
DELETE | /places/:id | Delete a particular place
POST | /places/:id/rant | Create a rant (comment) about a particular place
DELETE | /places/:id/rant/:rantId | Delete a rant (comment) about a particular place
GET | * | 404 page (matches any route not defined above)

The following information will be required for each place (restaurant) 

Name | Data Type | Description
:---: | :---: | :---:
name | string | Name of restaurant
city | string | City where restaurant is located
state | string | State where restaurant is located
cuisines | string | Type of food served at the restaurant
<<<<<<< HEAD
pic | string | URL of picture of restaurant
=======
pic | string | URL of picture of restaurant
>>>>>>> 1a07b978fd47abfa5e68539bd6825ec2f38533b2
