<h1>Sociopedia- Server</h1>

Firstly, copy the `.env.example` file to `.env` by
```
cp .env .env.example
```

Add the given environment variables in the `.env` file.
```
MONGO_URL=''
JWT_SECRET=''
PORT=
```

Install the node modules:
`npm install`

To run the server run the command:
`nodemon index.js`

Server should be running on port 3001

PS:
If you want to add dummy data in database:
Uncomment these lines in `index.js` file once.

```
/* Add Data One Time */
// User.insertMany(users);
// Post.insertMany(posts);
```

