# Traveling Wickets - The Cricket Travel Site
## Description
The purpose of this ecommerce website is to provide cricket fans with the option to buy the full cricket holiday experience, including booking the event tickets, booking hotels, and booking the flights and travel to hotel and grounds.
- I wanted to create this ecommerce website which combines two of my passions: Travel and Cricket.
- I built this ecommerce website in order to showcase what I have learned so far through my level 5 diploma in Coding using django, python, allauth, and stripe.
- Troughout this project so far I have grown in confidence and feel like I can easily build an ecommerce website from scratch, and also make it interactive for the user, something  I previously did not feel capable to do.
- From studying the course material and other resources on the web, I have learned lots of different ways to get the ideas from my head to the code of my ecommerce website. It's been a thrilling ride!
 
## UX design

I wanted to make the user experience as easy to use but at the same time making the ecommerce website unique and interesting to use. 

I created a number of HTML files, all of which are extending from the base.html templete, in order that the finished project will be very interactive and fun to use.

The Django database allows for the creation, reading, updating and deletion of Categories and citiProductses. the Products are grouped according to their respective Categories.

I used a shades of green color scheme to go along nicely with the cricket theme.


USER STORIES

![Screenshots of User Stories](/media/UserStories.png "User Stories")

WireFrame

![Screenshots of the Wireframe](/media/WireFrame.png "Wireframe")


## Database Schema

The data schema is arranged in such a way so that a user can add a Category, but also they can add a Product that can be placed within a Category in order to keep the data tidy and searchable.

I built the database using Django, in which, a data schema refers to the structure that defines how data is organized within the application. Here’s a brief overview:

Database Configuration: The schema includes settings for the database engine, name, user, and password, which are specified in the DATABASES setting in settings.py.

Models and Fields: Django models represent tables in the database, and each model field represents a column in the table. The schema is defined by the models and their fields.

Migrations: Django uses migrations to manage changes to the schema over time. Migrations are generated when changes are made to the models and are applied to update the database schema.


## Accessibility Guidelines Complience

I created the site in order to comply to all accessibility guidelines:

Usage of div and span are limited as these don't tell the user anything about the content. Semantic elements preffered.

I used lanmarks such as "<header>" "<section>", and "<footer>" to allow the visually impaired to be able to navigate easily throughout the site.

All links use the href attribute, not using div or span to simulate a link.

I have followed the color contrast guidelines, so that writing on the images are easy to read.

Labels used where appropriate to enable the visually impaired.



## Bugs and Testing

I Manually tested Traveling Wickets every step of the way, using the web preview function on Gitpod. I also tested it once it was deployed on Heroku to check that it was still funtioning as I had initially expected it to.

Navigating between the pages via the back or forward buttons never break the site and there are no broken links.

I had an issue early on, when I couldn't copy the allauth files, because they had been added to a different directory than what I was expecting. Using the search function on the terminal, with the assistance of lovely people on Slack, I soon found the correct directory, and was happy coding again!

I have checked that all links are working correctly and there are no issues.)

I have used a mixture of manual testing and automated testing in the creation of this ecommerce website, the automated testing makes sure that it is in line with accepted standards, and the manual testing makes sure that it is comfortable for the user to use and has the correct level of interactivity.

W3 Validator
![Screenshots of the W3 test of HTML](/media/W3Validator.png "W3 Validation HTML")
There was a duplicate of the user-options ID, but I felt it was justified because one was on the main header, and the other was on the mobile-header, so in any one instance of the app there would only ever be one instance of the ID.

Jigsaw CSS Validation
![Screenshots of the Jigsaw test of CSS](/media/Jigsaw.png "Jigsaw Validation CSS")
No issues found at all.

I spent a lot of time trying to create a popup that confirms whether the user really wants to delete an item or not. I was doing it just on the products.html file, and testing on the product-detail page, so I couldn't work out why it wasn't working. I eventually realised that all I needed to do was add the code to product_detail.html. Problem solved!

## Deployment
My site was deployed on Heroku at https://fantasy-database-93b7701d6f44.herokuapp.com/

Data Stored on ElephantSQL, buckets on AWS.

Debug set to False for deployment.


## Credits
I used the Beutique Ado walkthrough project as an inspiration

I gained a lot of assistence from stack overflow and Slack for how to create the delete confirmation pop-up.



