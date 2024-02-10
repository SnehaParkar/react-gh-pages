# Deploying a React App* to GitHub Pages


# Introduction
In this tutorial, we will learn how to create a React app and deploy it to GitHub Pages. follow the below steps

To create the React app, I'll be using create-react-app, which is a tool people can use to create a React app from scratch. To deploy the React app, I'll be using gh-pages, which is an npm package people can use to deploy things to GitHub Pages, a free web hosting service provided by GitHub.


# Tutorial

## Prerequisites

1. Node and NPM are installed
2. Git installed
3. github account

## Steps
### 1. Create an empty repository on GitHub

1. Sign into your GitHub account.
2. Visit the Create a new repository form.
3. Fill in the form as follows:
   I'll enter: react-gh-pages
   I'll choose: Public
4. Submit the form.

At this point, your GitHub account contains an empty repository, having the name and privacy type that you specified.
### 2. Getting Started with Create React App

  This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### 2. Create a React app

1. Create a React app named `my-app`:

    > In case you want to use a different name from `my-app` (e.g. `web-ui`), you can accomplish that by replacing all occurrences of `my-app` in this tutorial, with that other name (i.e. `my-app` --> `web-ui`).
  
    ```shell
    $ npx create-react-app my-app
    ```

    > That command will create a React app written in JavaScript. To create one written in [TypeScript](https://create-react-app.dev/docs/adding-typescript/#installation), you can issue this command instead:
    > ```shell
    > $ npx create-react-app my-app --template typescript
    > ```

    That command will create a new folder named `my-app`, which will contain the source code of a React app.

    > In addition to containing the source code of the React app, that folder is also a Git repository. That characteristic of the folder will come into play in Step 6.
    2. Enter the newly-created folder:
  
    ```shell
    $ cd my-app
    ```

At this point, there is a React app on your computer and you are in the folder that contains its source code. All of the remaining commands shown in this tutorial can be run from that folder.
