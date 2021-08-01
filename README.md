# React-Book-Reading-List

This app adds React Router to the Books application in order to render a book details page as well as a no match 404 page.

## User Story

### Part 1

* Set up React Router inside of the `client/src/App.js` file.

  * The `/` and `/books` routes should both render the `Books` component page.

### Part 2

* Inside of the `pages` folder create a `NoMatch` component. This is the component for our 404 page.

* Add a route for the new `NoMatch` component. This should only render if no other routes are matched. e.g. `/sjdfhjsdhfjsa` or `/notarealroute/lalala` should both render the `NoMatch` component page. 

  * Use the `Switch` component from the React Router Dom library to accomplish this. An example can be found [here](https://reacttraining.com/react-router/web/example/no-match).

### Part 3

* Inside of the `pages` folder create a `Detail` component. This component displays additional information about a book.

* Add a route for the the new `Detail` component. This should render when the `/books/:id` path is matched. e.g. if a book's `_id` is `59a39cf2549cf482c814333f`, then `/books/59a39cf2549cf482c814333f` should render its book `Detail` page.

* Inside of the `Detail` component, add code so that when the component mounts, we retrieve the book for the rendered route and save it to `book`. e.g. when the route is `/books/59a39cf2549cf482c814333f`, an AJAX request should be made to get the book with an `_id` of `59a39cf2549cf482c814333f`. If completed successfully, you should see the book's synopsis on this page.

  * Refer to [URL params with React Router](https://reacttraining.com/react-router/web/example/url-params) to accomplish this.


## Review

* The URL of the functional, deployed application.

* URL of the GitHub repository (https://github.com/KrishnaKakarla88/React-Book-Reading-List)

### To clone this repository
* git clone https://github.com/KrishnaKakarla88/React-Book-Reading-List