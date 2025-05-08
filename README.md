# Taskify 

## Taskify is a full stack task management web application built using latest tech stacks

### Tech used ⬇️

## ✅ Frontend : Next.js , Tailwindcss , ShandCN UI , Formik , Yup 
## ✅ Backend : Node.js with Express 
## ✅ Database : MongoDB with mongoose (as ODM)
## ✅ Secure Password and authentication : Bcryptjs ,JWT

### Functionalities ⬇️
- Registration and Login users.
- Create , Read , Update and Delete task.
- Search task by task Title.
- Filter tasks by status , priority , date and overdue date.
- Assign and Unassign task to other users.
- Get notify when task  assigned.


### Setup and Run locally

- clone this repo using `git clone`
- open terminal 
- Go to respective folder ( backend and frontend)
  `cd backend/` and `cd frontend/`
- Run `npm install` in both terminal.
- Run `npm run devServer` for backend server
- Run ` npm run dev ` for frontend server

### Approach

#### 1 . First, I have read the requirements properly then started working . I have first developed the authentication and authorization flow in both frontend and backend . Developed user schema(backend) , UIs(frontend) and then APIs and connected both properly .

### 2 . Secondly, developed the frontend fully like different pages ,components as well as search and filter functionalities , tested them by using some sample data on frontend without any API then developed the whole backend for the CRUD task functionalities .

### 3 . Lastly sovled some bugs and few more functionalities like assigning and unassigning tasks.

### Assumptions
- Used JWT and Bcryptjs for authentication and authorization for secure login and registration
- Used Formik and Yup for better form management and validations
- Used ShadCN UI along with Tailwindcss for mordern and aesthetic look as well as fast development

### Trade-offs

- Not developed any advanced features mentions for developing core functionalities within deadline

- Not used Socket.IO due to time constraints as well as complexity 

- Not developed any proper task assigned notification but basic  by assuming that user will get all task whenever he/she login again (user stays for few minutes on the app and login again) , also with every time when user will delete , update and add task , getTasks called everytime so user get updated tasks along with assigned task .


*Note : While developing this application I was fully engaged and focussed  and to deliver within deadline I have not done git commits after every feature