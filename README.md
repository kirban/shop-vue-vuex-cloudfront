[Link to S3 Bucket](http://kirbanan-first-app.s3-website-eu-west-1.amazonaws.com/)
[Link to CloudFront](https://d1bkt47zufnr4.cloudfront.net/)

Automated hints:

Run this command to build application and deploy it

```
npm run client:build:deploy
```

Also run 

```
npm run cloudfront:build:deploy
```

to update content on CloudFront and to invalidate cache

# shop-vue-vuex-cloudfront

See `develop` branch for development

## Project setup
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

### Run your unit tests
```
npm run test:unit
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
