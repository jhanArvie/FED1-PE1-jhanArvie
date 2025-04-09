Git repo    https://github.com/NoroffFEU/FED1-PE1-jhanArvie.git
Figma       

# FED1 Project Exam 1

Use this file to describe your project.# HotView Labs Blog

A responsive blog web application built with vanilla HTML, CSS, and JavaScript.

## Features

- Interactive banner carousel showing latest posts
- Responsive blog post grid
- Individual blog post pages
- User authentication (login/register)
- Blog post management (create/edit/delete) for authenticated users
- Responsive design for all screen sizes

## Project Structure

```
my-blog-project/
│
├── index.html                     ← Blog Feed Page (Home)
│
├── css/
│   └── style.css
│
├── js/
│   ├── api/                      ← All API interaction logic (ES6 modules)
│   │   ├── auth.js              ← login, register, token storage
│   │   └── posts.js             ← fetch, create, edit, delete posts
│   │
│   ├── components/              ← UI components (e.g., carousel, modal)
│   │   └── carousel.js
│   │
│   ├── pages/                   ← Page-specific logic
│   │   ├── feed.js              ← Homepage (index.html)
│   │   ├── post.js              ← Single blog post (post/index.html)
│   │   ├── create.js            ← Create post (post/create.html)
│   │   ├── edit.js              ← Edit/Delete post (post/edit.html)
│   │   ├── login.js             ← Login (account/login.html)
│   │   └── register.js          ← Register (account/register.html)
│   │
│   └── utils/                   ← Reusable helpers (e.g., formatDate, storage)
│       ├── formatDate.js
│       └── storage.js           ← Handles localStorage (get/set token, etc.)
│
├── account/
│   ├── login.html
│   └── register.html
│
├── post/
│   ├── index.html
│   ├── create.html
│   └── edit.html
│
├── assets/
│   ├── logo.png
│   └── images/
│
└── README.md

```

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Noroff API for backend services

## Setup and Installation

1. Clone the repository
2. Open index.html in your web browser
3. Register an account to access admin features

## API Documentation

The application uses the Noroff API. Documentation can be found at:
- [API Documentation](https://api.noroff.dev/docs)
- [Swagger UI](https://api.noroff.dev/docs/static/index.html)


