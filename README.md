# Chat App
This is Chat App with React JS

### Installation

This Repo requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies and start the server.

```sh
$ git clone 'repo-name'
$ cd 'repo-name'
$ npm install or yarn install
$ npm run build
$ npm run start
```
### Tech

This repo uses a number of open source projects to work properly::

Frontend :
  -  [React JS](#)
  -  [React DOM](#)
  -  [Axios](#)
  -  [Socket-IO](#)
  
Backend :
  -  [Node.js](#)
  -  [Express.jss](#)
  -  [Socket-IO](#)
  
Database :
  -  [Mongoose](#)
  -  [MongoDB](#)

### Demo
  - HTTP protocol (no certificate, listen on 3000 port)

### Required Global Package
  - sudo npm install -g nodemon

### Project Structure
````
repo-name/
  README.md
  node_modules/
  package.json
  public/
    assets/
    
    outputs/
    chatroom.html
    login.html
    signup.html
  src/
    app/
      ButtonAppBar.js
      ChatGridLayout.js
      ChatRoomLayout.js
      ChatRoomPaper.js
      ContactList.js
      index_chatroom.js
      index_login.js
      index_signup.js
      InputBox.js
      Login.js
      SignUp.js
    models/
      Message.js
      User.js
    socket/
      MessageSocket.js
      UserSocket.js
  package-lock.json
  package.json
  server.js
  webpack.config.js
````  

### Screenshot
![Image description](/images/npm-run-start.png)
