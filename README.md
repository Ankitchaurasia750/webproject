The MERN stack which consists of **Mongo DB**, **Express.js**, **Node.js**, and **React.js** is a popular stack for building full-stack web-based applications because of its simplicity and ease of use. the MERN stack has been the goto stack for a large number of web applications. 


This is a full-stack chat application that can be up and running with just a few steps. 
Its frontend is built with [Material UI](https://material-ui.com/) running on top of React.
The backend is built with Express.js and Node.js.


Real-time message broadcasting is developed using [Socket.IO](https://socket.io/).

### Features

This application provides users with the following features

* Authentication using **JWT Tokens**
* A **Global Chat** which can be used by anyone using the application to broadcast messages to everyone else.

* A **Private Chat** functionality where users can chat with other users privately.

* Real-time updates to the user list, conversation list, and conversation messages

### How to use

You can have this application up and running with just a few steps because it has both the frontend and the backend in a single repository. Follow the steps below to do so.

1. Once you have the repo, you need to install its dependencies. 
So using a terminal, move into the root directory of the project and execute `npm install` to install the dependencies of the Node.js server and 

2. Then run `npm run client-install` to install the dependencies of the frontend. The second command is a custom command that I wrote to simplify the installation process.

3. This application uses MongoDB as its Database. So make sure you have it installed. You can find detailed guides on how to do so [here](https://docs.mongodb.com/manual/administration/install-community/). Once installed, make sure that your local MongoDB server is not protected by any kind of authentication. If there is authentication involved, make sure you edit the `mongoURI` in the `config/keys.js` file.

4. Finally, all you have to do is simply run `npm run dev`. 

5. The frontend of the application will be automatically opened in your web browser and you can test it away.


