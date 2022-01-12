# YelpCamp
YelpCamp is a web Application in which users can find campgrounds and review them. Users can also add their own campgrounds. A map has also 
been displayed for better searching. When a user enters a location, the map finds and shows it automatically. I have completely revamped the UI and made it into a dark mode for reducing eye strain. It is already populated with Indian cities. Implemented a fuzzy search with autocmplete feature using MongoDB Atlas search.

## Specifications
Authentication
User can register and login
Used Passport for that purpose
Authorization
User needs to be logged in to make any change(add,update or delete)
A user can only alter his posts or reviews
Functionalities
Campgrounds are marked on a cluster map using Mapbox API
Fuzzy search with automplete using MongoDB Atlas search
Client side and server side validations are done
Images of campgrounds are uploaded to Cloudinary
Images can be added and deleted after creation of Campground
CRUD functions have been implemented on Campgrounds
Flash messages were displayed
Sessions and cookies were used
Every Campground has it's location displayed seperately on a map

## Built with
- ### Front End
HTML, CSS, Bootsrap v5.0
EJS, EJS Mate
- ### Back End
NodeJS
ExpressJS
MongoDB
cloudinary
MapBox
passport(local-strategy)
JOI
connect-flash
morgan
sessions
helmet
mongoSanitize
sanitizeHtml
### Deployed using Heroku, database on MongoDB Atlas
