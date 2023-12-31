# Lerich Osay's Full-Stack Planner Web Application

Simple productivity web application that will be built using **MongoDB**, **React**, and **Spring** over the course of Winter 2023/24. Both the React client application and Spring server application will be held in this repository, navigate to either respective folder to run them. Remember to make sure the requried dependencies are installed before running.

## Key Features to Implement

* [ ] Clock Component
* [ ] To-Do list
  * [ ] Mark off items when completed
  * [ ] Dynamic UI depending on severity / deadline of item
  * [ ] Able to overlay onto calendar
  * [x] MongoDB collection for to-do items
* [ ] Calendar
* [ ] User Account Create / Login
  * [x] Create Log In / Sign up Form template
  * [ ] Link session / token that controls access to user info
  * [x] MongoDB collection for users
* [ ] Able to save User Calendar and To-Do List to MongoDB database
  * [x] Create API endpoints in Spring application for planner data 

## Dependencies

**Client**
* ``react v18.2.0``
* ``react-dom v18.2.0``
* ``react-router-dom v6.21.1``
* ``react-scripts v5.0.1``
* ``tailwindcss v3.4.0``
* ``axios v1.6.4``
* ``@klarr-agency/circum-icons v1.1.39``

**Server**
* ``spring-boot-starter-web v3.2.1``
* ``spring-boot-starter-data-mongodb v3.2.1``
* ``spring-boot-devtools v3.2.1``
* ``spring-dotenv v3.0.0``
* ``lombok v1.18.30``
