# Lennd - Front-End Developer Exercise

## Instructions

You are building a list of event team members using React.js.

![alt text](https://raw.githubusercontent.com/lennd/front-end-developer-exercise/master/excercise-design.png "Exercise")

#### Details
- Use the JPG or Sketch file contained in this repository as your visual guide. If you'd like, you can download a trial of Sketch here: https://www.sketchapp.com/
- You must consume this endpoint (http://jsonplaceholder.typicode.com/users) to get the users for the list. How you consume the endpoint is up to you.
- You can use static CSS, setup a CSS precompiler + watching, or use inline styling
- You should be able to filter the list by typing into the filter text input
- Clicking on a row should expand it to reveal the user's address -- only one row should be able to be expanded at a time
- You should demonstrate knowledge on how to construct and re-use components
- Use ES6/7
- Add a "loading" indicator for when the users are being fetched

#### Bonus points
- Write tests for your components using a testing library of your choice
- Demonstrate knowledge of pure functions / components

#### For fun / if you want to get crazy (encouraged)
- Find a way to incorporate Redux (We use it heavily)
- Add animation to the expanding rows
- Output some location-relative information using the latitude / longitude returned by the API endpoint for each user
- Use a Gravatar for displaying a user's avatar based on the user's email

#### To submit
- Send Josh (josh@lennd.com) an email with a link to your repository

#### Notes
- The design shows just a sampling of users. You should display all of the users that the endpoint returns.
- For the icons, use FontAwesome (https://fortawesome.github.io/Font-Awesome/icons/). The CSS has already been included in the project.

#### Resources
New to React.js? Check out these resources:
- http://courses.reactjsprogram.com/courses/reactjsfundamentals
- http://tylermcginnis.com/an-introduction-to-life-cycle-events-in-react-js/
- http://tylermcginnis.com/building-user-interfaces-with-pure-functions-and-function-composition-in-react-js/
- https://camjackson.net/post/9-things-every-reactjs-beginner-should-know

#### Questions / problems / comments?
Contact Josh - josh@lennd.com

---

## How to get up and running...

#### Step 1 - Install Webpack
```
> $ npm install webpack-dev-server webpack -g
```

#### Step 2 - Clone this repository and install modules
In the directory where you'd like this repository to live, run the following commands:

```
> $ git clone git@github.com:lennd/front-end-developer-exercise.git
> $ cd front-end-developer-exercise
> $ npm install
```

#### Step 3 - Run!
Run the development server:
```
> $ npm start
```

#### Step 3 - View in browser
Open up your browser to http://localhost:5000/ and voila!

#### Notes
- The static CSS files you need are in `public/css`.
- The React files you need are in `src`
- When you edit CSS files, you will have to refresh the browser
- When you edit React files, the browser will automatically reflect your changes
