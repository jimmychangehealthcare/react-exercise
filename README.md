# Instructions

Link to finished app: https://react-exercise.now.sh/

Your task is to build a "Saved Search" functionality for US cities in JavaScript and React. See the finished app in the link above for how the app should function and look like.

You have freedom to implement this app using any component tree structure and hierarchy as you see fit while adhering to JavaScript and React best practices. You may `npm install` any libraries to help your development within reason, i.e. do not install a save search component that someone else already made. The only hard requirements are to use React, and you may take advantage of any feature of the React API (this app uses React v16.13.1 bootstrapped from `create-react-app`; we also **strongly encourage the use of React Hooks and modularly breaking down large components into smaller ones**).

## Requirements

- Main Requirements:
  - [ ] App dynamically shows list of US cities with city's name, country, and number of likes
  - [ ] Next to each city is a checkbox that user can check if they want to move the city to "My Saved Search" queue, with the queue displaying the number of cities stored in it. (Button to move to "My Saved Search" queue)
  - [ ] From my Saved Search, user can delete the city from the queue which will be then transferred back to the list of all cities.
- Bonus:
  - [ ] Accomplish the above requirements with Redux.
  - [ ] Categorize
  - [ ] App dynamically shows list of US cities whose names have partial match to the user search input.
  - [ ] Implement frontend tests using Jest, React Testing Library, and/or Enzyme.

## Notes

- To start the app, run `npm install` to install dependencies and `npm start` to start the local server at http://localhost:3000.
- For your data, you can import a static JSON file of US cities located in `src/us-cities.json`. Therefore, you will **not** have to request data from a remote server.
- You can use Chrome Developer Tools, including React Developer Tools. You may also consult documentation online. Please explain your debug process to us out loud whenever you hit an obstacle.
