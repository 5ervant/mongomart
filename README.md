A good sample of e-commerce site, backed by MongoDB.<br />
5ervant's implementation of the final exam/project for "M101JS: MongoDB for Node.js Developers".

You can get this MongoMart application up and running with the following:<br />
*(It doesn't do much (yet), but you should be able to run it and experiment with the UI.)*

 - Checkout this repo, or download the .zip file and extract the zip file's contents.
 - Install the dependencies.
 - Make sure you have a `mongod` running version 3.2.x of MongoDB.
 - Import the *"item"* collection: `mongoimport --drop -d mongomart -c item data/items.json`
 - Import the *"cart"* collection: `mongoimport --drop -d mongomart -c cart data/cart.json`
 - Run the application by typing `node mongomart.js` in the mongomart directory.
