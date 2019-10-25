## Setup

To help speed up the process of moving from question to question we have provided a bunch of `app-#/` folders that have been created using the `create-react-app` CLI. Therefore, if you are currently on question 1, you will put your work inside of `app-1`. If you are currently on question 4, you will put your work inside of `app-4`.

- Run `npm install` in each `app-#/` folder before starting the questions.
  - You can either run `npm install` for each `app-#/` before starting question one or just remember to run `npm install` as you move from question to question.

You can then test your work for each question, as you develope a solution, by running `npm run start`.

## Set 1 - State, Class Methods, Capturing User Input, Mapping, Axios

### Question #1

Create a basic react app where you type in a text box and it shows up as text on the DOM.


### Question #2

Create an app where there is an array of data on state that is then shown on the DOM as a list. The array of data can be as simple as an array of strings. The list can be as simple as a list of `<h2>` elements.


### Question #3

Create an app where there is an array of data on state that is then shown on the DOM as a list. There should also be a way for the user to filter what's shown in the list. The array of data can be as simple as an array of strings. The list can be as simple as a list of `<h2>` elements.


## Set 2 - State, Class Methods, Capturing User Input, Props, Multiple Components

### Question #4

Create a `Login` component that has two text inputs, one for a `username` and one for a `password`, and a button to login the user. When the login button is clicked, an alert should be showed to the user that displays what the user typed in for the `username` and `password`.


### Question #5

Create an `Image` component that renders an `<img />` element. The `src` for the `<img />` should be passed down as a prop from the parent component. You can use whatever image URL you would like to or you can get a placeholder from <a href="https://placeholder.com/">Click Me!</a>


### Question #6

Create an app that displays a to-do list. You will need two components, the `App` component and a `Todo` component. The `App` component should be responsible for getting new tasks and storing the list of tasks. The `Todo` component should be responsible for displaying the individual tasks from the `App` component. The `App` component should create a list of 'Todo' components passing down a `task` into the `Todo` component as a prop and display the list.

### Question #7

Create an app similiar to question #6, except this time add a new third component called `NewTask`. `NewTask` should be responsible for adding a new task to a `task array` on the `App` component. Also add a new fourth component called `List`. `List` should be responsible for display the tasks inside of a `task array` on the `App` component in a list-like fashion.


## Set 3 - Axios ( hitting an API ), React Lifecycle Methods

### Question #8

Create an app hitting an API of your choice (swapi.co, birdapi.com, pokeapi, smurfs, marvel api, etc). The API should be hit as soon as the component is finished rendering. The app should set value(s) on state based on results from the API and then show the propertie(s) on state in the DOM.

The `axios` package should be used to hit an API.

## Set 4 - react-router-dom ( Routing ), Axios ( hitting an API )

### Question #9

Create an app that has three routes (using `react-router-dom`):

- Component name: `Home`, Component route: `'/'`
- Component name: `Signup`, Component route: `'/signup'`
- Component name: `details`, Component route: `'/details'`

Each of these components only need a very basic template:

```js
<div>
  <h1>This is the Home/Signup/Details page.</h1>
</div>
```

The `App` component should render a `<nav>` element that provides links to all three routes. The `router` should be rendered underneath the `nav` element.

### Question #10

Create an app that has two routes (using `react-router-dom`):

- Component name: `Products`, Component route: `'/'`
- Component name: `Details`, Component route: `'/details/:id'`

The `App` component should render the `router`. The `Products` component should hit an API of your choice that shows a list of products/info/people/cars. When a user clicks on one of the products/info/people/cars it should route to `Details` component with the `id` as a route parameter. The `Details` component should hit an API of your choice to get more data for a single product/info/person/car.
