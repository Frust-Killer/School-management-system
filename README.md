
# School Management System

A comprehensive web-based school management system for managing students, teachers, classes, and payments.

## Project Structure

- **Backend**: Node.js, Express, MySQL
- **Frontend**: HTML, CSS, JavaScript (Vanilla)

## Features

- **Main Panel**:
  <img width="1412" height="975" alt="image" src="https://github.com/user-attachments/assets/802ab326-11c7-4530-bc6f-a6c3d678d700" />
  
- **Admin Dashboard**: Manage students, teachers, classes, subjects, and payments.
  <img width="1425" height="902" alt="image" src="https://github.com/user-attachments/assets/97b0369f-b229-403e-9338-33e34d48b806" />

  <img width="1416" height="961" alt="image" src="https://github.com/user-attachments/assets/23718681-9c85-4ec4-b99e-5723e23a9996" />
  
- **Teacher Dashboard**: View assigned classes, students, and enter grades.
  <img width="1437" height="971" alt="image" src="https://github.com/user-attachments/assets/01855962-a3e4-4674-a76e-d49b7599815f" />

  <img width="1432" height="955" alt="image" src="https://github.com/user-attachments/assets/f28977a6-180a-4bdb-9a60-fa5dd10158c9" />

- **Student Dashboard**: View profile, grades, timetable, and payment history.
  <img width="1433" height="962" alt="image" src="https://github.com/user-attachments/assets/de44016d-461f-42e9-908f-1f1747cd83aa" />

  <img width="1432" height="913" alt="image" src="https://github.com/user-attachments/assets/3b8e73d4-d342-4199-a882-baf6739e8d06" />

- **PDF Generation**: Generate certificates and transcripts.
  <img width="1427" height="972" alt="image" src="https://github.com/user-attachments/assets/6e060939-e5f4-4d89-b1d8-485b65ed13f3" />

## Setup

1.  **Database Setup**:
    - Ensure your MySQL database is running.
    - Configure database connection in `backend/config/database.js` or `.env`.

2.  **Backend**:
    ```bash
    cd backend
    npm install
    npm start
    ```

3.  **Frontend**:
    - Open the `frontend` directory.
    ```bash
    python -m http.server 8000
    ```
    - Serve the files using a static file server (e.g., Live Server in VS Code).
4.  **Web Navigator Usage**:
   - Type in http:\\localhost:8000 on your web browser to access the main screen.
     
## Technologies

- Node.js
- Express.js
- MySQL
- Vanilla JavaScript
