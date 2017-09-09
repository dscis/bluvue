# BluVue
This package is a fork of [vue-blu](https://github.com/chenz24/vue-blu). Unfortunately the original
author isn't maintaining the package. So I created this fork do so myself. Primary objective is to keep
Bulma.io in line. Any bugs unresolved in the original package will be addressed in time.

# Upgrade (Sept 2017)
Depedencies
* Bulma 0.2.3 > 0.5.1
* Vue.JS  2.1.10 > 2.4.2
* Vue-Router 2.1.1 > 2.7.0

* Remove breadcrumbs
* Update tags sass

# Bluvue
Bluvue is an ui components library base on VueJS and Bulma that helps you build your web application easily

## Documents & Demo (original package)
[documents & demo](https://chenz24.github.io/vue-blu/#/)

## Installation
Blu is available on NPM
```
npm install bluvue --save
```
### Quick Start
```
import Vue from 'vue'
import VueBlu from 'bluvue'
import 'vue-blu/dist/css/vue-blu.min.css'

Vue.use(VueBlu)

```

## Development

```bash
# install dependencies
npm install
# serve with hot reload at localhost:8080
npm run dev
# build for production with minification
npm run package
```