# HomeMe



#HomeMe

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Enlists and views listings of real estate properties present in your choice of area on the map.It allows registered users and admins to post listings and provide the user a filtered search of best value properties.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** 
	Real Estate/Bidding
- **Mobile:** 
	this app could be developed on any ios device and be almost as viable to build it on a computer. However mobile version gives the easy of access that computers fail to provide.

- **Story:**
	 A user can casually scan through the App to see the listings that have been uplaoded by the admin and registered brokers.If they wish to get further details they would have to login as a registered user if they wish to place a bid or contact the owner.

- **Market:**
	Any individual who just moved to the city or is looking for a change of apartment would be our target customers. 

- **Habit:**
	this app would be used by an individual until he finds his desired property. We also expect people who are real estate brokers to look for properties on our apps.

- **Scope:**
 	Initially we would begin with gathering listings from open source apis. The initial listings would help us gather some traffic on the website. We plan to inlcude rental properties to open the app to all the new customers who are looking to rent their spaces.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Users can login and logout.
* Users have a profile that can be personalized.
* User logs in to access previous bookmarks and preference settings.
* Profile pages for each user. 
* Settings (Accesibility, Notification, General, etc.)


**Optional Nice-to-have Stories**

* highest/lowest priced houses filtered.
* filter by type of housing
* search/filter by location
* filter by size
* filter by most recent listings
* filter by no. of rooms

### 2. Screen Archetypes

* Login / Sign up screen
   * Sign up screen asks the user to input a range of personal info.
   * ...
* User Profile screen
	*Allows user to change personal info.
	*Update/ access previous bookmarks and preference settings
	*Allows user to change app settings (Accesibility, Notification, General, etc.)
* Maps screen displaying all the listings
   * filter options dropdown to input personal preferences.
   * navgation buttons at the bottom to view saved homes, User listings, updated info on saved homes etc.
   * 

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Listing Updates
* Profile 
* Settings 

**Flow Navigation** (Screen to Screen)

* Log in > Invalid Account > Sign Up
* All Listings > Search 
* Profile > Your Listings 
* Settings > Navigate Settings 

## Wireframes
<img src="https://i.imgur.com/cOSCVG1.jpg" >


### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
#### Post

   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | listingId     | String   | unique id for the user post (default field) |
   | author        | Pointer to User| image author |
   | image         | File     | image of the listing |
   | comments      | String   | details of the property |
   | favoriteCount | Number   | number of people auto favorite |
   | createdAt     | DateTime | date when post is created (default field) |
   | updatedAt     | DateTime | date when post is last updated (default field) |
### Networking
- Home Screen
      - HTTP GET all users /users
      _ HTTP GET all property /property
      _ HTTP POST register user /register
      _ HTTP POST login /login
      _ HTTP PUT update description /update/:id
      _ HTTP DELETE delete request /delete/:id

### Unit 10 
- Creating data models & digital wireframes

    - status of the issue :
        - Created data models
        - brainstormed & implemented some ideas about wireframes

    - sprint for next week 
        - Integrate Backend into the App
        
    - completed user stories
        - integrated backend tables for feed view controller
        
    - Gifs :
    <img src="http://g.recordit.co/GsZBff1biM.gif" >

### Unit 11
- Backend Integration
    
    - status of the issue :
        - integrated parsing tables on backend
        
    - sprint for next week :
        - Using Api to pull data for the App
        
    -  completed user stories
        - implemented parsing for pulling api data
        
    - Gifs :
    <img src="http://g.recordit.co/GsZBff1biM.gif" >
    
### Unit 12
- Pulling data from API
   
   - status of the issue :
        - researched various API's for the App
        
    - sprint for next week :
        - final project deployment & testing various cases  
        
    - completed user stories
        - successfully implemented APi pull request to populate the feed view
        - implemented data store and verifiction for log in view controller
        
    - Gifs :
    <img src="http://g.recordit.co/GsZBff1biM.gif" >
    
### Unit 13
- Project deployment & testing
   
   - status of the issue :
        - solving bugs and front end constraints
        
    - sprint for next week :
        - prepare for presentation
        
    - completed user stories
        - ran various tests
        - completedm app deployment on user device
        - fixed constraints for different views
        
    - Gifs :
    <img src="http://g.recordit.co/GsZBff1biM.gif" >
