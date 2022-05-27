# Frontend Roadmap 2022

This document  serves as a walkthrough for newcomers who want to prosper their career in frontend development.

## Effective ways of learning
- Focus on fundamentals
- Learn by doing. Practice the code with examples
- Learn to ask for help
- Take a break from code debugging when necessary
- Do More Than Just Read Sample Code
- Check out useful resources


## Opinionated
In recent years, [React.js](https://reactjs.org/) is getting a good impression. If we look at the [StackOverflow survey of 2021](https://insights.stackoverflow.com/survey/2021?_ga=2.143519986.693422786.1653535525-940540015.1653535525#section-most-popular-technologies-web-frameworks), React.js is the most commonly used web framework.
This roadmap has used React as an example, however, one can pick any other framework such as [Vue.js](https://vuejs.org/) or [Angular](https://angular.io/start). These three frameworks three major frameworks are similar in essence and have great demand. 


## Roadmap
The decisive frontend journey is shown below.

![Frontend Roadmap](./files/frontend.jpg)

Frontend development is the practice of producing a website or Web Application using HTML, JS, and CSS that can be seen and interacted with by the user. With the everchanging tools and technologies used for the development, one has to keep updated to cope with the changes.

## Pre-requisites

Most things are done on the internet, so its good to have some understanding of the inner working of the Internet, which are categorized as below:
   
   * Internet 
      - Internet is a global network of computers connected together that communicates through a standard set of protocols.
      
   * Domain Name and DNS 
      - Domain Name is a unique name, an easy-to-remember address used to access websites such as 'google.com' with the help of DNS. DNS maps the IP address with the domain name and serves the resources.
   
   * Hosting
     - Hosting allows you to publish internet files so that everybody on the internet can access them.
 
   * HTTP Basics
     - HTTP  uses `TCP/IP` a communication protocol that defined how the content should be transmitted over the internet.
     
   * Browsers and their working mechanisms
     -  Browsers are software application  that enables a user to access and display web pages or other online content through its graphical      user interface.
     
## Foundation Layer
Getting a strong  grasp of the fundamentals is beneficial for long term  success. It will allow grasping complex logic further along. HTML , CSS, and JavaScript are the core foundations in frontend development which are described  below.
1. HTML
   - HTML stands for HyperText Markup Language and  is used to give structure to the webpage. It can be styled using CSS and make interactive using Javascript. 

    * HTML Semantics elements clearly describe its meaning to both the browser and developer. `<form>`, `<table>` are some of its examples.
    * Validations are performed to make sure that all required for filling out in the correct format before submitting the data to the server. This whole process
    is also known as client-side validation.
2. CSS

   * CSS stands for Cascading Style Sheets and is used to style websites or web applications.
   * Float, grid, flexbox, positioning, display, and box model are some of the important topics that are used for making layouts. 
   * CSS Cascade is the way our browsers resolve competing CSS declarations.
   * CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax. `SASS`, `LESS`, `Stylus` are some of the examples of it.
   * CSS is notoriously difficult to manage in large, complex, rapidly-iterated systems. `BEM`, `OOCSS`, `SMACSS` are some of the ways of writing CSS that allows for writing more maintainable CSS.
   * CSS framework is a pre-prepared library that is meant to allow for easier, more standards-compliant styling of web pages using the Cascading Style Sheets language. `Tailwind CSS`, `Chakra UI`, `Material UI` and `Material UI` are some of the examples of it.
   * Bootstrap is the most popular CSS framework for developing responsive and mobile-first websites. It contains HTML, CSS, and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.
  
   
4. Javascript

   * It adds interactivity to a webpage. `Sliders`, `Cick interactions`, `popups` are some of its common implmentation seen on websites.
   * Document Object Model (DOM)  is a programming interface for web documents that allows changing the document structure, style, and content. It views document as tree of nodes and objects. 
   * Closure is a function that references variables in the outer scope from its inner scope. The closure preserves the outer scope inside its inner scope.
   * ES6 brings new syntax and new awesome features to make your code more modern and more readable. It allows you to write less code and do more.
   * Fetch API provides a JavaScript interface for accessing and manipulating parts of the HTTP pipeline, such as requests and responses. 
   * Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables, or classes to the top of their scope, prior to execution of the code. It allows `functions` to be safely used in code before they are declared.
   
   
## Bonus Section
   * Version Control and Repository Hosting
     - It allows is a collaborative tool that allows tracking changes to the codebase/files over time. Backtracking is also possible here.
     - `Github`, `GitLab` and `BitBucket` are some of the examples of repository hosting services providers.
   
   
## Node, TS and the ecosystem

1. NodeJS
   - Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine designed to build scalable node applications.
   - `npm` is a package manager for the JavaScript programming language maintained by npm, Inc. It is the default package manager for Node.js.
   - `yarn` is a software packaging system developed in 2016 by Facebook for Node.js JavaScript runtime environment that provides speed, consistency, stability, and security as an alternative to npm (package manager)
   - Task Runner are tools to simplify your tedious work on development, like automating sass/scss compiler, bundling assets, linting source code, hot reloading local server. 
   - npm scripts are the entries in the scripts field of the `package.json` file where we specify various commands and scripts that we want to expose.
   - Module bundler is a tool that takes pieces of JavaScript and their dependencies and bundles them into a single file, usually for use in the browser. `webpack`, `esbuild`, `parcel` are some examples of it.
   - Webpack is a module bundler capable of transforming, bundling, or packaging just about any resource or asset.
   - Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.
   - A linter is a tool used to analyze code and discover bugs, syntax errors, stylistic inconsistencies, and suspicious constructs.  `ESLint`, `JSLint`, and `JSHint` are some of the popular javascript linter.
   - Prettier is an opinionated code formatter with support for JavaScript, HTML, CSS, and more.
   - With ES6 modules one can easily reuse, maintain, separate, and encapsulate components from being changed by external behavior.
  
 2. Typescript
    - TypeScript is a strongly typed programming language that builds on JavaScript, giving better tooling at any scale. 
    - The `tsc` command envokes the TypeScript compiler. When no command-line options are present, this command looks for the tsconfig.json file.
    - TypeScript Generics is a tool that provides a way to create reusable components. It creates a component that can work with a variety of data types rather than a single data type.
    - The type declarations  reside under @typings for third party javascript libraries.
  
  3. Functional Programming in JS/TS
     - Functional programming (often abbreviated FP) is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions.
     - Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.
     - A pure function works as an independent function that gives the same output for the same inputs. 
     - Currying is a process in functional programming in which we can transform a function with multiple arguments into a sequence of nesting functions.
     - Composition is about creating small functions and creating bigger and more complete functions with them.
     - Memoization is an optimization technique used primarily to speed up computer programs by storing the results of expensive function calls and returning the cached result when the same inputs occur again.
     - `.map()` is  when we want to transform elements in an array, whereas `.reduce()` is used when you want to derive a single value from multiple elements in an array.
     - `.filter()` selects a subset of multiple elements from an array and `.forEach()` is used to execute a function for each individual element in an array.
 

## Understanding React 
 - It is one of the most popular javascript libraries for building user interfaces that can render on servers using Node and power mobile apps using React.
 - Next.js is an open-source development framework built on top of Node.js enabling React based web application
   functionalities such as server-side rendering and generating static websites.
 - Redux is a light weighted State Management Tool that helps the components in our React App to communicate with each other. 
 - Flux is an architectural pattern proposed by Facebook for building SPAs. It suggests splitting the application into `Stores`, `Dispatcher`, `Views` and `Action / Action Creators` parts.
 - Create React App is a comfortable environment for learning React, and is the best way to start building a new single-page application in React. 
 - React Router is a great way to build single-page applications as it prevents a page refresh every time a link is clicked.

 
 
 ## Testing 
  - Before delivering the application to the users, one needs to make sure that the application meets the requirements it was designed for, and that it doesn't do any weird, unintended things (called 'bugs'). In order to accomplish this, we test applications.
  - Jest is a delightful JavaScript Testing Framework with a focus on simplicity and works with projects 
    using: Babel, TypeScript, Node, React, Angular, Vue and more!.
  - React Testing Library (RTL) is a library for testing React applications. Its primary guiding principle is: The more your tests resemble
    the way your software is used, the more confidence they can give you.
  - Cypress is a javascript based end-to-end testing library running on and in the browser, making asynchronous testing simple and convenient.
  - Enzyme is a JavaScript Testing utility for React that makes it easier to test your React Components' output.
   
 ## Additional Concepts
  - MobX is a simple, scalable, boilerplate-free state management solution. It allows you to manage the application state outside of any UI framework, making the code decoupled, portable, and, above all, easy to test.
 - GraphQL is designed to make APIs fast, flexible, and developer-friendly. It allows developers to construct requests that pull data from multiple data sources in a single API call.
 - Apollo is a platform for building a unified graph, a communication layer that helps you manage the flow of data between your application clients (such as web and native apps) and your back-end services.
 - React Native is a popular JavaScript-based mobile app framework that allows you to build natively-rendered mobile apps for iOS and Android using the same codebase.
 - Electron allows you to build cross-platform desktop applications with HTML, CSS, and Javascript/Typescript.  It is a "Browser" like application that uses Chromium and Node.js, and is compatible with Mac, Windows, and Linux.
 - Next.js is an open-source framework designed to work with React and provides functionalities such as server-side rendering and generating static websites.
 - Gatsby is an open-source framework that combines functionality from React, GraphQL, and Webpack into a single tool for building static websites and apps.
 - Bulma is a free, open source framework that provides ready-to-use frontend components that you can easily combine to build responsive web interfaces.
 - Web accessibility, or eAccessibility, is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with physical disabilities, situational disabilities, and socio-economic restrictions on bandwidth and speed.
 - Progressive Web Apps (PWAs) are web apps that use service workers, manifests, and other web-platform features in combination with progressive enhancement to give users an experience on par with native apps.
 - Web Storage API provides mechanisms by which browsers can store key/value pairs, in a much more intuitive fashion than using cookies.
 
 ## Video Courses
1. [Frontend Masters](https://frontendmasters.com/courses/) 
2. [egghead](https://egghead.io/)
    * [getting-started-with-redux](https://egghead.io/courses/getting-started-with-redux)

    * [building-react-applications-with-idiomatic-redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)

    * [manage-application-state-with-mobx-state-tree](https://egghead.io/courses/manage-application-state-with-mobx-state-tree)
3. [JavaScript 30 challenge](https://javascript30.com/)
4. [Learn Git in 20 Minutes](https://www.youtube.com/watch?v=SWYqp7iY_Tc&ab_channel=TraversyMedia)
5. [CSS Masterclass - Tutorial & Course for Beginners](https://www.youtube.com/watch?v=FqmB-Zj2-PA&ab_channel=ChrisCourses)
6. [HTML Tutorial for Beginners: HTML Crash Course](https://www.youtube.com/watch?v=qz0aGYrrlhU&ab_channel=ProgrammingwithMosh)

4. Udacity
	* Good JS courses
		* [Object Oriented Programming in JS](https://www.udacity.com/course/object-oriented-javascript--ud711)
		* [JS and DOM](https://www.udacity.com/course/javascript-and-the-dom--ud117)
	* [Course on Responsive Design \[CSS\]](https://www.udacity.com/course/responsive-web-design-fundamentals--ud893)
	* [Course on a11y by Google is amazing](https://www.udacity.com/course/web-accessibility--ud891)

## Documentation and Blogs
1. [React Docs](https://reactjs.org/docs/getting-started.html)
1. [HTML Spec](https://html.spec.whatwg.org/dev/) has a dev only version for reading
3. [Webpack getting started tutorial](https://webpack.js.org/guides/getting-started/)
4. [JavaScript Garden for understanding JS quirks](https://bonsaiden.github.io/JavaScript-Garden/)
5. [An introduction to the Flux architectural pattern](https://www.freecodecamp.org/news/an-introduction-to-the-flux-architectural-pattern-674ea74775c9/)


## Youtube Channels
1. [netninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg)
1. [Brad Traversy](https://www.youtube.com/user/TechGuyWeb)
2. [Kent C. Dodds](https://www.youtube.com/c/KentCDodds-vids)

## Interactive CLI based 
1. [nodeschool.io](https://nodeschool.io/)
1. [freecodecamp](https://www.freecodecamp.org/)

## Books

1. [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)
1. [Eloquent JS](https://eloquentjavascript.net/)
1. [JS info](https://javascript.info/)
2. [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X)

## Updating this doc
Feel free to comment with links to free courses and topics that should be added here.
