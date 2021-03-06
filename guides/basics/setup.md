# Setting up

In this section we will go over the required tools and preliminary knowledge for best learning Feathers.

## Prerequisites

Feathers and most plug-ins work on [NodeJS](https://nodejs.org/en/) v6.0.0 and up. For the guides we will use syntax that only works with Node v8.0.0 and later. On MacOS and other Unix systems the [Node Version Manager](https://github.com/creationix/nvm) is a good way to quickly install the latest version of NodeJS and keep up it up to date.

After successful installation, the `node` and `npm` commands should be available on the terminal and show something similar when running the following commands:

```
$ node --version
v8.5.0
```

```
$ npm --version
5.5.1
```

Feathers does work in the browser and supports IE 10 and up. The examples used in this guide will however only work in the most recent versions of Chrome, Firefox, Safari and Edge.

## What you should know

Readers should have reasonable JavaScript experience using [ES6](http://es6-features.org/) and some experience with NodeJS and the JavaScript features it supports like the [module system](https://nodejs.org/api/modules.html). Some familiarity with HTTP and [REST APIs](https://en.wikipedia.org/wiki/Representational_state_transfer) as well as websockets is also helpful.

The guide examples use [async/await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function). Familiarity with [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) and `async/await` (and how they interact) is highly recommended. For a good introduction to JavaScript promises see [promisejs.org](https://www.promisejs.org/) and then follow up with `async/await` in [this blog post](https://blog.risingstack.com/mastering-async-await-in-nodejs/).

Feathers works standalone but also provides [an integration](../../api/express.md) with [Express](http://expressjs.com/). This guide does not require any in-depth knowledge of Express but some experience with Express will be helpful in the future (see the [Express guide](http://expressjs.com/en/guide/routing.html) to get started).

## What we won't cover

Although Feathers works with many databases, this guide will only use examples of standalone database adapters so there is no need to run a database server.

Authentication will be shown later in the [chat application guide](../chat/readme.md).

All examples will reside within a single file. The Feathers generator (CLI) will create a recommended structure for a Feathers application. You can see what it does to structure an application in the [Generator guide](./generator.md) and how to use it in the [chat application guide](../chat/readme.md).

## What's next?

All set up and good to go? Let's [install Feathers and create our first app](./starting.md).
