# TodoList_Project
## [TodoList Application](https://hull-todos-program.herokuapp.com/lists)

![image](https://user-images.githubusercontent.com/12583065/158920617-49ae46ec-8755-4e17-ad20-53cd3263da83.png)

## Description
This is a simple todo app that allows a user to create catagories for their todos and check them off as they are finished. This project is based on an sinatra/ruby backend connected to a posgres SQL database using a adapter pattern. The sql database has two tables one for the todo catagory list and one for todos. These tables have a many to one relationship because there can be more than one todo for each catagory but only one catagory for each todo. The backend is using Ruby with the Sinatra framework. The front-end uses vanilla HTML, CSS and Javascript.

## Development
To start building this application I started with a basic file using cookies/session to store the data to be used for the application. This included dates, daily budget, and expenses. AFter getting the application working, I pulled out all of the methods creating, retrieving, updating, and deleting data from the main application file into a session persistance file to set up a simple interation between the session and the main file. Lastly, I changed the session persistance file into a data persistance file that connected to a prosgre SQL database using an adapter pattern.

## Usage
Step 1: Start by adding a Catagory
Step 2: Add Todo items to the Catgory
Step 3: Check Off items as they are completed
Step 4: Check off entire catagories
Step 5: Edit catagories/Todos
Step 6: Delete catagories/Todos

## Roadmap
