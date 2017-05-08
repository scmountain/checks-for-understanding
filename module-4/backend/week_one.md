## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
in all honesty very little was completed. I think just becoming more familiar with JS syntax was useful on the sorter
2. What are some tools to help debug JavaScript code?
pryJS!!!
3. What are some tools you need in order to unit test your JavaScript?
chai, mocha
4. What is the syntax for invoking a function?
()
5. What's the difference between `==` and `===` in JavaScript?
double compares the values, triple compares the exact value and type
6. What's the difference between asynchronous and synchronous JavaScript? 
determines what is called and when. AKA the stack is not there for async
7. What's a callback function and what are some reasons when we use/need callback functions?
a callback is a reference to functionB that is executed inside of functionA
8. What's the biggest difference between a promise and a callback?
call back is async, promise runs callbacks in sync
9. How do we setup a route when creating an API with Node and Express?
app.get('route here/, function(request, response)
10. What's `npm` and what do we use it for?
it is node package manager and it is our "gems"

#### Review  
11. What's the MVC design pattern? Describe each part of MVC?
controller: is the operator that directs incoming/outgoing response/request to either the model or the view.
model: takes request from controller and nteracts with the DB to return info to controller
view: takes info to and from the controller for client to see/send
12. What is AJAX? What are some benefits of using AJAX?
GREAT cleaning product! :)    Ajax allows us to render new information without refreshing the page/view
13. What's a background worker? When would we want to use a background worker?
Backround worker is a process that will be running "behind" your scipts, so that the site can move faster.
