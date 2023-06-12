## ES6 Classes

**1- Classes are a template for creating objects.**

**2- Can a class declaration be hoisted?**

In JavaScript, unlike function declarations, class declarations are not hoisted. 

**3- How would you describe a constructor and contextual “this” to a non-technical friend?**

a constructor is like a recipe or blueprint that helps create objects with specific characteristics, and "this" is like the word "I" or "me" that refers to the current object being created or used.

## Using Express Routing

**1- Within Express, what does routing refer to?**

In the context of Express, routing refers to the process of matching incoming HTTP requests to specific handlers or functions that should be executed to handle those requests. 

**2- What is the difference between a route path and a route method?**

The route path defines the URL pattern or the path segment of the URL that the server will match against incoming requests.

The route method corresponds to the HTTP method or verb used in an HTTP request.

**3- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**

In Express, the next parameter is used to pass control to the next middleware function or route handler in the chain.

## Express Routing

**1- What is an Express Router?**

In Express, an Express Router is a feature that allows you to create modular and reusable sets of routes and middleware.

**2- By what mean do we initialize express.Router() in an express server?**

import the Express module in server file , then create an instance of the Express Router using the express.Router() method.

**3- What do we use route middleware for?**

route middleware is used to perform specific operations or checks on incoming HTTP requests before they reach the actual route handler.

**Links to an external site.Things I want to know more about**

more about middleware