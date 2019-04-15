# TRIPP

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview
### Description
Tripp is a restaurant-discovery platform that connects users interested in exploring new food with restaurants looking for more foot traffic. Users can see restaurants they haven’t been to before, book an Uber to that restaurant, and get a discount/coupon on their food for doing so. 


### App Evaluation
- **Category:** Food/Restaurant-Discovery
- **Mobile:** This app would be limited to mobile, as it needs to interact with Uber’s API to get rides to the restaurant. 
- **Story:** Gives a Listview of a set of ten restaurants, sortable by categories like price and location, with text and picture descriptions and an Uber API integration for direct rides to that restaurant. If Uber ride is pressed, random code is generated: if restaurant sees code they give a certain portion of your meal off for dining in and sharing your feedback. Acts as a lead-generator and restaurant discovery platform, can be then plugged into Uber Eats recommendations, and if gamified for the user in the future, it could even be marketed to individuals as a “Let anyone be a food critic” app.  
- **Market:** Any individual could choose to use this app, and it would primarily be targeted at young, working individuals ages 25-40, as they would be the ones that tend to Uber and Lyft to restaurants anyway. Lyft and Uber already know where customers are going, so if they leverage their brand and network for 
- **Habit:** This app could be used as often or unoften as the user wanted depending on how interested they are in trying new food, and depending on what exactly they're looking for.
- **Scope:** First we would start with getting 10 restaurants to sign up, then we would get 25 people to do a test run of the service to provide feedback, then later, given more time and resources we could expand to 100 people, collect the information and present it to Uber and Lyft themselves. Even works if you partner with scooter companies to give access to restaurants. Data is gold here.

## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Logo page when app is loaded.
* User can select from a tableview of ten different restaurants
* Each restaurant is a separate page view, has a description of price, category of food, address, pictures and menu. Can explore using Yelp, Opentable and/or Square API integration depending on level of sophistication. 
* Question mark on bottom right corner that pulls up cards that give a description of what this app is. 
* Every restaurant must have Uber API “ride to this restaurant” button. 
* If Uber button is clicked, code is generated, and restaurant gets that code from the beginning of the day, limited one per purchase per visit so individual brings that code in, he/she gets a portion off the meal.

**Optional Nice-to-have Stories**

* Integration with Yelp API for automatic-restaurant pulling. 
* Dynamically generated restaurant cards that let you swipe on different places to add to your restaurant collection. 
* Sign-in feature + User profiles 
* Restaurant Playlists, Social twitter like feature where people can blast their restaurant and you can check-in with them.
* A ride history tab 
* Open-table integration for quick booking to restaurant.
* Instead of Uber API, settings tab can let you choose whether you have Uber or Lyft to set which app the button redirects to, with the restaurants address restored. 
* Language change in settings also possible.

### 2. Screen Archetypes

* Logo/opening screen
* TableView and ten individual restaurant pages. 
* Each page has a restaurant’s description, picture(s) and some added elements
* Each page has a “take a Tripp here” button that connects them to Uber API. Explore way to get a guest ride, no account required given temporary information for the purposes of not needing Uber account. Or set up backend account that all users use when they take a ride. 
* Question mark button at end pops-up a series of cards about the description of the app. 
* Once Uber button is pressed, should automatically redirect them to the Uber App
* In Tripp App, next page should be a code that’s preset for the day at that restaurant. 


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Restaurants
* Back 
* Settings

Optional:
* Music/Encounter Queue
* Discover (Top Choices)

**Flow Navigation** (Screen to Screen)
* Restaurants-> Restaurant selection
* Restaurant selection (if Uber is called) -> Jumps to promo-code
* Restaurant selection (if Uber is called) -> Uber API
* Settings -> Toggle settings

## Wireframes
<img src="https://github.com/tripp-app/Tripp/blob/master/Tripp%20Wireframe.jpg" width=800><br>
