## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
get requests data

delete removes data

post posts data

put updates data

2. What is Sinatra?

puts ruby onto the web


4. What is MVC?

model, view, controller - the setup for an app

5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?

more specificity, need to use methods that HTTP understands, CRUD allows you to do most things one would want to do with databases

6. What types of variables are accessible in our view templates without explicitly passing them?

instance variables

7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    @count = 1
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?

@name = 'Mr. Ed'

9. What's the purpose of ERB?

erb interpolates ruby to put on the web

10. Why do I need a development AND test database?

to test methods and random data, then test with real data

11. What's responsive design?

able to respond to screen size (mobile, laptop, tablet)

12. What is CRUD and why is it important?

Create, Read, Update, Delete - covers most database functionality for an app

13. What does HTTP stand for? 

Hypertext transfer protocol

14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?

<%= %> for a single line of code

<% %> for a block of code

15. What's an ORM?

Object Relational Mapper - ActiveRecord

16. What's the most commonly used ORM in ruby (Sinatra & Rails)?

ActiveRecord

17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.

GET - '/restaurants'

GET - '/restaurants/:id'

GET - '/restaurants/new

POST - '/restaurants'

GET - '/restaurants/:id/edit

PUT - '/restaurants/:id'

DELETE - '/restaurants/:id

18. What's a migration? 

Creating datbases, columns, and could seed data

19. When you create a migration, does it automatically modify your database?

need to migrate after create

20. How does a model relate to a database?

creates relationships and requirements for database

21. What's the difference between agile workflow and waterfall method?

agile does an iteration at a time as opposed to all designing, planning, coding, testing in their respective chunks

22. What is the difference between `#new` and `#create`?

new doesn't save - crate is new and save combined
