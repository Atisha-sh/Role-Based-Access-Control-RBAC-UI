# Role-Based-Access-Control-RBAC-UI
A simple User Management Dashboard built using HTML, CSS, JavaScript, and JSON Server. This dashboard allows administrators to add, edit, and delete user information, such as usernames and emails, through an intuitive and responsive user interface. The project demonstrates how to create a basic CRUD application with a REST API using JSON Server to store and manage data.

The main goal of this project is to demonstrate how a scalable user interface can simplify user management tasks for administrators. By leveraging a clean design and seamless functionality, this dashboard serves as a foundational example of creating efficient and user-friendly applications for handling data. It is an excellent starting point for building more advanced systems like role-based access control or enterprise-level management tools.

## Features:
### Add Users: 
Easily add new users by entering a username and email. Each submission updates the backend in real-time.
### Edit Users: 
Modify existing user details directly from the dashboard. A seamless update feature makes editing intuitive.
### Delete Users: 
Remove users from the system with a single click. A confirmation prompt ensures safe actions.
### Dynamic User Display: 
Users are dynamically fetched and displayed from the backend using RESTful APIs.
### Responsive Design: 
Enjoy a smooth experience across devices with an interface that adapts to all screen sizes.

## Technologies Used:
### Frontend:
HTML: Markup for the structure of the dashboard.
CSS: Styling the interface to ensure a clean, user-friendly experience.
JavaScript: Handling the logic for CRUD operations, such as adding, editing, and deleting users.
### Backend:
JSON Server: A simple REST API for data management.

## File Structure:
```user-management-dashboard/
│
├── index.html            # Main HTML file containing the layout
├── style.css             # CSS file to style the dashboard
├── app.js                # JavaScript file for handling user management functionality
├── db.json               # JSON file used by JSON Server to store user data
├── README.md             # Project description (this file)
```

## Real-Life Use Cases
### Enterprise User Management:
Simplifies handling user data for small businesses and startups.

### Access Control in Applications:
The dashboard can serve as a base for implementing advanced RBAC systems.

### Educational Projects:
Perfect for learning CRUD operations and integrating RESTful APIs in front-end applications.

## Future Scope
### Role-Based Access Levels:
Introduce user roles (Admin, Moderator, Viewer) with different access privileges.

### Authentication:
Implement login and logout functionality for secure data handling.

### Pagination and Search:
Add features for searching and navigating through large user datasets.

### Database Migration:
Transition from JSON Server to a full-fledged backend like Node.js or Firebase.

### Integration with Real APIs:
Connect with production-grade APIs to handle real-world data.

## Setup Instructions:
#### 1. Clone the Repository
To get started, clone this repository to your local machine:

```git clone https://github.com/your-username/user-management-dashboard.git```

#### 2. Install JSON Server
To run the backend locally, you will need to install JSON Server. Install it globally using npm:


```npm install -g json-server```

#### 3. Create db.json
Create a file named db.json in the root directory of the project. This file will serve as the database for the application. Add the following initial content to db.json:


```
{
  "users": []
}
```

#### 4. Start JSON Server
After setting up db.json, open your terminal, navigate to the project folder, and run the following command to start JSON Server on port 5000:


```json-server --watch db.json --port 5000```

This will simulate a backend API that you can use to store and retrieve user data.

#### 5. Open the Project
Once JSON Server is running, open the ```index.html``` file in your browser or use a tool like Live Server in Visual Studio Code to view the project.

## How It Works:
#### Adding Users:

Admins can use the form in the dashboard to add new users. Once the form is submitted, the user data is sent to the backend (JSON Server), and the new user is added to the db.json file.

#### Editing Users:

Users can be edited by clicking the Edit button next to their name. The user’s data will be populated in the form fields, and once the form is submitted, the user’s information is updated in the backend.

#### Deleting Users:

Users can be deleted by clicking the Delete button next to their name. A confirmation prompt will appear, and upon confirmation, the user is removed from the backend.

#### Dynamic Display:

The list of users is dynamically fetched and displayed from the backend (JSON Server) each time the page loads or when a user is added, edited, or deleted.
Contributing
If you want to contribute to the project, feel free to fork the repository and submit pull requests. Suggestions and improvements are always welcome.

## Contributors:
Atisha Shrivas
Email: atisha.shrivas@gmail.com

## Live Demo:
https://atisha-sh.github.io/Role-Based-Access-Control-RBAC-UI/

