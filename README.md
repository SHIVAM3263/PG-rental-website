# Pg-Life
## PG Life is a Full-Stack Web Application. This is a project that I was assigned to make during my Internshala Full Stack Web Development Internship Training. I got the guidance, and following that I made this web application with my own undertsnading and knowledge. It is customized according to what I thought would be better functionalities in this app, from the user perspective.

## Entire web-app is fully responsive and is operational from any device.

# Tech Stack:- HTML, CSS, Bootstrap 5, Javascript, AJAX, PHP, MySQL.

# This web app has the following functionalities:-

## The home page:-
### Search bar, where user can enter city name(in any case), and PGs listed in that city(if exists in database), will be shown as list.
### Contains main cities in the form of circular sections, clicking upon which user can get the list of pgs existing in that city.

## The PG list page:-
### Shows the list of all the PGs and their main features in the selected city, in the form of beautiful cards.
### Filter bar, using which the PGs can be sorted according to rent and rating, in ascending or descending order.
### User can see here which PG is being marked interested by how many users, to know popularity.
### After logging in, user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
### The heart icon toggles style in terms of fill color, when alternatively clicked to like or dislike the pg. Based upon click, interested user's number remains updated dynamically.

## The PG details page:-
### In the property list page, if any user clicks on "View" button, that pg's entire details is being displayed in the PG details page.
### Images of the selected PG is being viewed at top front as a beautiful carousel.
### The page shows all the details such as amenities, testimonials, address of the PG neatly.
### User can see the selected PG is being marked interested by how many users, to know popularity.
### After logging in, user can mark any PG(s) as interested, from the list itself, by clicking on the heart icon.
### The heart icon toggles style in terms of fill color, when alternatively clicked to like or dislike the pg. Based upon click, interested user's number remains updated dynamically.

## The dashboard:-
### Appears only for the logged in users.
### Shows the account details of the logged in users.
### Below profile details, there is a section for Interested properties, which shows the cards of those PGs which the logged in user marked interested, accross any city.
### From this list, user can click the heart icon on any PG card, to remove that PG from interested list, and that specific page section gets dynamically changed according to user's action.

## The Navbar:-
### Contains brand name.
### If NOT logged in, it shows option to Signup and Login.
### If logged in, it shows option to got to Dashboard and Logout. Also, it displays the user's first name who is being logged in currently, by using SESSION.
### Totally responsive toggler navbar.

## The Breadcrumb:-
### Beautify shows the relative location of the user in the web app.
### Contains hyperlinks to easily navigate back and forth an endpoint.

## The Footer:-
### Shows the list(containg hyperlinks) to show the list of PGs in the most popular cities.
### Displays copywright information.
