# Week 7 Assignment

Your assignment for this week is to think of a final project idea and create a plan for the project.

## Final Project Requirements

* The project must be a React application, bootstrapped with `create-react-app`
* Your app must be created and visible in a Github repo under your Github account
* Your app must be your own work. You may have a partner if you'd like, but be aware that you'll need to come up with a strategy for working together. Most developers on small projects create branches for new features/fixes, then merge them back into the `main` branch. Merge conflicts can arise, and you'll need to know how to resolve them.
  * The simplest and most straightforward workflow for each team member:
    ```bash
    # create a branch off of main
    git checkout main
    git branch -b feat/new-feature-name

    # commit code to this branch
    git add .
    git commit -m 'more code'

    # periodically push to Github
    git push
    ```
  * Create pull requests on Github into the `main` branch when ready to merge code. It's recommended that you merge only working and/or tested code.
* Your app should be deployed onto a web server and publicly accessible (unless you decide to use React Native. In that case, it's recommended you use [Expo](https://expo.io/) to share the project).
* Your app should be polished. Some recommendations for this requirement:
  * Remove `console.log` statements once you're finished with development
  * Utilize CSS and images to make your app look great
  * Check for any React errors in the console
  * Perform some basic user testing. Have other people use your app and receive feedback on usability
  * Keep your feature set small, so you'll have time to polish the app
* If you're feeling adventurous, you can also use React to build mobile apps using the [React Native](https://reactnative.dev/) framework. Usage is allowed for this project, **but** note that it will involve additional learning and research. Proceed at your own risk.

Other than the above requirements, you're encouraged to be creative and create something you're proud of. It can be as simple or as complex as you want, and it should be high quality.

## Assignment Requirements

Above are the requirements for the project. For this week however, you'll need to create a plan for your project. More details are to come, but you'll need to create a pull request with the following:

* The name of your project
// Weather app

* An elevator pitch (a paragraph about what your project does). Be sure to address:
// My final project will be a weather app. It will have a search bar which a user can use to search the weather for a particular
// city. The app will then show the weather in the specified city for the next 7 days. The user can click on any of these 7 days for a more /// detailed information on that day. I am also planning to create a feature where users can save their favorite cities. This weather app is /// targeted to everyone. It will provide the user with valuable weather information in the end.

* [Wireframes](https://en.wikipedia.org/wiki/Website_wireframe) to help visualize what your project will look like
// A wireframe is provided in wireframe.png

* A list of dependencies you'll be using for your project (npm modules, APIs, Firebase, etc.)
// React
// OpenWeather API (https://openweathermap.org/api)
// Firestore
// Firebase Authentication
// React-Router
// Prop-Types

* A list of tasks that need to be completed for your project
// Setup create-react-app
// Create a "card component" for basic weather info
// Create component for detailed weather info
// Setup router
// Call the API to retrieve weather data
// Render the components accordingly

* A plan for the next 3 weeks and what you plan to accomplish each week
// Week 1:
// Finalize project idea
// Imagine how my project will look and function in the end
// Create the react app and start working

// Week 2:
// Continue working! This is when most of the work will be done!

// Week 3:
// Finish up
// Testing

## Recommendations

* Keep the scope of your project small. A small, completed project is much better than a large, incomplete project. You can create a list of "nice to have" features that you can work on if you have time (similar to how our assignments have a main list of requirements and "bonus" items).
* Ensure you have plenty of buffer time in your schedule. Life events pop up, and tasks can take longer than initially estimated.

## Submitting your Project Idea

1. Fork this repository
2. Add your project name, elevator pitch, wireframes, dependencies, task list, and plan to the Github repo (you can add a markdown file + images or links to images)
3. Create a pull request
