# GyaanKosh---A-Kubernetes-and-Docker-based-Library-Management-System

--> Components:
Frontend: Plain HTML, CSS, JavaScript served via Nginx
Backend: Node.js + Express REST API
Database: MongoDB
Orchestration: Kubernetes
Authentication: Basic Auth (role-based: Student / Admin)
-------------------------------------------------------------------------------------------------------------------

 --> Features :
 
Student:
Register and login
Browse book catalog (public access)
Request books
View issued books and request status

Admin (Librarian):
Secure login - (Email - admin@library.com   Pass - admin123)
Add, update, delete books
Approve or reject student requests
Track issued books

-------------------------------------------------------------------------------------------------------------------


--> Project Structure


project-root/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── student-dashboard.html
│   ├── librarian-dashboard.html
│   ├── css/
│   └── js/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│   ├── server.js
│   └── package.json
│
├── k8s/
│   ├── frontend.yaml
│   ├── backend.yaml
│   ├── mongodb.yaml
│   └── seed-job.yaml
│
└── README.md

