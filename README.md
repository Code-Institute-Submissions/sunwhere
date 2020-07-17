# SunWhere?

![SunWhere logo](https://github.com/Mr-Smyth/sunwhere/blob/master/assets/images/sunwhere-logo.png "Site logo")

<div align="center">

[View the website on GitHub Pages](https://mr-smyth.github.io/sunwhere/index.html)


This is a dynamic user friendly responsive utility project website, for quickly and easily comparing the weather for different locations.

This project will be submitted for my Interactive Frontend Development, and second milestone project, in my Full Stack Software Development course. The project will is a working interactive front-end website, demonstrating the technologies I have learned so far.
</div>

--- 
# UX

SunWhere is a browser based application designed to help the user decide which destination to choose for a weekend away, based on predicted weather.

The main objective of this website is to provide the user with a simple way to compare the weather for multiple locations, for the upcoming weekend. Then once this has been achieved it will return those results. The results are formatted in a simple single viewpoint page, in descending order, with the best location highlighted. 

**The results are calculated using rates of rain, sunshine, cloud, humidity, wind and temperature. The score is then combined for the weekend and converted to a percentage.**

 The user can then easily see the best location, with a percentage comparison making the system simple to understand.  
The user can then click on any of the results and will then be directed to an information page, where the complete weather line up for the weekend will be displayed in a simple, clear responsive style.  

The user can also scroll down to view a map with markers highlighting points of interest. The user can also use the predictive searchbox within the map, to search and add further markers to their map. The searches are Bias to, but not confined to, the viewport of the map.


## User Stories
The Application is intended for users of any age who are deciding on a location for their mini break, or even just a day out.


The following user stories have been identified:

1.  As a user, I want the home screen to be inviting and with information relevant to my location. 
2.  As a user, I want to quickly and easily understand the purpose of the application.
3.  As a user, I want to easily understand what i have to do.
4.  As a user, I want to easily enter my information.
5.  As a user, I want to see an obvious and quick way to get my results.
6.  As a user, I want to be able to see an obvious comparison of predicted weather for my entered locations, including my home or current location.
7.  As a user, I would like to select my preferred location from the results, and see places of interest for that location.
8.  As a user, it would be helpful to get a wildcard location returned, for a place not on the list, but which has a good rating for the next weekend.

<br>

## Opportunities arising from user stories:

<div align="center">
 
|Opportunities | Importance | Viability / Feasibility
|-----|:------:|:-----:|
|**Clean Visually Appealing Interface** | 5 | 5 |
|**Purpose of Application Explained** | 5 | 5 |
|**Clear Simple Instructions** | 5 | 5 |
|**Easy Location Input** | 5 | 5 |
|**Simple Submission and Viewing of Results Procedure**| 4 | 5 |
|**Clearly Defined Results** | 4 | 5 |
|**Suggest Places of Interest** | 4 | 5 |
|**Return WildCard Location** | 2 | 3 |

</div>

<br>

## UI Structure

### Structure

Considering the above user stories, i have decided upon the following UI Structure and styling:

* Home Page:
  * User will be requested to allow geo-location.
  * A clear spacious area with the weather for the users current location displayed, with relevant weather icon.
  * Below the current weather will be a Introduction and brief explanation, with an area below this for submitting locations.

* Results Page:
  * Reachable upon submission of the locations.
  * Containing the results from the 4 user locations and the results for the users current location.

* Information Page:
  * Reachable upon clicking on a result, the page will weather for that location for the upcoming weekend and also provide a map of places of interest. 
  * A disclaimer.

* Common:
  *  A Site logo at the top of the page will provide a link to the home page from subsequent pages, and will represent the only required common site navigation.
  *  The Footer will provide copyright information only.
  
### Styling

Considering the purpose of the site, The following styled theme was decided upon.

* Colours:
  * linear gradient blue/white/orange TBD
* Wireframes: 
  * [Home Page](https://github.com/Mr-Smyth/sunwhere/blob/master/wireframes/SunWhere%20-%20Home-Page.pdf)


  * [Results Page](https://github.com/Mr-Smyth/sunwhere/blob/master/wireframes/SunWhere%20-%20Results-Page.pdf)
  

  * [Information Page](https://github.com/Mr-Smyth/sunwhere/blob/master/wireframes/SunWhere%20-%20Information-Page.pdf)


## Features

### Home Page
The home page opens with a common site logo top center, styled to a matching theme, and also provides the sites only common required navigation, returning the user to the home page once clicked.

The background image is dynamic, and will change depending upon the weather in your current location.  
The weather for the users current location is displayed on top of this background image in a semi transparent container. The weather details displayed depend upon the current screen size and will increase in detail as the screen size increases.

The user can also click on the temp, to convert it to fahrenheit.

A brief introduction, invites the user to scroll down or "click here" to get more information. Once the user does this, they get a full explanation of what the site does and how to proceed.
The User can enter up to 4 locations into a small form with integrated google searchbox, to help with the location names.

"Click for Results leads the user easily to the results page.


### Results Page
The results page opens with the common site logo, and the soothing background linear gradient.

The

The results are displayed in a simple no clutter column, that also responds to all screen sizes. The results are clearly defined, with the best result always highlighted at the top, and in descending order after that.  
The results are calculated as a percentage which provides a simple easy to understand comparison. The user is invited to select a location, which leads the user simply to the information page.



### Information page
The Information page opens with the common site logo, and a static image background.  
The weekends weather for the selected location is then displayed in 3 containers, on top of the background image. The weather details displayed depend upon the current screen size and will increase in detail as the screen size increases. 

The background image is set to 95vh, to allow the user to notice the top end of the map section, inviting them to scroll down to investigate further.

The map area displays a map centered above the user selected location. It uses google places to provide a preloaded set of markers which mark out points that may be of interest to the user.  
The user can also use the searchbox, inside the map, which has google searchbox integrated, to provide a simple user experience. Any searches done will helpfully post new styled markers to the map.

The searchbox is also Bias to, but not restricted to the current viewport.

A final message and a disclaimer completes the site layout.

It may be worth noting that the user can navigate back to choose a different location, as the search results remain, until the user returns to the home page by clicking the site logo.

