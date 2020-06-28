## Intro

First of all, welcome to the our Bootcamp! This is going to be a challenging but exciting journey for getting started in the programming world.

In this guide we will go through all the steps and tools you will need to get ready for the classes. Please, make sure that you have all the tools installed and ready to go before starting the course.

> You might feel a bit overwhelmed sometimes, especially if it is the first time you are hearing about some of these tools and concepts. Please bear with us! :bear: Just try to get the main concept, and contact us with any doubts or problems you encounter during the process (later we will explain how to get in touch with us during the course).

We will provide information about tools for macOS and Windows in this guide. If you use another systems like Linux, and you don't find the download links or enough information, please get in touch with us.

- [MongoDB and Robo3T](#mongodb-and-mongo-hub)
- [Vue](#vue)
- [Docker](#docker)
- [Heroku](#heroku)
- [Checklist](#checklist)

## MongoDB and Robo3T

### MongoDB

On our 5th lesson we will learn how to use [MongoDB](https://www.mongodb.com/), an open-source document database. [Here](https://docs.mongodb.com/manual/installation/) you can find the download links for every platform.

If you are a macOS user, we recommend to install it through Homebrew (check on the Node.js point how to install it if you haven't done so). Once you have Homebrew on your machine, submit on the terminal the following commands (one after the other):
```
brew tap mongodb/brew
```
```
brew install mongodb-community@4.2
```

**Important** :speaker:: Make sure that you have MongoDB properly installed typing on the terminal:
```
mongo --version
```

If you see a message starting with something like _MongoDB shell version v4.0.3_, you are good to go :)

The most important commands are `brew services start mongodb-community@4.2` for connecting to the database, and `brew services stop mongodb-community@4.2` to disconnect from it. If you didn't use homebrew, `mongod` for starting it, and CTRL+C one or two times for stopping it. You can also consider `brew services restart mongodb-community@4.2` if you'd like to restart your connection. But we will see all these commands more in depth during the class. 

_Note: You might need to use `mongodb-community` instead of `mongodb-community@4.2`, depending on which one you used when installing it_.


### Robo3T

We will also use a MongoDB GUI application (an interactive program where we can easily see and manage the items of our database).

They all work very similarly, but in this course we will use Robo3T ([download link](https://robomongo.org/download). Go to right side of the website, click on the button **Download Robo 3T**, and choose your platform).


## Vue

To quickly setup a [Vue](https://vuejs.org/) application we will use [Vue-CLI tool](https://cli.vuejs.org/).

Please follow [this guide](https://cli.vuejs.org/guide/installation.html) for installation.
Run following command to install Vue-CLI globally:
```
npm install -g @vue/cli
```
You can check if you have the right version with this command:
```
vue --version
```
After that go to your project folder and type:
```
vue create frontend
```
For Windows users:
```
winpty vue.cmd create hello-world
```
If for some reasons you are not able to install global packages, please use following commands:
```
npm install @vue/cli -D
npx vue --version
npx vue create frontend
```

You will be prompted to pick a preset.\ Select "Manually select features" and select following options: "Babel", "Router", "Vuex", "Linter / Formatter".\
Use history mode for router? "Y"\
Pick a linter / formatter config: "ESLint with error prevention only"\
Pick additional lint features: "Lint and fix on commit"\
Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? "In dedicated config files"\
Save this as a preset for future projects? "N"

When installation is complete run following commands:
```
cd frontend
npm run serve
npm install -D pug pug-plain-loader
```


## Docker

In our last class we will learn how to deploy our application using [Docker](https://www.docker.com/). Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package.
[Source](https://opensource.com/resources/what-docker).

On [this site](https://www.docker.com/products/docker-desktop) you can find the download links for Mac and Windows and all the steps to follow.

If you don't manage to follow all the steps of that guide, don't worry. We will explore it more deeply in our class. You will just need to download and install Docker on your machine, and
make sure before the class that it is running (On Mac it should appear the little whale on the top menu bar, and if you click on it should indicate that is running. On Windows it will appear on the notifications area, bottom-right of the screen).

**Windows 10 Home Edition users** (or other editions that doesn't support current Docker version): There is a workaround to make it work -> [Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/). You can start from Step 2. If after finishing Step 3 you run `docker run hello-world` and get the response showed on the guide, you should be good to go for the class! Anyhow, if you can come a bit before the class we can check it together.

## Heroku

After we create our containers with docker, we will deploy them to Heroku. When we deploy our apps, they will be accessible from anywhere in the world.

To install Heroku CLI, please follow instructions on [Heroku Dev Center here](https://devcenter.heroku.com/articles/heroku-cli#download-and-install).

Please also create a free Heroku account before coming to the class. Here you can create it: <https://signup.heroku.com/>


----------

#### And that's it! :tada: Please contact us anytime you have doubts or any step of the guide was unclear or didn't work for you. It will also help us make it better for the following students.
#### Enjoy the course! :school_satchel:


## Checklist

#### Have you everything ready to go? :eyes:

- [x] Read the Welcome Guide
- [x] Chrome
- [x] Slack and join #coyotiv-community
- [x] Terminal basic learning
- [x] Git and Github setup
- [x] Node.js
- [x] MongoDB and Robo 3T
- [x] Docker
- [x] Heroku Account & CLI
