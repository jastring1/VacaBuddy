# VacaBuddy
Tripp Stringfield

## Deployed Link
 https://jastring1.github.io/VacaBuddy

Vacabuddy is a web application that allows a user to search for information based on Cities

## Technologies

- HTML5
- BootStrap4
- Javascript
- JQuery
- API services (Zomato, TicketMaster, OpenBreweryDB, Untappd, Google Maps)

## Functionality

#### The application propmts a user for 3 Input fields:

- City
- Date of Arrival
- Date of Departure

![VacaBuddy Landing](/Images/landing.JPG)

#### Once the user completes the form they have 3 search areas to explore:

- Restaurants
- Events
- Breweries

#### Restaurants

The Zomato API will return the 20 most trending restaurants for a given city
Google maps will display the city on a map and add markers for each of the returned restuarants
The table below the map will provide the user with:

- The name
- The type of cuisines served
- Overall Rating
- More Info

![VacaBuddy Restaurant](/Images/rest1.JPG)

When the more info button is selected, a modal will pop up and give the user access to:

- A photo from the restaurant
- The phone number
- The address
- A list of the 5 most relevant reviews available

![VacaBuddy Restaurant2](/Images/rest2.JPG)

#### Events

- The Ticketmaster API will return a list of events in the city captured from the form, in the date ranges 
that have been given by the user
- Google Maps will redraw the markers on the map to show the user where these events are taking place
The table below the nap will provide the user with:
- The name of the event
- The date of the event
- The time of the event
- More Info

When the more info button is selected, a modal will pop up and give the user access to:
The name of the team/performer
- A picture of this team/person/group
- The name of the Venue of the event
- A picture of the venue(if provided by API)
- A link that will land the user on the page to purchase tickets for the event

![VacaBuddy Ticketmaster](/Images/ticket.JPG)

#### Breweries

OpenBreweryDB provides the list of breweries determined by the users input
Google maps will redraw markers for these entities
The table below the map will provide the user with:

- The name of the breweries
- The type of brewery
- The address of the brewery
- More info

When the More Info button is selected, the Untappd API will search for the brewery by Name
If a brewery is returned from the API call the user will be provided with:

- The Brewery's Logo
- A phone number
- The Address
- A table that displays the breweries current tap list with information on each beer for the user

![VacaBuddy Brewery](/Images/brew.JPG)





