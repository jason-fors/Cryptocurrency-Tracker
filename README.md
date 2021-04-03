# Python Live Project

## Introduction
After completing courses in HTML/CSS, JavaScript, SQL and Python at The Tech Academy, I had the opportunity to participate in their "Python Live Project" with a team of instructors and students.  Using Azure DevOps for project management and following the Agile management approach, the students contributed applications to the "AppBuilder9000" project using the Django Framework.  The project included checking out stories to complete, working with others in a large-project environment using a version control system, conforming to project conventions, daily stand-up meetings, and code retrospectives.  My contribution to the project was a Cryptocurrency App, which allows users to create and modify their own database of cryptocurrencies, as well as look up specific information on cryptocurrencies provided by another site via API.  What follows is a summary of some of the highlights and lessons learned from this experience.

## Creating Database and Interface
To allow users to enter information into the database, a model had to be constructed.  I chose a simple structure where the more permanent characteristics of a cryptocurrency would live in one model while those that would change daily would be in another. I added views and templates for users to create a "Currency" and "Status".  To permit full CRUD functionality, I then added a details page where users could view selected information for all of their currencies in one table, which included links to pages where users could edit or delete records, as well as view all the data for a single record. 

## Implementing API
To further enhance the capabilities of this application, I added pages where users could see the top 7 currently "trending" coins as identified by coingecko.com, using their API.  When the link to the "Trending Coins" link is clicked, a request is sent to the API and the response parsed, and a new page is rendered with the latest list.  I also leveraged their API to create a page where users could look up selected information on any coin made available in coingecko's API via a simple search, following the same process.

## Skills Acquired
* Working with a group of developers to collaborate on a larger project, implementing a project management system and the Agile managment approach.
* Checking files out in a version control system, following proper procedures for maintaining the integrity of branches and the master while merging changes, following project conventions, and creating pull requests.
* Creating forms and widgets and rendering views including form reponse data in Django, using Django Template Lanaguage tags and variables.
* Accessing a 3rd party site API, parsing the JSON response and rendering selected data from the reponse in HTML.
* Propertly setting up unique url routing and following naming conventions within Django for a larger project.
* Implementing template inheritance in Django to ensure consistency in design across a website. 
