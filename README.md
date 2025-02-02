# REST Discussion Questions

## Learning Goals

- Define REST conventions
- Practice domain modeling

## Instructions

**1.** Take 30 minutes with your table; choose a _resource_ that your server
contains data about. A resource will be something like 'books', 'users',
'episodes', or 'characters', something that your users will be performing
CRUD actions on.

Write out the 5 RESTful routes from the curriculum that correspond to the 4 CRUD
actions. Be sure to include the HTTP verb, the name of the route, the path (URL)
and the corresponding CRUD action (Although there are actually 7 RESTful routes,
this phase will only use 5 of them).

- What SQL (if applicable) would be fired in the controller actions for each of
  the routes?
- Why might it be important that routes and resources have a conventional structure?

| HTTP Verb | path (URL) | Route name (Index, etc.) | CRUD Action | SQL |
|---|---|---|---|---|
|   |  |   |  |  |

**2.** Let's say you have built an app that is a blogging platform. You have a Post
and an Author model and you have controllers and routes for the CRUD actions
of each model. You sit down at your computer and visit
`www.youramazingrailsblog.com/posts`:

- What kind of web request is this making? (i.e. is it a `GET`, `POST`, etc request?)
- What controller action (i.e. which method in which controller will the
  request get routed to) will receive that web request?
- What is the response that your Rails app will send back to the client, i.e.
  the browser?

**3.** Spend a few minutes mapping out a domain model for a parking lot. How would
you model the relationship between cars and spaces? How would you keep track
of how long a car had been parked in a space? How would you keep track of how
much money someone would need to pay for having parked a certain amount of
time?
