# nuxt-feathers-boilerplate

A full-stack boilerplate leveraging Nuxt 2.x and Feathers 3.x.

It's still **work-in-progress**. Use it at your own risk.

## Features

* Hot-reloading on back-end and front-end
* REST and SocketIO pre-installed

### Roadmap

* Linting
* Testing
* Integration with `feathers-vuex` (once it supports Feathers 3.x and Vuex 3.x)

## Useful commands

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# run @featherjs/cli commands
$ yarn server generate service      # generate new Feathers service
$ yarn server generate hook         # generate new Feathers hook
$ yarn server help

# generate static project
$ yarn static
```

For detailed explanation on how things work, checkout [Nuxt.js](https://nuxtjs.org) and [Feathers](https://feathersjs.com/) docs.

## Credits
This repo is based on [create-nuxt-app](https://github.com/nuxt/create-nuxt-app) Express template and [@featherjs/cli](https://github.com/feathersjs/feathers/tree/master/packages/cli) app generator.
