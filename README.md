douitsu
=======

Identity management service.

## Setup

```bash
cp options.example.js options.mine.js
npm install
```

Edit options.mine.js as needed.

## Run

```bash
node app.js
```

And open [localhost:3333](http://localhost:3333)

## Gulp

Gulp does the following:
* Lint JavaScript
* Concatenate JavaScript
* Minify and rename said concatenated files
* Watch for file changes and do the above on the fly

### Install globally

```bash
npm i -g gulp
```

### Run

Make sure to run gulp in the background when making JavaScript changes.

```bash
gulp
```

## UI Config

### Signup

Edit signup_enabled in [public/js/config.js](https://github.com/ninjablocks/douitsu/public/js/config.js) to enabled / disable signup.

