# Capstone project ideas

## Required functional components

* A client application&mdash;an Android app, a Java SE application, web pages constructed dynamically on the server side using a templating or component approach, etc.

* An application server, usually in the form of a REST service provider.

* A database server&mdash;typically&mdash;but not necessarily&mdash;a MySQL or Derby database server. (Note that the application server and database server may reside on different hosts or the same host; they may even be embedded in a single program.)

    The inclusion of a back-end database (which is required) doesn't necessarily preclude the use of a database on the client side&mdash;e.g. a SQLite database on Android.

* Communication between the client application and server application. Typically, this will consist of one or more REST (or REST-like) services published by the server application, and consumed by the client application. These services should allow the client application to create, read, and update (and optionally delete) objects stored on the server side, in accordance with the business logic of the server side.

* Support for multiple simultaneous client application users, connected as relevant to the server application.

* Automated pre-loading of any relevant base data sets (client- and server-side).

* User authentication (this may&mdash;and often does&mdash;leverage the services of an OAuth2 provider, such as Google).

## Task 1: 6-7 October

Write (below) a description of your capstone idea. Don't worry about a specific structure, but make an attempt to address all of the points above in some way (even if briefly). As with your Android project ideas, feel free to copy this file (keeping the `.md` extension on any copy) and complete this task for multiple project ideas.
