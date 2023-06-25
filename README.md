# MERN Stack E-commerce Web Application
This is a MERN Stack e-commerce application. The application will have not only basic functionalities such as a shopping cart and product search, but also advanced things such as chat, real-time sales charts, product attributes (e.g. product color to choose from), creating testable components in React and other things. MERN consists of MongoDB (as a database), Express (a framework to make it easier to use Node), React (to create user interfaces), and Node (as a server). 
![1687473194259](https://github.com/yuantian94/MERN-Project/assets/13746207/4a636c95-2f48-484f-b5cb-870befdae4e4)

Some of the e-commerce app features:

- shopping cart

- login, register

- PayPal payment

- upload images to Cloudinary and to local disk

- searching, sorting, filtering, pagination of product list

- multilevel categories

- bestsellers carousel

- star rating system and reviews

- real time sales charts using SocketIO

- chat using SocketIO

- deploy application to Heroku & Render

- React local state

- Redux state

- functional programming using React Hooks


Make sure you have your own credentials:
 - in backend/.env file for MONGO_URI variable
 - frontend/src/pages/user/UserOrderDetailsPage.js for PayPal client-id

1. Open terminal on the frontend folder and run "npm install"
2. Open terminal on the backend folder and run "npm install"
3. Having terminal opened on the backend run "npm run dev" to run the application
4. Optionally run seeders by running "npm run seed:data" (being in the backend folder)
