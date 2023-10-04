# Car
# Car Seller App

## Description
This is a car selling application built with React. (Add more details about your app here)

## Technologies Used
- React

## Setup
1. Clone the repository
2. Install the dependencies using `npm install` or `yarn install`
3. Start the application locally using `npm start` or `yarn start`

## Available Commands
- `npm start` or `yarn start`: Start the app locally in your development environment, by default it will be in http://localhost:3000.
- `npm test` or `yarn test`: Run tests.

## Development Flow
Here are the steps of the process you need to follow in order to integrate new code or a new feature into the project:
1. Create a local branch to get started using git: `git checkout -b <feature|bug|enhancement|doc>/<issue-tracker-number>-<short-description>`.
2. Develop the new feature while doing atomic commits to your local branch using `git commit`.
3. After you are done, you might want to do a `git rebase develop` in case new changes were integrated, so your new commits are applied on top of that and you make sure everything still works.
4. Before creating the Pull Request, you need to make sure the tests pass (`npm test` or `yarn test`).
5. Now you are ready to create a new Pull Request with your changes, but before, push your changes to origin using `git push -u origin <your-branch-name>`.
6. Your code should be reviewed, you can update the branch with new changes after you get some feedback.
7. After the Pull Request is approved, merge it using the UI on Github (you can also remove the branch directly from the same page, which is also convenient).
8. Your code will land to the develop branch (and eventually deployed into the staging environment).

## CSS Preprocessor
This project implements SASS via node-sass, as per the suggestion of Create React App's documentation. The styles for each component are therefore located in their corresponding `<component_name>.scss` file. There's also a utility folder under src/styles. The folder contains some common variables, mixins and other stuff that is meant to be reused from other SASS files. You import these styles from another .scss file by doing:

