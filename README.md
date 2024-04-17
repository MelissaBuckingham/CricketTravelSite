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

The data schema is arranged in such a way so that a user can add a Category, but also they can add a Product that can be placed within a Category in order to keep the data tidy and searchable.

USER STORIES

![Screenshots of User Stories](images/UserStories "User Stories")

WireFrame

![Screenshots of the Wireframe](images/Wireframe.png "Wireframe")




## Bugs and Testing

I Manually tested Traveling Wickets every step of the way, using the web preview function on Gitpod. I also tested it once it was deployed on Heroku to check that it was still funtioning as I had initially expected it to.

I had an issue early on, when I couldn't copy the allauth files, because they had been added to a different directory than what I was expecting. Using the search function on the terminal, with the assistance of lovely people on Slack, I soon found the correct directory, and was happy coding again!

I have checked that all links are working correctly and there are no issues.

JS Lint

Below is the result on JS Lint when I enter the JS Code:
![Screenshots of the JS Lint test of site JavaScript](images/JsLint.jpg "JS Lint")


I have used a mixture of manual testing and automated testing in the creation of this ecommerce website, the automated testing makes sure that it is in line with accepted standards, and the manual testing makes sure that it is comfortable for the user to use and has the correct level of interactivity.

W3 Validator
![Screenshots of the W3 test of HTML](images/W3HtmlValidation.jpg "W3 Validation HTML")
No issues found at all.

Jigsaw CSS Validation
![Screenshots of the Jigsaw test of CSS](images/jigsawValidation.jpg "Jigsaw Validation CSS")
No issues found at all.

I spent a lot of time trying to create a popup that confirms whether the user really wants to delete an item or not. I was doing it just on the products.html file, and testing on the product-detail page, so I couldn't work out why it wasn't working. I eventually realised that all I needed to do was add the code to product_detail.html. Problem solved!

## Deployment
My site was deployed on Heroku at https://fantasy-database-93b7701d6f44.herokuapp.com/

Help received from ElephantSQL.

Debug set to False for deployment.


## Credits
I used the Beutique Ado walkthrough project as an inspiration

I gained a lot of assistence from stack overflow and Slack for how to create the delete confirmation pop-up.



