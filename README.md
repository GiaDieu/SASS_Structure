### Install SASS

#### create package.json

> npm init or npm init -y by default

#### install node-sass

> npm install node-sass --save

#### config npm run

```JSON
"scripts": {
    "compilecss": "node-sass sass/main.scss css/style.css -w"
},
```
