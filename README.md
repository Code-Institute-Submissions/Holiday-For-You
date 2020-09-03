# Holidays For You

Holidays For You is a holiday platform designed to help users find spot of interest near them or near to where they're going. This can all be achieved easily through the use of the 
Google Maps and Places API. The API is situated within the centre of the page beneath a row of promotion cards. The API itself is easy and intuitive to use, however not all users are alike 
so a few lines of instructions are written in a non formal manner to help users make the most of the websites capabilities.  
Alongside this the site will allow for booking of holidays and then suggest using the map to help them plan their trip. As of right now that is in development. However, the website holidays has 
been made in mind to accomodate these changes, by having buttons in place to link to these places, as well as a common theme in mind to use across the pages. Bootstrap has also been used 
to help in the presentation of elements on the page. 

## UX

Holidays For You was designed to be an extension of a holiday booking site. To achieve this the Google Maps and Places API has been integrated into the website, with the purpose of allowing 
visitors to see local attractions before or after they arrive at their destination. The webpage is left relatively empty to focus on the API, this helps users not get distracted on their way 
down to the map positioned near the bottom of page. The reason for this is so users must pass by promotions on bigger screens, and more importantly the instructions on how to use the API before 
arriving at it. This is to help users understand how to use the software before they even get to it. This is so users with less experience with these types of applications don't get frustrated, 
leaving the site prematurely. 

The reason for my site being an appropriate way to achieve the intended goal is the software is simple and intuitive to use lacking any unnecessary features involved with the working of the API. 
The process of getting to the map is stream lined and easy, no matter what screen size the user is on the instructions for the map are always visible allowing the user to always know they are in 
the right place and have not become lost. 

In terms of the theme of the page I have used a skyblue in colaboration with the plane logo to represent the travel that the users will be taken. On top of this black has been chosen as the 
colour of the type face to make it stand out, allowing users to easily read the text. along with this the Montserrat Alternates font has been used as this provides an easy to read and 
aesthetically pleasing appeal. Another aspect of the header is the nav bar which is left simple making use of drop downs allowing for main categories and sub-categories of linked pages, as 
well as on smaller screens the entirety of the nav bar becomes a drop. This is to avoid it taking up too much screen real estate. The final aspect is that the header has a shadow effect this is 
to create the illusion of depth, as well as the coordinate with the place logo giving the effect of flight.

Straight after the header is a row of promational cards. These are formatted showing an image of the destination followed by a brief description of the area. This is so the user can at glance get 
information on these promations without paying much attention to them. On a larger screen this format works very well. However, on a screen with less space these would take up too much space. 
To combat this the cards shrink in stages first they go from four to three so the cards are still readable, second the text disappears leaving just the image, this stops the user being able 
to get information at a glance despite this the eye catching images should still entice the user to click on a card and learn more from there. Third the cards disappear all together leaving 
just the instructions and the API. 

Following after is the instructions for the API and the API itself. In terms of the instructions they put into steps to achieve this four separate &lt;p&gt; tags have been used. Forming them in 
their own rows created the illusion of a "1. 2. 3. 4." step count without forcing the user to do so. This area is left plain for the sake of not taking away from the user's attention on the 
information they are receiving. 

For the API map the styling have been left how the creator intended them this is because is the formatting is the same as that as Google Maps. So users that are familiar with that platform will 
feel at home here. This allows for intuitive use of the API.


### User Stories 

* As a general user, I wanted to have a look at some "popular destinations" tab but every time I click the link it takes me to the top of the main page.
This is a feature that will be added in later releases of the website. The reason the button takes the user to the top of the page is because "#" has been used as the link href, lacking a specified 
id it goes to the top of the page. 

* As a gernal user, I can look around the map but that's about it. I can't click on anything else. But I'd like to go to Rome please. 

more stories. try to use at least one of each type (assigned through membership, admin, editor).

## Features

1. Navbar 
    * The navbar is positioned at the very top of the page this is an industry standard and there's no reason to reinvent the wheel. However, the navbar contains a few tricks to assist in UX. 
    First is the integration of drop downs allowing for subcategories this also comes into play more as the user's screen becomes smaller. In this circumstance the entire navbar becomes a drop 
    down this is partly for styling purposes, as well as taking up less of screen. The last aspect is the name of the site disappears only leaving the logo and drop down. Oringinally this felt 
    unintuitive but on smaller screens there is no row of promations before the "welcome" text so the website starts off with a "Welcome to Holidays For You!" message, still saying the name of 
    the company.

2. Promotion Cards 
    * The promation cards' purpose is all in the name they promote potential holidays to any visitors to the site. What isn't in the name is where they are positioned, after the navbar this is 
    the second thing you see, as well as the first thing on your way down to the API. This forces the user's eye to the promotions taking their interest for a few moments. The cards also have 
    summarised informative text just enough to interest the user in the advertisement. On smaller screen all this info takes up too much space and would result in the user having to scroll for 
    some time to get past the advertisement. This is not the purpose of the quick glance approuch they are meant for. So with this in mind the cards first go from four to three and later lose their 
    informative text. This doesn't take away too much from the cards as they have been given eye catching images to also attract the eye of the user. Until they disappear completely on smaller 
    screens as there is not enough space to accomodate the feature. 

3. Instructions for the API usage
    * This is a very small but important section of the page. The steps are written in a non-formal manner to help relax users who go to use the API. As some users will not have experience 
    with applications such as this one. The steps are separated into their owns lines this is the user read them as steps without making it obvious that they are. Again this is all down to 
    relax an inexperience user to the thought of using something they are unfamilar with, as this can be a daughting task.  

4. APIs
    * The APIs used are the Google Maps and Places APIs supplied by Google. 
        1. Maps
            * This allows for the website to display dynamic and static maps of real world places, as well as allow them a street view 360&deg;. This is very helpful as users can search anywhere 
            in the world and be taken to it. This required very little effort on my part, other than reading through the documentation and understand the implmentation process everything else 
            was very straight forward saving myself a lot of time. 
        2. Places
            * This API is the backbone of the website whereas maps allows a user to see anywhere the places API allows the user to see what places of interest there are in an area. The API itself 
            can be a bit finicky so instructions has been written to help users when using the API. Despite some small shortcoming the Google Places API works very well for the purposes required.

5. Types of Holidays Shortcuts
    * These are to help users find the perfect holiday for them by asking subtle, simple questions the link themselves don't work at the moment but will link to pages with more information on 
    the topics. Other than this they shift from horizontal to vertical for the purpose of the different sized screen a user might have. The dynamic styling helps to keep the page working 
    smoothly no matter the screen sized giving all users a nice experience. 

6. Covid 19 travel Warning 
    * With the world in its current state it would be irresponsible to not warn users of the potential risks of traveling at the present time. The reason for this warning being positioned so 
    closely to the holiday links is so that users see it before clicking on a "type of holiday link". The title of the section is also in bold for the purposes of the catching the user eye. 