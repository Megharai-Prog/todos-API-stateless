Todo API Project
This is a simple Node.js + Express.js project that creates a RESTful API for managing a Todo list. The frontend is a static HTML page that interacts with the backend using the Fetch API.

Features
View all todos (GET /todos)
View a specific todo by ID (GET /todos/:id)
Add new todos (POST /todos)
Delete todos (DELETE /todos/:id)
Each todo item is an object with the following shape:

{
  "id": 1,
  "name": "Sample todo",
  "priority": "high",
  "isComplete": false,
  "isFun": true
}
Project Tree
Todos-API-in-memory 
  ├─ package.json
  ├─ server.js  
  ├─ public/  
  │  ├─ index.html 
  │  ├─ script.js 
  │  └─ style.css
  ├─ README.md 
  └─ .gitignore 
Frontend
HTML, CSS, and JavaScript
Styled using Flexbox
Buttons with distinct colors
How to Run
Run npm install express in your project directory.
Run node server.js to start the server.
Open index.html in your browser.
Add your code to the TODO activities for the program to run correctly!
Enjoy your Todo app!
