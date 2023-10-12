Never Give up ➜ Keep Going

# Chai Aur React

<div><i>Sarfaraz Running Notes</i></div>

## Content:

###### Reactjs Road Map

###### Create React Projects

###### Flow & Strcuture

###### Create Own Library & JSX

###### Why Hooks

###### Virtual DOM, Fibre, Reconcillation

###### Tailwind & Props

###### Counter Interview Question

###### bgChanger Project

###### useEffect, useRef & useCallback using 1 Project

###### Custom hooks - Currency Project

###### Context API with 2 projects

###### Context API with with local storage

###### Redux Toolkit

<hr/>

## Reactjs Road Map

- Details

  #### Why to learn React

  - It is easy to manage and build complex frontend

  #### When should we learn React?

  - After mastering javascript ➜ when you think you can do any project with javascript without reactjs.

  #### Why react is created?

  1.  React library work very consistently when there are lot of change in single event
  2.  In React state name is given for variables

  #### Who should not learn React?

  - Who don't know how javascript work internally, how execution context works

  #### Ways to learn React?

  - Approach 1) By going deep in subject ➜ than creating the project
  - Approach 2) By creating project ➜ then going deep
  - Here, we will create the project then will deep

  #### Is React a library or Framework?

  - Framework is like a miltary, here rules are given more importance, data will store like that
  - Library is like a cool dude, Sample example: we can put cap at any way, it look cool dude, So react is a library which gives freedom to do the things differently.

  #### What do we need to learn in Reactjs?

  1. State & UI Manipulation
  2. JSX: Writing html in JS
  3. Reusing component easier in Reactjs
  4. How to propgate the changes (Hooks) - Need to learn the concept of hooks

  #### Additional Addons to Reactjs?

  1. **Router:** Used when we need to move from one page to another
  2. **State management:** Redux or Context API is used to manage the state, as it is difficult to manage the changes in variables.
  3. **Class based component:** To understand the legacy components.
  4. **BASS Apps:** To work on Backend as service, Example: firebase, Appwrite etc.

  #### After Reactjs?

  - Reactjs is not a complete solution ni must case like no SEO, No routing
  - So we can opt for Nextjs, Gatsby, Remix.

## Create React Projects

- Tools: VS Code, Nodejs - gives the environment,
- Open the terminal ➜ and check node/ -v
- React documentation: react.dev

  ### Run the github commands

  - git init
  - git add README.md
  - git commit -m "first commit"
  - git branch -M main
  - git remote add origin 'url'
  - git push -u origin main

- It is always advisable to learn from documentation, so that any update happen, we can learn quickly.
- We can create react application using ** vite or Versal ** these are bundler which budle everything and gives 1 file.
- **npm**: Node packae manager, Which allows to install the packages in node

  ### Create Project using react

  - **npx**: Node package executor, which help to create the new project in react.
  - npx create-react-app 01basicreact ➜ Here, 'create-react-app' is the utility or software and '01basicreact' is the application name. ➜ This is slow way of creating the application.
  - There are other ways to create the react application fasster like vite or versal.
  - Go to the project and run 'npm start'.

  ### **package.json**: 1st entry point,

  - Here, it will give the list of dependencies list
  - web-vitals: We can track the performance of the application.
    #### scripts:
    - start: to run the project in dev environment.
    - build: when project goes in production, it behaves differently, so we generate files in html, css, js using build process.
    - test: To run the test case
    - eject: eject from react application usage. that react work is over, will use other library.
  - Linting: to show the error or warning messages
  - browserlist: on which browser i ll work.

- To run the project ➜ use 'npm start', here we can say run start or simply start.
- **npm run build**: It created the build folder ➜ which has all the static files available. ➜ build folder only serves to the user not src.
- As create-react-app project is taking too much time and bucky, we will be using vite to create the react application.

  ### Creating react application using vite

  - npm create vite@latest
  - y
  - Give project name
  - select 'React'
  - select 'javaScript'
  - Now project is created, check the package.json
  - cd 01vitereact --> npm install --> npm run dev --> open the url localhost:5173
  - We will be in mostly src folder


## Flow & Strcuture

- In package-lock.json, all the stable version is locked down.
- Eevrything mostly work is done in src folder or public folder
- **index.html**: This is the main file which will load on the page.
- noscript says if the javascript is disabled in any browser kindly enable it.
  #### **index.js**:
  - React uses its own DOM, DOM is a tree structure of elements which we call it as vitrual DOM and compare with actual DOM and give the differnce on UI.
  - Here it create and search the root element id --> says render the html from App component.
  - JSX is similar to html custom tags.
- App is simply a function which return a html, export it --> render the html
- react-script is responsible for loading index.js into index.html in create-react-app application creation but for vite, the script is dorectly loaded in index.html file.
- Either vite or create-react-app both are working same, just vite is light weight
- lets create a file chai.js in src folder.
- When we are creating any application using vite, it is advisable to use jsx extension file and Component name should starts with Uppercase letter.
- React components are simply pure javascript functions.
- JSX should be wrapped in sinlge element only, as JSX will return only 1 element.
