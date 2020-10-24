### Install SASS

#### create package.json

> npm init or npm init -y by default

#### install node-sass

> npm install node-sass --save

#### config npm run

```JSON
{
    "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "compile": "node-sass --watch sass -o css"
  },
}
```
