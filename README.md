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
1. First, open your folder project into terminal and type the text like in this screenshot
![Image description](/images/npm-run-start.png)

2. Open your browser and login wiht your account or signup when you dont't account [http://localhost:3000/login](http://localhost:3000/login) like in screenshot
![Images description](/images/second-steps.png)

3. After login, you will see chat room like in screenshot
![Images description](/images/chats.png)

4. And then, you must create another account when you want test the chat. For test chat, you can choose another account like in screenshot i choose 'maman@gmail.com'

- This is chat room from my account
![Images description](/images/chat1.png)

- This is chat room from maman account
![Images description](/images/chat2.png)

