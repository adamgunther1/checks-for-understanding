## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?

* The idiosyncrasies and how they differ from Ruby.

2. What are some tools to help debug JavaScript code?

* debugger, pryjs, console.log

3. What are some tools you need in order to unit test your JavaScript?

* mocha, chai

4. What is the syntax for invoking a function?

* ()

5. What is CORS?

* Cross-Origin Resource Sharing

6. How do we enable CORS?

* In the configuration of RACK CORS middleware to allow certain methods. From the requester, requires adding a headers object to the request

7. What's `this` in JavaScript?

* Refers to the object that the function is being acted upon

8. What is Webpack and why is it useful?

* Webpack is a builder to deliver javascript to the browser

9. When/why do you want to use event delegation?

* Use event delegation to call on elements that are loaded on document ready for elements that will be loaded dynamically

10. What is a callback function?

* A callback function is a function that is passed through another function as an argument

11. What's `npm` and what do we use it for?

* Node Practice Manager - is used to package javascript to download libraries, run tests, etc

#### Review  
12. What's the MVC design pattern? Describe each part of MVC.

* Model, View, Controller. The controller controls all the actions and keeps the application together. The view contains everything that will be loaded on the client side. The model contains the object, its attributes, relationships, and methods and logic for what will be shown and/or saved.

13. What are a few ways to optimize a Rails application?

* ActiveRecord/SQL queries, caching, background workers, lazy-loading, minifying, pagination

14. What's a background worker? When would we want to use a background worker?

* A background worker uses a queue to fire off actions in the background to not affect load time
