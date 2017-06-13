# geekenforcer-boilerplate
![alt text](https://s3-us-west-2.amazonaws.com/geekenforcer.com/header_red.png)

This is a template my site: www.geekenforcer.com. Any actual changes for the site will be reflected in the site's own repo. This is a boilerplate to makes sites like these using React and Node.d

## To run the project:
Clone the repo
```shell
npm install && node run
```
*This installs the latest build from the repo*

## For development
```shell
npm install && npm run
```
This runs the dev mode with webpack and react-hot plugin. While the dev-server is running, any changes made to a file will reflect and refresh in the browser. This is pointed to _127.0.0.1:3000_. 

## Building
To build any changes you have made into production:
```npm build``` 
If that does not work then run:
```webpack --config webpack-production.config.js --progress --colors```
Now your node server will host all the static files from the build folder

## Libraries
This project uses:
- Semantic-UI for the design: <https://react.semantic-ui.com/>
- Webpack v1 for transpilation *yes I know I should be moving to v2 but I like how versatile my config is* <https://webpack.github.io/>
- MobX is configured but not used in the project <https://mobx.js.org>
- React <https://facebook.github.io/react>
- Background uses a modified version of Particles.js <https://github.com/VincentGarreau/particles.js/>
