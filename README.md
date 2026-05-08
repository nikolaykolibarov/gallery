# Gallery

A full-stack gallery web application built with the MEAN stack (MongoDB, Express.js, AngularJS, Node.js). Upload, manage, and display images with a responsive Bootstrap interface and smooth animations.

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Node.js | JavaScript runtime |
| Express.js | Backend web framework |
| MongoDB | NoSQL database |
| Mongoose | MongoDB ODM |
| AngularJS | Frontend framework |
| Angular UI Router | Client-side routing |
| Bootstrap | Responsive CSS framework |
| ng-file-upload | Angular file upload directive |
| Gulp | Task runner |
| Bower | Front-end package manager |

## Features

- Image upload functionality
- Gallery view with responsive grid layout
- RESTful API for picture management
- Client-side routing with Angular UI Router
- Smooth animations with angular-animate
- File upload handling with express-fileupload
- Gulp build system for minification
- Modular AngularJS architecture

## Prerequisites

- [Node.js](https://nodejs.org/) (v6.x or higher)
- [MongoDB](https://www.mongodb.com/) installed and running
- npm (comes with Node.js)
- Bower (`npm install -g bower`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nikolaykolibarov/gallery.git
   ```

2. Navigate to the project directory:
   ```bash
   cd gallery
   ```

3. Install server dependencies:
   ```bash
   npm install
   ```

4. Install front-end dependencies:
   ```bash
   bower install
   ```

## How to Run

1. Make sure MongoDB is running:
   ```bash
   mongod
   ```

2. Start the application:
   ```bash
   nodemon server/app.js
   ```

3. Open your browser and navigate to `http://localhost:3333`

## Project Structure

```
gallery/
├── client/
│   ├── css/              # Stylesheets
│   ├── dist/             # Built/minified files
│   ├── js/
│   │   ├── pictures/     # Picture module
│   │   ├── app.module.js # Main Angular module
│   │   └── app.routes.js # Route configuration
│   ├── views/            # Angular templates
│   ├── favicon.ico       # Site favicon
│   └── index.html        # Main HTML file
├── server/
│   ├── controllers/
│   │   └── picturesController.js  # Picture CRUD operations
│   ├── models/           # Mongoose schemas
│   ├── routes/
│   │   └── pictures.js   # Picture API routes
│   └── app.js            # Express server setup
├── bower.json            # Bower dependencies
├── gulpfile.js           # Gulp build tasks
├── package.json          # Node.js dependencies
└── README.md
```

> **Note:** This project was created for educational purposes to learn MEAN stack development and full-stack JavaScript application architecture.
