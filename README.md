## Blog App Node Back-end

Add .env to main folder

```js
MONGO_URI=
PORT=
JWT_SECRET=
```

To run go to nodeapi folder:

```js
npm run dev
```

## App Screenshots

<img src="app3.png" alt="BlogNode">
<img src="app4.png" alt="BlogNode">
<img src="app6.png" alt="BlogNode">

1st commit:

- DB using MongoDB Atlas
- Error validation using express-validator (validator/index.js)
- Completed API development for Posts

2nd commit:

- Nodejs crypto documentation https://nodejs.org/api/crypto.html to hashed passwords
- Virtual fields
- Completed API development for Authentication(user signup and signin)

3rd commit:

- Protecting routes (authorization) using express-jwt
- Users must be signin to make a Post
- Completed API development for Authorization

4th commit:

- User create, update and delete functionality
- Completed API development for Users

5th commit:

- Handle post file uploads using formidable
- Completed API Users and Posts CRUD relationship schema

6th commit:

- Added API Update profile with image
- Added API GET User Photo with route

7th commit:

- Added API USER follow and unfollow
- ADDEd API User remove follow and following

8th commit:

- Added API like/unlike functionality on Users
- Added Super Admin features
- Added Social register and signin/signout google
