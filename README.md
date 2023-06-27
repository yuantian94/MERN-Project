# MERN Stack E-commerce Web Application
This is a MERN Stack e-commerce application. The application will have not only basic functionalities such as a shopping cart and product search, but also advanced things such as chat, real-time sales charts, product attributes (e.g. product color to choose from), creating testable components in React and other things. MERN consists of MongoDB (as a database), Express (a framework to make it easier to use Node), React (to create user interfaces), and Node (as a server). 

# Application Demo
- main page

  ![1687473194259](https://github.com/yuantian94/MERN-Project/assets/13746207/4a636c95-2f48-484f-b5cb-870befdae4e4)

- Filter and search

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/3efe9275-f0ed-406e-bc16-2ab1715f5ace)

- Product detail page

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/6148842a-0029-4524-9550-bea53beeae0f)

- Cart page

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/05430d0f-b940-43fe-9739-740087284c51)

- Order page

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/4c4cede6-9f78-46ee-920e-dd6929cf576e)

- Seller Order page

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/c850ca4f-9632-44d6-9725-aac52c4b5d47)

- Live chat

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/01b9c931-c58f-4fbb-8254-b181938e8f06)

- Seller Analytic

  ![image](https://github.com/yuantian94/MERN-Project/assets/13746207/b2861ee4-8673-446d-bfb1-3edc021b58c9)


# Application features
- Some of the e-commerce app features:

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

# How to run
Make sure you have your own credentials:
 - in backend/.env file for MONGO_URI variable
 - frontend/src/pages/user/UserOrderDetailsPage.js for PayPal client-id

1. Open terminal on the frontend folder and run "npm install"
2. Open terminal on the backend folder and run "npm install"
3. Having terminal opened on the backend run "npm run dev" to run the application
4. Optionally run seeders by running "npm run seed:data" (being in the backend folder)
