# SWE-432 HW-4 Starter Application

## Submission Information

### Student Information

*Please fill in this information before submission*

* **Student Name:*jaime pena* 
* **Student G-Number:*01300925* 
* **Heroku Deployment URL:https://jaime-pena-swe432-hw4.herokuapp.com/**

### Documentation of your Web App and React Components

*Here please describe your (at least) 5 different React components as well as the overall purpose of your web application. We provide an example below of what we expect this documentation to look like.*

**General App Description:** This web application provides information about cities loaded from a centralized database at www.citiesinfo.org. This app can help people find reference information about various city attributes such as population, capitals, and other demographic information.



* **React Component 1:** component that asks the user for a the name of the workout.
* *Functionality:*  shows user the name of the website
* *Interactivity:* The user can enter input and when focus is given to the box the backgroud of the box turns blue


  * **React Component 2:** Consists of a button that counts and keeps track of the number of sets  
  * *Functionality:* Displays a button that when clicked clears the section for the reps and weight and then an event is sent to a parent component to store in a list what was inputed durign that particular set
  * *Interactivity:* The user can click on an the button and when they hover over it, the button expands

  * **React Component 3:** displays the logo for the website
  * *Functionality:* it resets the table
  * *Interactivity:* if user clicks on this logo the page is reseted.


  * **React Component 4:** records the number of reps and weight that was used during that set
  * *Functionality:* displays two inpput boxes that ask the user for the number of reps that were done and the weight that was used during that set
  * *Interactivity:* boxes turn blue with focus and input disappears after reciving the enter key

  * **React Component 5:** List all info for each set
  * *Functionality:* Displays a list of sets for a particular workout
  * *Interactivity:* this is where all components are put together with a button thatis clicked when the workout has been terminated. This event clears the section for that work out and returns a list with the number of reps, weight, and set number for each workout that was used

## Project Overview

This repo contains a barebones React app with a single component. You will use this as the "base" version of your Interactive Front-end application for HW Assignment #4. You will simply create a copy of this repo through GitHub classroom and then work in that repo. 

## Homework Assignment 3 Detailed Instructions

You can find the deatiled instructions for HW Assignment #4 on the [course webpage](https://kpmoran.cs.gmu.edu/swe-432-f22/hw4-tutorial/). Please read these carefully before getting started.

## Running this Project Locally

Make sure you have [Node.js](http://nodejs.org/) and (optionally) the [Heroku CLI](https://cli.heroku.com/) installed. You only need the Heroku CLI installed if you plan to deploy the project from the CLI instead of the Heroku web interface. See the [HW Assignment #4 instructions](https://kpmoran.cs.gmu.edu/swe-432-f22/hw4-tutorial/) for more details.

*Note the following commands assume a Unix-based enviornment. If you are on windows, you may need to use something such as Windows Subsystem for Linux (https://docs.microsoft.com/en-us/windows/wsl/about).*

```sh
$ git clone <repo-name>
$ cd <repo-name>
$ npm install
$ npm start
```

After executing these commands, your React frontend should now be running on [localhost:3000](http://localhost:3000/). You can visit this page in your web browser to view your front-end user interface.

## Deploying to Heroku

Check out [our instructions](https://kpmoran.cs.gmu.edu/swe-432-f22/hw4-tutorial/) for deploying your application to Heroku. You can use the button below for quick access to your Heroku account.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Testing with Continuous Integration

**Note that you are not required to test your project with Jest for HW3, however, we have enabled this functionality in case you would like to use it. If you would like to remove the tests, you can remove the `.github` directory from the repo.**

Currently, this repo is set up to run the Jest tests in the `App.test.js` file upon each commit to the `main` branch of the repository. If any of the tests fail, the CI process will fail and this will be indicated with red "X" on the main page of your repo, and GitHub will likely also send you a notification email that your automated tests have failed.

Currently, the tests are configured to run by getting deployed to a remote virtual server with an Ubuntu operating system, where the `npm install` and `npm test` commands are executed.

Note that we have included the [`jest-dom`](https://testing-library.com/docs/ecosystem-jest-dom/) library for your tests. This allows you to check DOM elements in your tests.

You can find the [GitHub Actions](https://github.com/features/actions) script for this CI job [here](.github/workflows/ci.yml) if you want to learn more.

## Additional Resources

For more information about using Node.js on Heroku, see these Heroku Dev Center articles:

- [React Tutorial](https://reactjs.org/tutorial/tutorial.html)
- [Express Documentation](https://expressjs.com/en/5x/api.html)
- [Supertest Documentation](https://www.npmjs.com/package/supertest)
- [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
