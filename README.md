# Full-stack Technical Task

Welcome to the Propelr technical task for the Full-stack JavaScript Engineer role. 

The aim of this task is to review how you tackle a "real life" project – however we don't want this task to **take no longer than 2-3 hours** so we're not expecting you to go deep on any one feature. 

## Goal

For this task we'd like you to create a simple full-stack web application that allows a user to view properties from a listing and add new properties. You should use **React** on the frontend and **Node** on the backend, and your code should be written in **TypeScript**. Any other technology choices are up to you. 

Please include two main frontend features: a **Property Listing** page and a form to **Add a Property** to the listing page:

### Property List
Create a page that lists all properties for sale, with each entry displaying at least the:
1. Property's address;
2. A photo of the property; and
3. Price.

The list should be fetched from your Node server.

### Add a Property
Create a form that allows a user to add a new property to the listing. At a minimum, the form should collect the:
1. Property's address;
2. A photo of the property, and
3. Price.

On form submission, the data should be sent to your Node server and added to the listing.

### Create a Simple Server
To process the information on the backend create a simple server with the following endpoints:

* `GET /properties` endpoint that returns a list of all properties; and a
* `POST /properties` endpoint that accepts a property object and adds it to the listing, then returns the updated list of properties.

## Considerations

Things to consider when building out your application:

* Error handling: Your application should handle potential errors gracefully. This includes form validation, server errors, etc.
* State management: What sort of state management is suitable for this application?
* Responsive design: While this application is simple, it should be resilient enough to respond to a different device size.
* Styling: Use CSS to style your components. You can use a CSS-in-JS solution, a CSS preprocessor, or plain CSS — whichever you think is most appropriate for this task.
* Testing: Include tests for your React components and your Node endpoints.

## What Would You Do Next?

We're going to build this web application into the next Zoopla or Rightmove and take the market by storm! If you had 20+ hours to further develop this project what would you build next and why?

## Deliverables

Please send a link to your code, in a public Github repository, to [talent@propelr.co.uk](mailto:talent@propelr.co.uk).

Your repository should include a README file explaining how to run the application and tests. This is also a great place to introduce any design or technology decisions you made and what you'd do if you had another 20 hours to further develop this project. 
