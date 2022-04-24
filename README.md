# PHP Gulp Boilerplate

Will run a PHP server with BrowserSync, Sass support, and ES6 Javascript.

#### Install your modules
```
npm install
```

#### Local development
```
gulp
```

#### Build files for production
```
NODE_ENV=production gulp build
```

#### Deploy

You'll need to add the SFTP information in `gulpfile.js/local.config.js`

```
NODE_ENV=production gulp deploy
```
