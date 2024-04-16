# LightBnB Project

LightBnB is a simple, AirBnB clone with the following features:

<b>User Authentication:</b> Users can sign up, log in, and log out. Passwords are securely stored using hashing.

<b>Property Listings:</b> Users can create property listings with details such as title, description, price per night, number of bedrooms, number of bathrooms, location, and photos.

<b>Search and Filter:</b> The application allows users to search for properties based on location, dates, number of guests, and other criteria. Users can also apply filters to narrow down the search results.

<b>Booking:</b> Users can request to book a property for specific dates. Hosts can approve or decline these booking requests.

<b>Reviews:</b> After a stay, guests can leave reviews for properties they've booked. Hosts can also respond to these reviews.

<b>User Roles:</b> The application distinguishes between hosts and guests. Hosts can manage their listings, view booking requests, and respond to reviews. Guests can browse listings, make booking requests, and leave reviews.

<b>Database:</b> The application uses a database (psql) to store user information, property listings, bookings, and reviews.

<b>Front-end and Back-end:</b> The application has both front-end and back-end components.


## Getting Started

1. [Create](git@github.com:TrevorJohnSullivan/LightBnB.git) a new repository using this repository as a template.
2. Clone your repository onto your local device.
3. Install dependencies using the `npm install` command.
3. Start the web server using the `npm run local` command. The app will be served at <http://localhost:3000/>.
4. Go to <http://localhost:3000/> in your browser.

## Note

When you add a new property to the database, it will not appear in the My Listings area of the application because it does not have a review or an average rating.
Therefore, to validate the output, just check that the property has been added by querying the database directly in PostgreSQL.

## Dependencies

- Express
- Node 5.10.x or above
- psql

## Screenshots