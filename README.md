# htpasswd-generator
[![pipeline status](https://gitlab.hellbit.de/ichag/htpasswd-generator/badges/master/pipeline.svg)](https://gitlab.hellbit.de/ichag/htpasswd-generator/commits/master) [![coverage report](https://gitlab.hellbit.de/ichag/htpasswd-generator/badges/master/coverage.svg)](https://gitlab.hellbit.de/ichag/htpasswd-generator/commits/master)


This project provides a web application which generates htpasswd entries.  
The app uses hash algorithms implemented in JavaScript, so your password has not to leave your browser.  

[bcryptjs](https://github.com/dcodeIO/bcrypt.js/) is used for [bcrypt](https://en.wikipedia.org/wiki/Bcrypt), it's the default and the recommended hashing algorithm.


## Demo
http://ichag.pages.gitlab.hellbit.de/htpasswd-generator/

## Project setup

```
git clone https://gitlab.hellbit.de/ichag/htpasswd-generator.git
```

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
