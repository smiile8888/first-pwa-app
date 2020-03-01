# The Weather App - First Progressive Web App

This repository is part of my learning journey on Progressive Web App technique via [Google codelab][codelab]. If you want to get through whole tutorial, just go to codelab.

You can also find the original sourcecode at this [GitHub repository][git-repo].

## Progressive Web App (PWA) ?
It is a technique enable the web-based application to be an installable, app-like experience on desktop and mobile. It also provides a precache feature by using a service worker. To be installable, adding `manifest.json` to the app with `beforeinstallprompt` event notifies the user that the app is inatallable. To be an app-like, the app has to be responsive to support the look in both mobile and desktop.

## Getting started

1. Clone this repository
2. Go to the directory in your local laptop
3. Install dependencies
```npm install```
4. Start the server
```node server.js```
5. Open a browser tab to http://localhost:8000

**Note:** you have to get the API key at [DarkSky][darksky] and put the key in `.env` file as following:
```DARKSKY_API_KEY="_PUT_YOUR_DARK_SKY_API_KEY_HERE_"```

[codelab]: https://codelabs.developers.google.com/codelabs/your-first-pwapp/
[git-repo]: https://github.com/googlecodelabs/your-first-pwapp/
[darksky]: https://darksky.net/dev