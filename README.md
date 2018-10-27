# Vue Overview


# Purpose

The purpose of this is to explain vue in simple and easy to understand terms.
Some objective we will cover are:

-   Why Vue.js is in many cases the better tool for for the job.
-   Quickly creating a project using the vue-cli.
-   Creating new components
-   Passing props from one component to another
-   Using Vue directives
-   Using Vue Events

We may lightly and indirectly touch on:

-   Webpack
-   Bootstrap
-   ES6


## Requirements

-   Node v8.12+
-   NPM v6.4.1+

## Necessary Skills

-   Basic concept of front end frameworks
-   Javascript
-   Basic knowledge of ES^

## What is Vue?

Vue is a fast, lightweight, front-end Javascript based framework.

Every Vue app is an instance of of the ViewModel.  In plain english it is an
object that syncs that data with what we see in the DOM. Doing this, like many
other framework allows for a faster web experience.

Vue is unique in that is performs better than many other frameworks including
React and angular. [Metrics](https://stefankrause.net/js-frameworks-benchmark8/table.html)

It does not require a domain speific language, such as JSX.

HTML rendered in templates makes for easy conversion of large scale apps.

Assurances to be non-breaking. [Angular backwards compadiblity](https://www.codementor.io/codementorteam/migrating-from-angular-1-x-to-angular-2-upgrade-strategies-a3fgzrhxo)


# Getting Started

First we need the handy vue-cli tool which will quickly get us a full vue 3 app.

Let's install this with the command

```bash
npm install -g @vue/cli
```

Now that we've installed our command line tool let's scaffold our first Vue app.

```bash
vue create my-app
```

For now we don't need to worry about any config options and can just click enter
and accept the defaults.

Now let's take a look at what got scaffolded and run `npm run serve` to take
a look at our app.

## Clear and setup

First we're going to remove some of this starter code. So clear out everything
from `HelloWorld.vue`, the CSS inside `App.vue`, as well as everything inside
the `<div>` tags.
