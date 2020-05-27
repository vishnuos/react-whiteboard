# This is whiteboard application

The purpose of this application to create whiteboard using [react](https://facebook.github.io/react/) and [imutable.js](https://facebook.github.io/immutable-js/)

If you like to play with application, there is brief instructions:

clone it

```
git clone https://github.com/vishnuos/react-whiteboard.git
```

make sure you have nodejs and those packages (babel webpack webpack-dev-server) globally installed, if not, install fresh [node.js](https://nodejs.org), then

```
npm install
```

to start application in development mode run

```
npm start
```

to build bundle for deploy run

```
webpack
```

**application structure**

- index.html - web page
- main.js - app entry point
- components/whiteBoard.js - main component
- store.js - main store

_it uses: React, SVG (to draw and graphical primitives), Immutable.js (to track history)_

## License

MIT
