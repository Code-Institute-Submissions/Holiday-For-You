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

* As a general user, "I wanted to have a look at some "popular destinations" tab but every time I click the link it takes me to the top of the main page."
This is a feature that will be added in later releases of the website. The reason the button takes the user to the top of the page is because "#" has been used as the link href, lacking a specified 
id it goes to the top of the page. 

* As a gernal user, "I can look around the map but that's about it. I can't click on anything else. But I'd like to go to Rome please." 
There could be many reasons as for why the API did not work however, as it has worked on multiple platforms it can be reasoned that this is a user error. 
To help avoid this in the future the instructions will be written more clearly to help diminish the likelihod of this happening. 

* As an admin user, "I wanted to test to the Google API Maps and Places it took a few attempts to get the result I wanted" 
After some testing it is clear the API requires a specific sturcture so that the user can get the intended result. To combat this the instructions will be rewritten to reflect this.

## Features

### Existing Features

* Navbar 
    * The navbar is positioned at the very top of the page this is an industry standard and there's no reason to reinvent the wheel. However, the navbar contains a few tricks to assist in UX. 
    First is the integration of drop downs allowing for subcategories this also comes into play more as the user's screen becomes smaller. In this circumstance the entire navbar becomes a drop 
    down this is partly for styling purposes, as well as taking up less of screen. The last aspect is the name of the site disappears only leaving the logo and drop down. Oringinally this felt 
    unintuitive but on smaller screens there is no row of promations before the "welcome" text so the website starts off with a "Welcome to Holidays For You!" message, still saying the name of 
    the company.

* Promotion Cards 
    * The promation cards' purpose is all in the name they promote potential holidays to any visitors to the site. What isn't in the name is where they are positioned, after the navbar this is 
    the second thing you see, as well as the first thing on your way down to the API. This forces the user's eye to the promotions taking their interest for a few moments. The cards also have 
    summarised informative text just enough to interest the user in the advertisement. On smaller screen all this info takes up too much space and would result in the user having to scroll for 
    some time to get past the advertisement. This is not the purpose of the quick glance approuch they are meant for. So with this in mind the cards first go from four to three and later lose their 
    informative text. This doesn't take away too much from the cards as they have been given eye catching images to also attract the eye of the user. Until they disappear completely on smaller 
    screens as there is not enough space to accomodate the feature. 

* Instructions for the API usage
    * This is a very small but important section of the page. The steps are written in a non-formal manner to help relax users who go to use the API. As some users will not have experience 
    with applications such as this one. The steps are separated into their owns lines this is the user read them as steps without making it obvious that they are. Again this is all down to 
    relax an inexperience user to the thought of using something they are unfamilar with, as this can be a daughting task.  

* APIs
    * The APIs used are the Google Maps and Places APIs supplied by Google. 
        1. Maps
            * This allows for the website to display dynamic and static maps of real world places, as well as allow them a street view 360&deg;. This is very helpful as users can search anywhere 
            in the world and be taken to it. This required very little effort on my part, other than reading through the documentation and understand the implmentation process everything else 
            was very straight forward saving myself a lot of time. 
        2. Places
            * This API is the backbone of the website whereas maps allows a user to see anywhere the places API allows the user to see what places of interest there are in an area. The API itself 
            can be a bit finicky so instructions has been written to help users when using the API. Despite some small shortcoming the Google Places API works very well for the purposes required.

* Types of Holidays Shortcuts
    * These are to help users find the perfect holiday for them by asking subtle, simple questions the link themselves don't work at the moment but will link to pages with more information on 
    the topics. Other than this they shift from horizontal to vertical for the purpose of the different sized screen a user might have. The dynamic styling helps to keep the page working 
    smoothly no matter the screen sized giving all users a nice experience. 

* Covid 19 travel Warning 
    * With the world in its current state it would be irresponsible to not warn users of the potential risks of traveling at the present time. The reason for this warning being positioned so 
    closely to the holiday links is so that users see it before clicking on a "type of holiday link". The title of the section is also in bold for the purposes of the catching the user eye. 

### Features Left to Implement

* Navbar Links 
    * Currently the project is just a single webpage this can easily be expended upon by creating additional pages and linking them through the navbar. 

* Promotion Cards Pages and Links
    * The promation cards still need information pages about them to help inform users about what is being offered. On top of this links would be needed to link these pages together. The benefit 
    of this is that these holidays can be advertise to the user properly, rather than just being eye catching and then scrolled past.

* Holiday types Pages and Links
    * At the moment the holiday types are just for decoration to expand upon this multiple pages need to be made and then linked to. This would create a more dynamic experiece for users, 
    as there would be more for them to experiece and explore. 

## Technologies Used 

* [HTML5](https://html.spec.whatwg.org/multipage/)
    * **HTML5** was used to build the structural elements of the webpage.
* [CSS3](https://www.w3.org/Style/CSS/Overview.en.html)
    * This was used to style the elements made by **HTML5**, as well as position them.
* [Github](https://github.com/)
    * Used as a hosting platform for testing and deploying the final product. Along with helping with any rollback needed to access backup files.
* [Gitpod](https://www.gitpod.io/)
    * Was used for its ready to code environment allowing the project to begin and end.
* [Bootstrap](https://getbootstrap.com/)
    * The external **CSS** styles provided by **Bootstrap** was used to help make complex styles simple tasks saving time.
* [Google Fonts](https://fonts.google.com/)
    * Used to embed more fonts to allow for a bespoke experience.
* [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign=en_tier1_desktop_branded_x_exact&km_CPC_CampaignId=1490375427&km_CPC_AdGroupID=55688909257&km_CPC_Keyword=lucid%20chart&km_CPC_MatchType=e&km_CPC_ExtensionID=&km_CPC_Network=g&km_CPC_AdPosition=&km_CPC_Creative=442433236001&km_CPC_TargetID=aud-561781099678:kwd-55720648523&km_CPC_Country=1007106&km_CPC_Device=c&km_CPC_placement=&km_CPC_target=&mkwid=sVrXnwD0X_pcrid_442433236001_pkw_lucid%20chart_pmt_e_pdv_c_slid__pgrid_55688909257_ptaid_aud-561781099678:kwd-55720648523_&gclid=Cj0KCQjwy8f6BRC7ARIsAPIXOjiQYeykbPL_LmTiHj4BypQ90ja1hToA7P0X--EVGSU0_VrDA2s-GBAaAivTEALw_wcB)
    * Used to make wireframes for the planning stages of the project.
* [Google Maps API](https://tray.io/connectors/google-maps-integrations?utm_campaign=DG|G|Search|Connectors|All&utm_source=Google&utm_medium=ppc&utm_term=%2Bgooge%20%2Bmaps%20%2Bapi&gclid=Cj0KCQjwy8f6BRC7ARIsAPIXOjjKFm3BSuYEeC3GKVl2gQOxF5FTZy2t5Ikca_5d0cgYCyY4WKKWcJwaAjkoEALw_wcB)
    * Embedded into site for the foundation of the **Google Places API**, making a dynamic map for users to use. 
* [Google Places API](https://developers.google.com/places/web-service/overview)
    * The main aspect of the project used to allow users to search for places of interest within a specified location.

## Testing

1. Navbar
    * i. Load website
    * ii. Ensure nav bar has loaded 
    * iii. See if "plane-cropped.png" has loaded in correct position with styling
    * iv. Check stylings on nav bar
    * v. Ensure dropdowns function correctly
    * **vi. Check all links function as intended**
    * vii. Check media queries with different screen sizes
    * viii. Make sure links become a drop down, and title centers itself
    * ix. Title disappears

Links do not function as intended as with the "#" placeholder they link to the top of the page, this will be fixed as pages are linked 
in feature releases.

2. Promotion Cards
    * i. Ensure loaded correctly on largest screen, with 4 cards
    * ii. Go to break point 4 turn to 3 Cards
    * iii. Next break "info" text disappears
    * iv. Cards disappear completely

3. API Instructions
    * i. Load as intended
    * ii. Forms to all screen sizes where the text is understandable

4. APIs
    * i. Map loads
    * ii. Check "Map" and "Satellite" modes
    * iii. Check if "Labels" can be turned on and off
    * iv. Check "Fullscreen" mode and if can be exited
    * v. Check zoom in and out buttons
    * vi. Check "Street View" mode
    * vii. Check compass in "Street View"
    * viii. Check back button can be used to exit "Street View"
    * ix. Check if search box can be clicked
    * x. Check if search box can be typed in
    * xi. Check if auto suggestions appear
    * xii. Check if appropriate results appear

5. Holiday Types
    * i. Display correctly
    * **ii. Check if links work as intended**
    * iii. Ensure horizontal list becomes vertical list as screen becomes smaller

Links do not function as intended as with the "#" placeholder they link to the top of the page, this will be fixed as pages are linked 
in feature releases.

6. Covid warning
    * i. Loads correctly
    * ii. Forms with screen size and is readable

### Bugs

1. The API can be very specific with how it handles the search function. Taking the user to an entirely different# location than intended. This isn't something that can be fixed. However, to avoid users 
recreating the bug the instructions will be worded to encourage proper use of the API. 

## Deployment

To host the website I made use of **Github** as a hosting platform. To accomplish I had to link **Github** to **Gitpod** this is quite a simple process having me add **Gitpod** as a browser extension to 
my browser of choice. From there I had created a repository then I can proceed to open it with **Gitpod** and begin to develop the code. After enough code has been written I can then host the 
website from the settings options scrolling to the **Github** pages section choosing to host off of the master branch. This will then provide me a link to access the website from. 
The project has no differences between the development and deployed versions, this is so it is easy to update and maintain in the future as both are carbon copies of each other. Therefore 
do not contain different configuration files and run on the master branch provided by **Github** pages.
 
In order to run the code locally you will need **Github** and the **Gitpod** browser extension from there you will need to access **Github** repositories and open it within **Gitpod** using the added options 
from the extension. 

## Credits

### Content

* The text for the footer section was taken from [TUI](https://www.tui.co.uk/holidays).

* Code within maps.js was taken from [Google Maps Platform](https://developers.google.com/maps/documentation/javascript/examples/places-searchbox).

* Navbar, image cards and list for holiday links was taken from [Bootstrap](https://getbootstrap.com/docs/4.4/components/navbar/).

### Media

* bath-england.jpg taken from [Wikimedia](https://commons.wikimedia.org/wiki/File:Villa_dundar_kas_turkey_-_panoramio.jpg)

* pantheon-in-rome.jpg taken from [PublicDomainPictures](https://www.publicdomainpictures.net/en/view-image.php?image=213076&picture=pantheon-in-rome)

* plane-cropped.png taken from [pngkey](https://www.pngkey.com/detail/u2q8r5a9y3u2r5t4_plane-logo-png-sketch/)

* tokyo-japan.jpg taken from [Flickr](https://www.flickr.com/photos/pedrosz/38162201235)

* turkey-villa.jpg taken from [Pikist](https://www.pikist.com/free-photo-vqdbo)

### Acknowledgements 

Inspiration for this project came from multiple places the main sources were 
* Disney World (the exact website can't be found)
* [Expedia](https://www.expedia.co.uk/Holidays)
* [TUI](https://www.tui.co.uk/holidays)
* [First Choice](https://www.firstchoice.co.uk/holidays)