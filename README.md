# AddressBook
This project is an AddressBook app designed to demonstrate full-stack web development using Django Rest Framework (DRF) for the backend API and React for the frontend UI.

### Features:
- **CRUD functionality** for managing contacts (Create, Read, Update, Delete).
- **User Authentication** for secure access to the app.
- Backend built using **Django Rest Framework (DRF)** to expose RESTful APIs.
- Frontend built using **React** with components for adding, editing, deleting, and displaying contacts.
- **Form validation** to ensure data integrity before submitting new or updated contacts.
- **Responsive design** to ensure a smooth experience on both mobile and desktop devices.

### Technologies:
- **Backend:** Django, Django Rest Framework, SQLite (or PostgreSQL)
- **Frontend:** React, Axios for API calls, React Router for navigation
- **Authentication:** JWT tokens for secure login
- **UI:** Styled with CSS/Bootstrap (or Material-UI)

### Installation:
1. Clone the repository: `git clone https://github.com/sinkukumar/addressbook-app.git`
2. Navigate to the backend directory and install dependencies: `cd backend && pip install -r requirements.txt`
3. Run migrations for the database: `python manage.py migrate`
4. Navigate to the frontend directory and install dependencies: `cd frontend && npm install`
5. Start the backend server: `python manage.py runserver`
6. Start the frontend server: `npm start`
   
Visit `http://localhost:3000` to view the React frontend and interact with your AddressBook app.

### Contributing:
Feel free to open issues or submit pull requests for improvements, features, or bug fixes. Contributions are welcome! 
