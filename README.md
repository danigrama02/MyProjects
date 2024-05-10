# MyProjects

/*
Hello my name is Daniel and here on my GitHub profile you can find some of my personal projects.
This file explains what the projects are about.

# HolobotChatbot
HolobotChatbot is a chat bot that knows how to respond to programming related questions,
it was trained with 2 mil. questions and answers from stack overflow. 
The chatbot is hosted on a Django server that is secured with JWT tokens.
More about it can be fond in the ReadME associated with the project.

# Weather on the Road
This project is my bachelor's degree final exam. This one has 3 microservices that work together in order to help
the user with his roadtrips. It computes the weather along a roadtrip that the user choses on a google map. 
The weather is computed by a regression model.

First component the UI :
  The user interface of the app can be found in the licentafrontend repo, it is a web app developed with the help 
  of the Angular framework. It has a login page, a page for creating the account, the main page containing the map
  , the weather list, an alers list for extreme weather alerts. It also has a profile page where the user can see its 
  past roadtrips.

Second component the java middle service:
  Here starts the backend, this service is a Java Rest server developed with the help of Spring framework,
  it is secured with JWT tokens. It handles the requests from the web app, handles users and their history
  and makes requests to the last service in order to get the weather predictions and parses them in a foramt 
  accepted by the front end, also has the logic for computing the time when the user will be in a certain location 
  in order to get more accurate weather predicitons.
  

*/
