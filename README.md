# CI/CD GCP Cloud Build test

This repo is for testing [Google Cloud Build](https://cloud.google.com/cloud-build/). Commits to this repo in the src/ and tests/ directories on the master branch will cause Cloud Build to build and deploy this Vue.js app to Firebase Hosting at [this](https://ci-cd-test-91831.web.app/) address.

------------

Vue.js setup

### Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Run your unit tests
```
npm run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
