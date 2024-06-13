# Blogfy Web Application - MERN Stack

## Introduction

Welcome to the MERN Stack Blog Website Blogify! This project is a full-stack application built using MongoDB, Express.js, React, and Node.js. It features a blog where users can read posts, comment on them, and like comments. Additionally, an admin dashboard is available with features such as creating, deleting, updating, and reading posts and comments. Users can upload their profile picture, and Firebase is used to store these images.

## Features

- User Authentication: Register and login functionality for users.
- Create, Read, Update, Delete (CRUD) operations for blog posts by only admin.
- Admin dashboard for managing users, posts and comments.
- search / filter option category wise and term wise which enter by user 
- Profile picture upload.
- Blog picture upload.
- Responsive design for optimal viewing on different devices.
- Commenting system for blog posts.
- User can also edit details like profile picture, user name, password and id.
- User profile.
- RESTful API design.
- JWT (JSON Web Token) for secure authentication.

  ## Usage
  
1. Visit the website and browse through the posts.
2. Sign up with your Google account or create a new account.
3. You can upload and change your profile picture.
4. Explore the dark mode and light mode themes.
5. Leave comments on posts and like other user's comments.
6. Access the admin dashboard by logging in with the following credentials:
- Email: your email
- Password: your password
- After signup Go to your user document in your collection in mongoDB and change value true of admin parameter and  it is your admin email.
- In admin dashboard you can create a new post and can see all the users, posts and comments.


## Technologies Used

- **Frontend:**
  - React.js
  - Redux
  - TailwindCSS
 
- **Backend:**
  - Node.js
  - Express.js
  - Google firebase 
  - MongoDB (with Mongoose ODM)
  - JWT (for authentication)
  - bcrypt (for password hashing)
 
## Live : 👉  https://blogify-blog-webapp.vercel.app/

## Production Ready

### Frontend repository : https://github.com/Darshanjasani73/Blogify-Frontend
### Deploy on Vercel : https://blogify-blog-webapp.vercel.app/

### Backend repository : https://github.com/Darshanjasani73/Blogify-Backend
### Deploy on Render : https://blogify-backend-1-0stb.onrender.com/

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and passes all tests.

## License

This project is licensed under the MIT License. See the [MIT LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me at [djasani93@gmail.com](mailto:djasani93@gmail.com).


Thank you for using the Blog App! We hope you enjoy using it as much as we enjoyed building it.
