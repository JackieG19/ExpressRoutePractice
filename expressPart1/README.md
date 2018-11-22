### Express Route Practice (part 1)

Create the following routes:

- Create a get route that displays Your personal name.

- Create a dynamic get route that then says something using the parameter sent to it.

- Create a dynamic query route: 
  - This query route should accept EITHER two nums (num1 and num2) or a word. 
  - If numbers were given it should send back some sort of mathematical equation and the result. 
  - If it is a word it should spell the word one line at a time.

- Create a post route that accepts a username and password. 
  - In your route have a static username and password
  - Then check to see if the username and password send match. 
  - If they match send a json with a status of "logged in" 
  - Or respond with a json that has a status of "invalid credentials"

- Final item in your server.js file create a global variable array.
  (Can fill this with random strings to start if you like.)

- Create a post request that has an item attribute, add the item to the array.

- Create a delete request (works like post) that has an item attribute, remove the item from the array.

- The routes should respond back with an error if the user tries to add an item that already exists in the array and should respond back with an error if the item does not exist in the array.

**Extra Credit:**

Find out how to respond with the correct http status code for the two errors.

