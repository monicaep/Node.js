1. What is `npm` and what does it do?

`npm` is the package manager for Node.js. Applications are made up of packages and `npm` manages those packages. The packages depend on each other.

2. What kind of information does `package.json` hold?

`package.json` holds the application information including the structure of the application. It tells npm how to structure the application. Any packages that are installed as part of the application will be saved under "dependencies" in the `package.json` file.

3. Google another Node package. Using the `demo` directory run `npm install <theNameOfThePackage> --save`. Check the contents of your `package.json` file to make sure that the dependencies list the name of the Node package.

I installed browserify.

{
  "name": "demo",
  "version": "1.0.0",
  "description": "Demo for node.js setup.",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [
    "demo"
  ],
  "author": "Monica",
  "license": "ISC",
  "dependencies": {
    "browserify": "^16.2.3",
    "express": "^4.16.4"
  }
}
