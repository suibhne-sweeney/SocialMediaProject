# SocialMediaProject
Twitter/Facebook clone using the MERN Tech Stack.

I created a full-stack social media website inspired by Facebook, implementing full CRUD (Create, Read, Update, Delete) capabilities using the MERN (MongoDB, Express, React, and NodeJS) stack. It's a proof of concept, but I believe it reflects my abilities and dedication to web development.

![first30secs](https://github.com/suibhne-sweeney/SocialMediaProject/assets/110748326/bac7e420-e76c-442e-b21c-d91a00db8eef)

# Overview
The application features a user-friendly registration page with thorough validation and an option to upload a profile image. Once registered, users could log in to access their personalized home page. The home page boasts a clean design, showcasing various widgets with detailed information about the current signed-in user. Users have the ability to create posts, add images, edit, and delete their posts, as well as view a feed containing all user-generated posts.

Furthermore, users could like and dislike posts, view comments, share, and add friends. The friend list is dynamically updated, allowing users to add or remove friends as needed. Additionally, users can visit other user's pages, view their friends, posts, likes, and interact with their content. The application offers the option to switch between light and dark modes. The responsive nature of the application ensures that it adapts to various screen sizes.

Backend APIs, created from scratch, fetched all the information displayed on the user interface from the MongoDB database.
# Back-End
On the backend, I leveraged Node.js as the runtime environment, Express.js as the backend framework, and Mongoose for managing the Mongo database. User authentication was handled using JSON Web Token, and file uploading was made possible with Multer.
# Front-End
The technologies employed for the front-end was React, with navigation powered by React-Router, Formic and Yup for forms and form validation. Redux Toolkit facilitated state management, enhanced by Redux Persist to store data locally. Lastly for image upload, React Drop Zone was utilized.
