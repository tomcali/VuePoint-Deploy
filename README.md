# VuePoint-Deploy

Heroku deployment of VuePoint Project

We had difficulty in posting to Heroku. The general process was to utilize webpack with Babel transpiling from ES6 to ES5. We created a dist subdirectory with what we though was all the requisite files. But we were unsuccessful in getting the full app to run remotely. To tell the truth, Heroku is not our preferred platform given its limited support of SQLite3. AWS is the more likely location for future hosting of the fully developed app. This repository shows the work as it stands for Heroku posting


## Original Deploy Source Info from Sagar Jauhari

https://medium.com/@sagarjauhari/quick-n-clean-way-to-deploy-vue-webpack-apps-on-heroku-b522d3904bc8

with GitHub repo at

https://github.com/sagarjauhari/vue-deploy-demo

### Vue Heroku deploy demo

Repo accompanying the blog post [Quick-n-clean way to deploy Vue + Webpack apps on Heroku
](https://medium.com/@sagarjauhari/quick-n-clean-way-to-deploy-vue-webpack-apps-on-heroku-b522d3904bc8#.xexhdzg4x)

- [dist/server.js](dist/server.js)
- [dist/package.json](dist/package.json)

### Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# deploy dist folder to Heroku
npm run deploy
```

For detailed explanation on how things work, checkout the [guide](https://github.com/vuejs-templates/webpack#vue-webpack-boilerplate) and [docs for vue-loader](http://vuejs.github.io/vue-loader).