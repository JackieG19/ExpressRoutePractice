### Express Route Practice (part 2)

*In your existing Express project, create a new github branch called part 2:*

- Take all your existing routes from part one and export them into a part one router.

- Update all your existing routes to use correct status codes.

- Update your query route that if the user provides no query parameters that you respond with an appropriate status code and message. (there is likely more than one applicable response here you could apply)

- Create a new Todo router.

- Create a todo array: 
  - give it one object with the minimum attributes:
    - id
    - title 
    - author
  - add at least one more attribute of your own choice that fits with a task.

- Create a get route that will return all todos in an array.

- Create a dynamic get route that accepts a parameter that is used to return one tasks.

- Create a dynamic get route that will return all posts that match the given parameter. (warning be careful that this route does not conflict with the previous get route.)

- Create a post route:
  - that takes the attributes for a new task 
  - Add this new task to your array
  - Send an error with an appropriate status if any of the attributes are not provided.

- Create a delete route that takes an id and removes that task from your array

- Create an update route that takes an ID as well as attributes for a task and update the existing task.

**_Note: All following routes should respond with an applicable status code. 
Some status codes will be accepted as applicable even if one is more commonly used. 
Simply use logic and reasoning to pick one and we will discuss the codes used in a future class._**

**Challenge:** Do not require all attributes in order to update the task.

**Extra Credit:** Create a delete route that accepts the author, route should delete all tasks made by that author.
