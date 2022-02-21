### For Markus Wals

It seems that I've done what you asked me to do. But it's not working properly.
Here is an explanation.

The extension "quasar-app-extension-firebase" doesn't seem to be working anymore.
I believe that when we talked about this task you mentioned easy method for authorization with  "quasar-app-extension-firebase" and "firebase-composables" packages.
But I investigated that none of these packages are supported by author Luke Diebold anymore. In addition, both of it were in alpha stage, what means they are not production ready.
Instead of contribution these packages author created new one - it called @vueauth/auth. But it's as well in the alpha version.

First thing which I noticed when I started to use this module - the last versions of it throws errors in console and not working at all.

I downgraded "firebase-composables" manually to version 1.0.0-alpha.16 and then it started to work, but it need to be improved by contributor of the npm package.

So my suggestion - is to make our own custom authorization without these non-stable extensions.



# Quasar App (firebase-ext-test)

A Quasar Framework app

## Install the dependencies

```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)

```bash
quasar dev
```

### Lint the files

```bash
npm run lint
```

### Format the files

```bash
npm run format
```

### Build the app for production

```bash
quasar build
```
