# Week 4 Assessment

In this week's assessment, imagine you have been scheduled for a half-day interview.  The first part of the interview is a technical challenge!  You will have 90 minutes to complete a technical challenge and provide some reflection.

## Technical Challenge (10 points)

### Setup
* Fork and clone this repository.
* Click on 'Planets' in the navbar and make sure you see the 8 planets of our solar system.
* Checkout a new branch and complete the following task.

Your task is to add the explored planets of the galaxy 'Far Far Away' (all of the planets in the star wars films, as outlined in the SWAPI API).

We would like you to get the necessary data by consuming the [SWAPI](https://swapi.dev/) API.  A successful mission will:
* Use HttpClient to make an API call to SWAPI when a request comes in (to get the most up-to-date information!)
* Display the known planets of the Far Far Away Galaxy on a view.
  * Be sure to include the name and population of each planet.

Outside of those requirements, you may choose to add any additional functionality!

When finished, create a PR and include your answers to the reflection questions below in a PR comment.

## Reflection Questions (6 points)
* What about this challenge was most difficult for you?
I think the most difficult part of this challenge was consuming the API. This is one of most confusing topics for me yet and didnt realize this til today. I struggled configuring the URL and setting up the client to the point where im not sure If the client was created and used.
  
* Highlight one peice of code that you wrote that you are especially proud of.
For me it would be the GetPlanets method ![image](https://github.com/iworsham/Launch-Mod5W4-Assessment/assets/35874300/5e7dbcef-ca0e-45a8-81eb-d207725e9343) I made this to the best of my knowledge and I am confident it is correct or close to that. Just couldnt get the interface to work correctly to run the code. Definitely couldve with more time.

  
* What would you do next, if we gave you another hour?
  Considering my stopping point, with another hour I would further debug my code and find my issue in the interface and finish getting planets to display in the application. Another hour would most likely loosen the collar on some of this stuff for me.

## Rubric

This assessment has a total of 16 points.  Earning 10 or more points is a pass.

For the technical challenge, we are looking for:
* 2 Points - successful creation of a HTTPClient
* 2 Points - correct URL configuration
* 1 point - making a get request
* 2 points - turning the response into a list of planets
* 3 points - getting the requested planets showing up on a page

