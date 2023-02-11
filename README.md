# API-Tests

Below are some API test samples that I tested from my experience.

**Test CRUD - http://qachallenge.ro/api/**

Read all

Read all the information ID /First Name/	Last Name

Method used: POST

Parameters:

key: action  and value: fetch_all
![all](https://user-images.githubusercontent.com/120104620/218257630-d4292f8e-ebb0-44f2-a10f-8a06830b18a3.png)

Create

Create user by first name and last name.

Method used: POST

Parameters:

key: first_name and value: Toto represents the first name
key: last_name and value: Groso represents the last name

![new](https://user-images.githubusercontent.com/120104620/218257634-13f7aa2c-e630-4718-8230-00a52881638e.png)

Update

Update a user's first or last name by id.

Method used: PUT

Parameters:

key: id and value: 457 represents the persons's id in the database. 
key: first_name and value: emma represents the first name
key: last_name and value: cremma represents the last name


![update](https://user-images.githubusercontent.com/120104620/218257638-7f92bd05-4c11-4b7a-a7ae-bed6de9b2207.png)

Delete

Delete a user by id.

Method used: DELETE

Parameters:

key: action and value: delete represents the action to delete a user by id. The other parameter is the user id 44

![delete](https://user-images.githubusercontent.com/120104620/218257640-09821ebe-67ca-413d-9bdd-775949d5f448.png)

-----------------------------------------------------------------------------

**Weather Tests - https://openweathermap.org/forecast5**

API for searching weather forecast for 5 days with data every 3 hours by city name.

Parameters:

key: q and value: Madrid represents the city
key: appid represents your unique API key generate by https://openweathermap.org/
key: units represents units of measurement, can take values: standard, metric or imperial
key: lang and the value: ro represents the language

![weather](https://user-images.githubusercontent.com/120104620/218258225-bc2a9119-ec9e-4b3b-86d0-5d126e78c967.png)

