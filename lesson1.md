## Welcome to lesson 2

We are advancing a lot this week. We will be building our first backend.

Last week we dove into a basic html page. We will be extending it massively by this week going into a backend.

### Why is a backend important

A backend is where most of the magic happens on an actual website. The reason for doing this is

1. Interact with databases (think storage of information, users data, etc.)

2. Offload the stress of computations from the backend (backends can cache results)

3. The backend may be used else where for things such as automation, or mobile apps.

The generalized logic of a full stack web should be that the frontend does minimal work, while the backend handles more complex things. This allows you to focus your frontend to just be about appearance.

### Assignment

This week we will have a very basic username storage setup.

1. Using node.js, express, create a server that serves up an index.html page.

2. Make an endpoint `(/user)` where you can POST a name, and it stores it on the server (in a variable is fine)

3. On the index.html page in step 1: Make a text input with a button to POST the data to the /user endpoint

4. On the index.html page in step 1: create Javascript to call another endpoint `(/users)` GET

4. Display this list of users

This is a hard assignment and will require a good bit of googling!

### Next Week:

We will make it dockerized and deploy it locally 
