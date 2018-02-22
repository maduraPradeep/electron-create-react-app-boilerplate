
# electron-create-react-app-boilerplate

A simple electron app boilerplate powered by create-react-app.

## Requirements
 * Node >= 8.2.0

## Running locally
1. `npm install`
2. `npm start`

## Packaging the app
1. `npm run build`
2. `npm run pack`
3. `npm run dist`

Your app will packaged as an .exe in the dist folder using the [electron-builder](https://github.com/electron-userland/electron-builder) package. Edit the build section of the package.json to build on additional platforms.

## Resources
* [Create React App](https://github.com/facebookincubator/create-react-app)
* [Electron](https://electronjs.org/docs/tutorial/quick-start)
* [electron-builder](https://github.com/electron-userland/electron-builder)