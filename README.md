# Capstone project ideas

## Required functional components

* A client application&mdash;an Android app, a Java SE application, web pages constructed dynamically on the server side using a templating or component approach, etc.

    The front end for this application will be an Android app, which 

* An application server, usually in the form of a REST service provider.

* A database server&mdash;typically&mdash;but not necessarily&mdash;a MySQL or Derby database server. (Note that the application server and database server may reside on different hosts or the same host; they may even be embedded in a single program.)

    The inclusion of a back-end database (which is required) doesn't preclude the use of a database on the client side&mdash;e.g. a SQLite database on Android. In fact, your client implementation will still be expected to include some kind of persistent data store.

* Communication between the client application and server application. Typically, this will consist of one or more REST (or REST-like) services published by the server application, and consumed by the client application. These services should allow the client application to create, read, and update (and optionally delete) objects stored on the server side, in accordance with the business logic of the server side.

* Support for multiple simultaneous client application users, connected as relevant to the server application.

* Automated pre-loading of any relevant base data sets (client- and server-side).

* User authentication (this may&mdash;and often does&mdash;leverage the services of an OAuth2 provider, such as Google).

## Task 1: 6 February

Write (below) a description of your capstone idea. Don't worry about a specific structure, but make an attempt to address all of the points above in some way (even if briefly). As with your Android project ideas, feel free to copy this file (keeping the `.md` extension on any copy) and complete this task for multiple project ideas.


## Todd's Capstone Project Idea

   This will be an Android App.  This app allows the user to point his phone at a celestial object or constellation in the night time sky, touch the screen at the location of the object, and that celestial app will be identified immediately in context of other celesial objects.   The presentation of the celestial sky will be aesthetically pleasing as possible.  The app will require acquiring a database containing the locations of those objects.  Also, to make the app work, gps location capability tied to angle tilt of the phone will be required.  The coordinate information needed for the app to locate and display a given celestial object will be downloaded when the app is down loaded and then updated periodically.  I believe a server will be needed for obtaining gps coordinates of the user.  This app will allow users to log in and provide to other users useful information such as particularly good locations for observing the stars.  Only those who log in to the service and have filled out a form will be able to communicate with others via the app: A third person user authentication service will be used for this part of the service.
   
### User Stories
#### [User Story 1](https://github.com/deep-dive-coding-java-cohort-6/capstone-project-ideas-tnordquist/blob/master/user-story-1.md)

#### [User Story 2](https://github.com/deep-dive-coding-java-cohort-6/capstone-project-ideas-tnordquist/blob/master/user-story-2.md)

#### [User Story 3](https://github.com/deep-dive-coding-java-cohort-6/capstone-project-ideas-tnordquist/blob/master/user-story-3.md)
