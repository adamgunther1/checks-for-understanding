## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?

Node is a runtime environment for running javascript server-side

2. What is Express? Why is Express similar to in the Ruby world?

Express is a lightweight Node framework. Express is to JS what Sinatra is to Ruby

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

```
app.get('/api/v1/items', (request, response) => {
  call on controller
})
```

4. What do we use Knex for?

We use Knex to interact with our database

5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?

Use Express API to have routes that call on controller which call on the model that query the database. On the front-end application, use html as views and api calls in models.

6. How do you execute raw SQL in node?

database.raw('SQL')

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

advantages - one page application that interacts with API on backend. 
disadvantages - more complex authorization and authentication.

#### Review  

8. Describe DNS.

DNS provides a DNS lookup based on a url to the ip address of a server to request data from the server

9. What does writing clean code mean to you?

DRY, SRP, readable, OO

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?

Hotel, has Rooms (modules for kitchen, hotel room, lobby), has Floors, has Elevators, has beds, has televsions.
