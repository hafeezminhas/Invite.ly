# Invitely 1.0

> A full fledged Knockout.js application with Node.js as a backend and REST API implemented with latest MongoDB, Mongoose and Express 4

Brief instructions:

# Step : 1

Create a database called 'invitify at https://mlab.com and get your credentials (username and password)

> Important: store the 'username' and 'password' safely. You have to enter them later.

# Step: 2

```
$ git clone https://github.com/scriptstar/Invite.ly
$ cd Invite.ly
```

# Step: 3

Create a .env file at the root of this project and add two variables

```
$ touch .env
```

Open the .env file that you just created using your favourite editor and add two variables. I hope you have saved username and password from the step 1. Use them below and replace username and password.

```
MONGO_USER = 'username'
MONGO_PASS = 'password'
```

Finally Run the following commands

```
$ npm install
$ npm start
```

Navigate to http://localhost:4000

# Live deployment to Now

install Now cli

```
npm i -g now
```

Go to root folder and then type the following command. I hope you have saved username and password from the step 1. Use them below and replace username and password.

```
$ now -e MONGO_USER='username' -e MONGO_PASS='password'
```

To see my working copy on the world wide web
https://invitely-yipbblaaso.now.sh/rsvp#5c7bfcd629146b006956fed3

Don't forget to vote. Enjoy!
