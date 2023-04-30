# ShinyDex

[ShinyDex](https://cornuel.github.io/ShinyDex/) is a living Scarlet and Violet Pokedex that allows users to manage their shiny Pokemon collection.

<img src="/login.png" width="45%"></img> <img src="/login_dark.png" width="45%"></img> <img src="/dashboard.png" width="45%"></img> <img src="/dashboard_dark.png" width="45%"></img> 

## Features

- **Sign-up** and **Login** pages
- A **dashboard** that presents cards of all 400 Pokemons from Scarlet and Violet games.
    - Add Pokemon to shiny collection and track them.
    - Sort Pokemons by name, number, type, stats, and ownership.
    - It's convenient to use when playing the game: you can see the shiny sprite of the Pokemon you want to hunt and/or see which Pokemon is the strongest in a certain stat.

## Built using

### Backend **Django**

- **Django**
- **Django REST framework**: To build the API endpoints for user authentication (signup/login) and to interact with the Firebase database.
- **Pyrebase4**: A Python wrapper for the Firebase Realtime Database API used to authenticate users and manage user data.

### Frontend **Vue.js**

- **Pinia**: A state management library used to define a user store that contains the user's token, login with getters and setters.
- **Tailwind**: for UI developement productivity and consistency across components.
- **Axios**: for the HTTP requests.
- **Vue-router**: to map URLs to views.
- **Notiwind**: provides a simple and flexible notification library to show success, error, warning, and information messages.
- **Vue-Sweetalert2**: it was employed to display confirmation pop-ups with a 'yes' or 'no' response option.
- **Vee-validate** to ensure proper user input validation.
- **Vue-chartjs**: for visually appealing and customizable bar charts.
- **Homemade Animated Place Holder**: to improve user experience when waiting for data to be fetched.
- **Font Awesome**

### Firebase Database

## What I learned
I am extremely satisfied with the development of **ShinyDex** 😄, as it provided an opportunity for me to gain experience with a variety of powerful libraries and technologies.
Throughout the development process, I learned how to effectively implement user **authentication** and **database integration** using Django Rest Framework and Firebase, as well as how to create an intuitive and visually appealing user interface with Vue.js and Tailwind.
I also gained valuable experience in **deploying** a full-stack web application using Python Anywhere, Github Pages and Amazon S3 for hosting images.
Overall, **ShinyDex** was a challenging and rewarding project that allowed me to expand my skill set and develop a greater appreciation for the power and versatility of modern web development frameworks and tools.
