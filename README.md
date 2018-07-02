# FoodHygieneRatings
2nd Year Android programming assignment

A screencast of the app running through the tests for the assignment can be found here:

https://youtu.be/4U75zYJ0yS0


The purpose of this app is to query a server which contains information about the food hygiene ratings from the Food Standards Agency for all eateries in the UK. The user can search in three different ways, by GPS co-ordinates, by business name and by postcode. The server returns data about the closest 10 businesses in JSON format. The app then presents the data in table format, using relevant pictures for the ratings. If the search term is too short (minimum 3 characters) or otherwise returns no results, the app displays a relevant error message.

When you click on one of the names, the app loads a Google Map showing the locations of all the results of the search, with the one you clicked on highlighted and centred. Sometimes the results in the database generated by the councils place more than one business with exactly the same GPS co-ordinates. In this case the app will generate a random but close by alternative in order to separate them.

## Screenshots
![Application Screenshots](/Screenshots/Application-Screenshots.png "Application Screenshots")
