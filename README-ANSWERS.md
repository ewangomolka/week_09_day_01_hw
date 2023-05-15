questions 1-10:

answer 1: inside the server folder there is another folder named "helpers" in which is a file called "create_router.js" this has the necessary code inside which implements the CRUD functionality and updates the routes of exsisting and new games.

answer 2: the server folder is resonsible for the back end information. (routes, database, api etc.). Whilst the front end is being taken care of by the client folder which renders the data from the server folder and puts it online via the domain it also allows the user to make changes to the database by inserting and deleting games. (HTML, CSS).

answer 3: the server.js file is the file which alows the client side to render in the correct place whilst allowing the backend have structures in place to access the correct database. it is the file which brings the backend information together.

answer 4: the games router is the file which basically allows the traffic to flow correctly to the database. in other words it implements the Get, Put, Post and Delete methods.

answer 5: it is using a fetch method.

answer 6: it is an init method which allows more control to the API. for example: (same-origin)
tells browsers to include credentials with requests to same-origin URLs, and use any credentials sent back in responses from same-origin URLs. This is the default value.

answer 7: it makes requests send to the localhost: 9000 which further sends back to mongodb.

answer 8: we are using the mongodb drive because the driver features an asynchronous API which allows you to interact with MongoDB using Promises or via traditional callbacks.