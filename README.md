less-plugin-lesshat
========================

Imports [Less hat](http://lesshat.com/) mixins before your custom Less code.

## lessc usage

Install..

Notice require Less v3.2.1 (download from github)

```
npm install -g less-plugin-lesshat
```

and then on the command line,

```
lessc file.less --lesshat
```


## Programmatic usage

```
var LessPluginLesshat = require('less-plugin-less'),
    LesshatPlugin = new LessPluginLesshat();
less.render(lessString, { plugins: [LesshatPlugin] })
  .then(
```

## Browser usage

Browser usage is not supported at this time.
