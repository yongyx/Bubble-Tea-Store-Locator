# Bubble-Tea-Store-Locator

## Introduction
This project is a Python project that utilizes web scraping, GUI and Databse techniques to create a store locator for bubble tea stores in select cities of the Bay Area. The data is in json format parsed using Yelp's API. The cities that we included are:

* Cupertino
* San Jose
* MountainView
* Palo Alto
* Santa Clara
* Sunnyvale
* Saratoga

We display a window to the interface that gives the user 3 choices.

<img width="402" alt="Screen Shot 2022-03-29 at 6 47 50 PM" src="https://user-images.githubusercontent.com/56427665/160734387-a5d71cd3-e269-457c-b797-4df12ad7a62d.png">

### Choice 1: Display Boba Shops
This choice allows users to display a list of bubble tea stores. The user selects a range given in miles, which then displays a list of bubble tea stores within that given range. There are a total of 4 ranges of distances given.

<img width="448" alt="Screen Shot 2022-03-29 at 6 49 24 PM" src="https://user-images.githubusercontent.com/56427665/160734542-cbe9fed7-c3bc-4792-91b0-8e6bb6a2cf89.png">

### Choice 2: Search for boba shops
The user can search for a bubble tea store by either city or "dollar sign", which is Yelp's way of categorzing how expensive it is. It will be arranged in ascending order from least expensive to most expensive.

<img width="201" alt="Screen Shot 2022-03-29 at 6 56 12 PM" src="https://user-images.githubusercontent.com/56427665/160735178-9487a340-65c0-4958-803c-b0bddbae7082.png">

  * Search by City:
<img width="475" alt="Screen Shot 2022-03-29 at 6 56 47 PM" src="https://user-images.githubusercontent.com/56427665/160735236-ceb3c2aa-5ebe-419d-b4ad-3663d76782b5.png">

  * Search by Dollar Sign
<img width="402" alt="Screen Shot 2022-03-29 at 6 57 24 PM" src="https://user-images.githubusercontent.com/56427665/160735317-48af0dc7-5745-4cf8-9882-9b2e0201b718.png">

### Choice 3: Number of 4-5 starred boba stores in each city
This choice displays the number of 4-5 starred bubble tea stores in each city. This is displayed in the form of a bar graph.

