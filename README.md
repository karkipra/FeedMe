# Feed Me

A recipe application for Android using an external API with a login function and persistent storage options.  <br />
Created by:
- Pratik Karki
- Marty Toney
- Hüseyin Altınışık.

## Motivation

This project was created as a Final Project for Mobile Software Development at AIT-Budapest, Fall 2018. Our goal was to use all the different features we learned about Android Studio and create a fully-functioning publishable app that has real-life uses. Creating a recipe app became a common theme that we pursued as it allowed us to explore fetching data through APIs and have it be customized to be as easy as possible to use. 

## Demo

Here are some screenshots from our latest demo:

![Home Page](/screenshots/Homepage.png?raw=true){:height="400px" width="200px"}
![Search Bar](/screenshots/Searchbar.png?raw=true){:height="400px" width="200px"}
![Side Bar](/screenshots/Sidebar.png?raw=true){:height="400px" width="200px"}

## Features

- Login function using Google Firebase that stores user information and can be accessed from any device.
- Persistent storage using Room so that recent search history does not disappear.
- Uses an external API known as Food2Fork to search for recipes (more details in the next section).
- Option to mark recipes as favorites and access them at any time.
- 25 items are shown per search results and are categorized by relevance. They include these parameters:
    - Display picture of the final product
    - Name
    - Option to favorite a recipe
- Finally, an section about the contributors.    

## API

We used the API of the recipe website [Food2Fork](https://www.food2fork.com/), which ranks recipes by social score and has a regularly updated social ranking for search keywords. The API we used was the free student version which allows up to 50 API calls per day. More information on the API can be found [here](https://www.food2fork.com/about/api).

## Future Updates

- Tutorial for first time users (using sharedPreferences)
- Ability to edit favorited recipes to user's own likings
- Search function can be modified with these features:
    - Number of results per page
    - Search by ingredients
    - Search by cooking time
- Add friends and see their recipes    
- Open source features and publishing to Google Play Store    

