### Example:

This repo houses the deployment infrastructure we use to release our code.

Because this is long you may navigate this guide using the table of contents:

#### Table Of Contents:

- [Example Deployment Repository:](#example-deployment-repository)
  - [Table Of Contents:](#table-of-contents)
  - [Intro:](#intro)
  - [How To Get Started:](#how-to-get-started)
  - [Services:](#services)
    - [Example App:](#example-app)
    - [Example JS:](#example-js)
  - [Bugs:](#bugs)

#### [Intro](#table-of-contents):

Example is a {insert a statement about what the project is. This helps your team and anyone else reading quickly discover what they are looking at.}

Give an example that is easy to understand.

{You often go out for drinks after work with your colleagues. Sometimes you have had too much to drink and need to easily get home. Uber makes that possible.} 

You can think of Example as the same thing, We make it possible to {1 thing that is easy to do with Example and was hard to do before}

{Add details about what Example does. Integrations, features, etc}

{What is the benefit of using Example.}

{Why did you write/create/build Example. Be as detailed here as possible. This helps others connect with what you're building.}

{What did you want that you couldn't get which led you to create example.}

{Define some beliefs. Like, convention over configuration. Services for everything. Mono-repo. Whatever describes your culture, decision making, etc.}


***{Set a success metric. If we do our job well, drunk driving will go down}***

The success metric helps those working with you understand what success is, and evaluate if the project is close.

#### [How To Get Started](#table-of-contents):

This section should contain how someone can get started using/running/compiling the code you provided. 

Start as basic as needed. If you are a company you might not need to tell someone they need a Github account. If you are an entry level computer science class you probably do!

List what people will need installed on their machine (and include a link on directions to do so: 


You will need Terraform installed on your machine. You can find a link on how to do that [here](https://learn.hashicorp.com/terraform/getting-started/install.html).

Once you have completed that, ensure you have the AWS CLI installed and you have AWS credentials.

{Define what happens once set up is complete. At this stage, you will have full access and ability to release code to customers.}


#### [Services](#table-of-contents):

This repo contains the Example services. If you add a new service please update here.

We currently have:

* [Example App](#example-app)
* [Example JS](#example-js)

##### [Example App](#services):

You should define the example app. An example is provided below.

Example App is our UI. The UI uses:

* VueJS
* Vuex
* Webpacker
* NodeJS
* MongoDB
* Docker

{Provide a note about if you don't know how to use these, ask. This makes a project more approachable and helps younger/less experienced developers have the confidence to ask.}

{Define how they can run a local version of the app. Include the actual command. Do not say things like run node. Write out something like: 
```
nodemon server.js
```

{Define where they can go to view the local version. If this is an API you might want to use curl. If it is a UI, you can go to localhost:3000}

{Define how they can make changes the easiest. If this means running webpacker, describe including the full command how someone can do that. If this means standing up another service describe and link to that service, with a similar readme to this one. }


#### [Example JS](#table-of-contents):

You should define the example service. An example is provided below.

Example JS is our {javascript snippet} that does {x} for cusotmers.

{Define versions. Dev, QA, Staging, Prod, etc. Make it clear where they should get familiar with the code and test changes vs where they should be careful.}

We have multiple versions:

* Dev
  - Use this as a testing ground. It is embedded on sites we own and operate.
  - https://dev.example.com
* Prod
  - This is our production service. Use with precaution.
  - https://cdn.example.com


{Define where the actual service is located. The script is housed in /src/example.js}

{Define how they can build/run locally}

To build locally you should run:

```
npm run local
```


#### [Bugs](#table-of-contents):

{Define any gotcha's or bugs in the code as is. If it took you 3 hours to figure out why something worked/didn't work, please include that here. An example is below}

* Node must be version <11.12.0 

* ENV variables must be set before running code. 
