# project-bazarra
## Project Overview
BAZAARA is an app created with the intent of saving people money while shopping for groceries. BAZAARA is a progressive web application that enables store price aggregation especially for groceries as well as featuring live price updating. Users will be able to visit and use BAZAARA on both PC and mobile devices to allow flexible usage. Each user will have their own personal account that they can log into. Once logged in, the user can search for the prices of items individually or in bulk via the ‘grocery list’ feature which saves their selections for future use. The app will let the user know about current prices, trends, and future expectations for the cost of goods. It supports user price reporting via a built-in barcode scanner and photo analysis to enable aggregation of local pricing data. 

The Infastructure is being hosted on GCP with Firebase and MongoDb. Visit [here](https://www.postman.com/bazaara/workspace/team-workspace/api/aed9dcf6-5c2f-4e28-8a5a-45cb01bc2ed6/version/82e5d025-163d-4527-91b5-0ed5474ac483) to see our API Documentation

## Installation
> not needed for web app, access web page via [Web App Url](#web-app-url)

## How To Build
- project is not containerized, will need to install [node.js](https://nodejs.org/en/download/) and define the following connections: 

- npm will come with node.js installation
- Will need to create a private .env file at project root. Define the following keys: **BAZAARA, MONGODB, PORT, FBProjectID:**

>BAZAARA=[name of the project]
> 
>MONGODB=[url of mongodb cluster]
> 
>PORT=[desired port to run express app]
> 
>FBProjectID=[number provided by firebase project]

MongoDB cluster has two default databases: BazaaraGrocery with GroceryCollection and BazaaraUsers with UserCollection
  - Table and collection names can be altered in [globals.js](https://github.com/Capstone-Projects-2022-Spring/project-bazarra/blob/main/globals.js)

Create firebase project and add [Firebase admin sdk json to root level of project](https://firebase.google.com/docs/admin/setup), keep thi file private
  
  
How to install:
  
1. ``` git clone https://github.com/Capstone-Projects-2022-Spring/project-bazarra.git ```
2. ``` npm ci && node app.js ```

## Current Release 
[v3.0.0](https://github.com/Capstone-Projects-2022-Spring/project_bazaaraUI/releases/tag/v3.0.0)

## Testing
[TESTING.md](https://github.com/Capstone-Projects-2022-Spring/project_bazaaraUI/blob/main/TESTING.md)

To test server 

## Team Members
- Ryan Babala
- Lin Li Oechsle
- Shivani Patel
- Terence Peterson
- Rico Rodriguez
