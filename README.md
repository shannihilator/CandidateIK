# MyPerson: An App for Organizing Contacts

## A proof of concept for a full-stack application that uses the SalesLoft API to retrieve data about contacts.

### Planning and Process

Technologies Used:
* Trello (https://trello.com/b/UpCaKZCW/myclient-customer-tracking-app)
* Git, branching
* VS Code, Postman
* React, React Router
* Ruby on Rails
* Axios, HTTParty

### Wireframes


### Process

The minimum viable product outlined in the directions only call for the list of users from the API. While I call the API from the backend in rails in this application, there is not necessarily a use case for a database in displaying the user data in the browser.

Adding another model, e.g. "My Contacts" could be used to save contacts from the API for personalization by the user. I will continue to work on that feature on a separate branch after submitting my progress so far.

While I am comfortable with the concepts in Redux, I am extremely new to it and continued without it in this application to turn this around in a more reasonable amount of time. I do think as this application grows, Redux would help manage state to be more accessible throughout the application. At its current size, Redux is not absolutely necessary and it was easy enough for me to pass props along and call the API as needed.

I tried to nest components as much as possible to avoid having to refresh the page with a page redirect. Each component has its own responsibilities and I tried to store state as high in the component tree as possible.

### Future Development
* Auth would be helpful for controlling who sees what data here.
* View one user view for a closer look at one individual user. This could even render more information about that user via the SL API.
* A "My Contacts" feature could store contacts to a user so that notes can be made or as a way to only store relevant users.
* Completing the third tier of development for a fuzzy search to identify possible duplicates.