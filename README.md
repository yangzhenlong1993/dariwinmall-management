
# Content-Management-System
The content management system is based on RENREN-UI. Renren-UI is a front-end solution that builds and develops based on Vue and Element-UI. It provides powerful front-end functionalities for the Renren-Security background management system. Renren-UI enables separation of the front-end and back-end, with data interaction through tokens and independent deployment.  

## project structure
```
├── src                        
│  ├── assets                 // static resources
│  ├── components             // public components
│  ├── element-ui             // element ui
│  ├── i18n                   // globalization
│  ├── icons                  // icon
│  ├── mixins                 // mix
│  ├── router                 // router
│  ├── store                  // status management
│  ├── utils                  // commonly used utils
│  ├── views                  // business related pages
│  ├── App.vue
│  ├── main.js                // entrance
├── ...
├── package-lock.json
├── package.json
└── vue.config.js             // vue-cli scaffold configuration
```
## Deployment
```
# Compile for production
$ npm run build
# npm run build -- --report # generate report.html to analyze bundle content

# Publish to Github Pages (https://bit.ly/2YeUyzG)
$ npm run deploy
```
