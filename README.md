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

## UI of Website

![Screenshot 2024-06-13 172959](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/543b9d3f-321d-4695-ab15-0ab583a872f7)

![Screenshot 2024-06-13 174016](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/5a706865-f6e3-4849-a34c-7d5f4d335a22)

![Screenshot 2024-06-13 173220](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/445e3a99-ee26-47e6-89f3-5dd48ff04e83)

![Screenshot 2024-06-13 173902](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/ae849a0f-9a26-4120-823f-ac98b87ae17c)

![Screenshot 2024-06-13 174315](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/dd21fa15-3b9f-4fbd-9eeb-ed3a70c063b8)

![Screenshot 2024-06-13 173122](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/f0e6ffd3-6976-4da1-993b-d4361ed873fe)

![Screenshot 2024-06-13 173046](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/26289049-a597-42f9-925a-b475a1c2febe)

![Screenshot 2024-06-13 174040](https://github.com/Darshanjasani73/MERN-Blogify/assets/167104440/dd80db81-9583-4c9f-99c1-549274f8c88e)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and passes all tests.

## License

This project is licensed under the MIT License. See the [MIT LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me at [djasani93@gmail.com](mailto:djasani93@gmail.com).


Thank you for using the Blog App! We hope you enjoy using it as much as we enjoyed building it.
