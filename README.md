# resource-and-docs-for-developer


### Overview

This repository contains resources and documentation specifically designed to support developers working on the OpenShift platform. It includes a variety of content, including:
This project is a collection of resources and documentation that can be imported into your projects to help developers understand how to use the code in this repository. <br>
This repository is used to store the resources (code, documents) related to developing a new feature or fixing bugs in an existing one. It contains information

### Get dummy/fake JSON data to use as a placeholder in development or prototype testing.

`https://dummyjson.com/` <br>

### Fake store rest API for your e-commerce or shopping website prototype

`https://fakestoreapi.com/` <br>

### Free fake API for testing and prototyping. Powered by JSON Server + LowDB. Tested with XV.

`https://jsonplaceholder.typicode.com/` <br>

### Get dummy/fake JSON data to use as a placeholder in development or prototype testing.

`https://restcountries.com/v3.1/all` <br>
`https://restcountries.com/#endpoints-all` <br>

### Location of a specific IP.

`https://ipapi.co/8.8.8.8/json/` <br>

### Generate random fake data and populate your application for easier development and testing.

`https://random-data-api.com/` <br>
`https://random-data-api.com/documentation` <br>

### All the Pokémon data you'll ever need in one place, easily accessible through a modern RESTful API.

`https://pokeapi.co/` <br>

### Public REST APIs (Postman docs)

This is a collection of different REST APIs that are completely public and do not require any authentication, making it easier for consumers to play with and understand what APIs are all about by seeing the many different ways in which APIs can be used.

`https://documenter.getpostman.com/view/8854915/Szf7znEe#0046135b-fdad-483b-8d39-0dafa956ef18` <br>

`https://api.zippopotam.us/in/767001` <br>

`https://documenter.getpostman.com/view/8854915/Szf7znEe` <br>


### chucknorris.io is a free JSON API for hand-curated Chuck Norris facts. Read more

`https://api.chucknorris.io/jokes/random` <br>


### React Js full course Learning Partner <Youtube>

`https://freeapi.miniprojectideas.com/index.html` <br>

### Free ER Model Deisign

`https://app.quickdatabasediagrams.com/#/d/ep45is` <br>


# Category MEAN/MERN Stack
 <br>

### Node.js and TypeScript Tutorial: Build a rest API with Typescript, NodeJS, and a file-based storage system.

`https://dev.to/realsteveig/nodejs-and-typescript-tutorial-build-a-rest-api-with-typescript-nodejs-and-a-file-based-storage-system-2l61` <br>

### JSON to Typescript interface Convert your JSON to Typescript interface. With AI

`https://js2ts.com/json-to-typescript` <br>

### JSON to JSON Schema

`https://codebeautify.org/json-to-json-schema-generator` <br>

### Route-Controller-Service structure for ExpressJS

`https://devtut.github.io/nodejs/route-controller-service-structure-for-expressjs.html#model-routes-controllers-services-directory-structure` <br>

### How to Build an API with Mongoose and Express.js

`https://dev.to/franciscomendes10866/setup-mongodb-with-mongoose-and-express-4c58` <br>

### Deploy React App on Hostinger
`https://dev.to/mwoodson11/deploy-react-app-on-hostinger-3id5` <br>

### Why API is Called Twice in React?

`https://xerosource.com/why-api-is-called-twice-in-react/` <br>


### Free Illustration Image for website 
#### Browse to find the images that fit your needs and click to download. Use the on-the-fly color image generation to match your brand identity.
`https://undraw.co/illustrations`
`https://www.manypixels.co/gallery`


### Beautiful CSS box-shadow examples
`https://getcssscan.com/css-box-shadow-examples`

### Tailblocks for Tailwind Code Sbippets
`https://tailblocks.cc/`

### Skip password field when retrieve users data mongoose author @bradtraversy repo proshop_mern
`https://github.com/bradtraversy/proshop_mern/blob/master/backend/controllers/userController.js`
```js
// @desc    Get user by ID
// @route   GET /api/users/:id
// @access  Private/Admin
const getUserById = asyncHandler(async (req, res) => {
  const user = await User.findById(req.params.id).select('-password')

  if (user) {
    res.json(user)
  } else {
    res.status(404)
    throw new Error('User not found')
  }
})
```
