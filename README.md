# Final Team Project "Drinkmaster"

A web application that allows you to explore various cocktails and create your
own masterpieces in the art of cocktail preparation. In our application, you can
discover the best recipes, learn how to make them, and experiment with flavors.

## Repository Template

This project was created based on
[Create React App](https://github.com/facebook/create-react-app). To familiarize
yourself with the template,
[refer to the documentation](https://facebook.github.io/create-react-app/docs/getting-started).

## Project Description

"Drinkmaster" is the graduation project of the "Full Stack Developer" course at
the GoIT IT school, utilizing all acquired knowledge and technologies. It
onsists of the frontend part: the main website, which is presented in this
[repository](https://github.com/Dyhless/drinkmaster-teamproject-frontend), the
backend part
([view the backend repository](https://github.com/Dyhless/drinkmaster-teamproject-backend)),
and the MongoDB database..

### Frontend

The "Drinkmaster" application is implemented using the React.js library,
utilizing HTML, CSS, Javascript, and the Vite build tool. It is a multi-page
website with the Redux Toolkit state library, routing through React Router, CRUD
operations implemented using Axios with requests to our RESTful web service.

`We implemented:`

- User authentication using tokens
- User subscription to newsletters via email
- Creation of custom recipes
- Adding recipes to the favorites category
- Viewing own recipes
- Viewing drinks by categories
- Filtering and searching for drinks based on various criteria
- Switching between light/dark themes, preserving the preference in the database
  for cross-device consistency
- Adaptive web layout for comfortable viewing on various devices
- Editing user data and adding avatars
- Motivational modal windows to uplift user mood and activity

`Libraries Used:`

- emotion
- mui/material
- mui/x-date-pickers
- reduxjs/toolkit
- types/react-transition-group
- vitejs/plugin-react-swc
- axios
- dayjs
- formik
- lodash.throttle
- moment
- prop-types
- reselect
- styled-components
- yup
- react
- react-debounce-input
- react-dom
- react-redux
- react-router-dom
- react-scripts
- react-select
- react-spinners
- react-svg
- react-toastify
- react-transition-group
- redux-persist
- uuidjs
- vite-plugin-svgr
- web-vitals

### Backend

The "Drinkmaster" backend is a web server implemented in Node.js, paired with
the NoSQL MongoDB database. The route documentation is described
[here](https://drinkmaster-teamproject-backend.onrender.com/api-docs/). The
backend project was deployed on the Render.com server, enabling developers to
work with a remote database, make requests, and test the application.

`We implemented:`

- Access to the application only for authorized users
- Ability to edit user data, as well as save, add, and create a personal
  collection of drinks
- Filtering drinks based on various criteria
- Restriction on showing alcoholic drinks to minors and displaying only
  non-alcoholic drinks on pages
- Highlighting popular drinks
- Retrieving information from external databases, processing on the backend, and
  returning information to the frontend application: information about drink
  collections, categories, necessary utensils, ingredients.
- Creating a unique avatar for each authorized user
- Saving images on the Cloudinary cloud service
- Subscribing to newsletters using the Mailgun email manager
- Logging server activity and error tracking

`Libraries Used:`

- jsonwebtoken
- mongoose
- morgan
- multer
- multer-storage-cloudinary
- nanoid
- nodemailer
- path
- pug
- swagger-ui-express
- uuid
- bcrypt
- body-parser
- cloudinary
- cors
- cross-env
- crypto
- dotenv
- express
- fs-extra
- gravatar
- html-to-text
- jimp
- joi

## Над проектом працювали:

- Anna Futryk - frontend
- Anastasiia Savitska - frontend
- Denis Kovtun - backend
- Dmytro Medvediev - scrum master, frontend
- Daria Yashchuk - frontend Yulia
- Soloveniuk - frontend
- Katerina Ryabykh - backend and frontend Volodymyr
- Musaelyan - frontend
- Svitlana Buiuvol - frontend
- Inna Tereshchenko - frontend
- Oksana Ponomariova - frontend
- Victoria Rosovska - team lead, frontend
