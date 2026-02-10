# 📋 Full Stack Project Management Application

A modern, collaborative workspace management tool that enables teams to organize projects, assign tasks, track progress, and manage team workflows efficiently.

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

## ✨ Features

### 🏢 Multi-Workspace Management
- Create and manage multiple workspaces
- Separate projects and teams per workspace
- Workspace-level permissions and settings
- Easy workspace switching

### 📊 Project Analytics
- Real-time project progress tracking
- Team productivity metrics
- Task completion rates
- Visual analytics dashboards
- Project timeline views

### ✅ Task Management
- Create, edit, and delete tasks
- Assign tasks to team members
- Set due dates and priorities
- Track task status (To Do, In Progress, Done)
- Task filtering and sorting
- Drag-and-drop task boards

### 👥 Team Collaboration
- Invite team members via email
- Role-based access control (Admin, Member, Viewer)
- User management and permissions
- Team member activity tracking

### 📈 Dashboard & Reporting
- Overview of all projects and tasks
- Upcoming deadlines and overdue tasks
- Team workload distribution
- Progress charts and statistics

## 🛠️ Tech Stack

### Frontend
- **Framework:** React 18
- **Styling:** Tailwind CSS
- **State Management:** Redux Toolkit
- **Routing:** React Router v6
- **Forms:** Formik + Yup
- **UI Components:** Custom components with Tailwind
- **Charts:** Recharts
- **Drag & Drop:** React Beautiful DnD

### Backend
- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** PostgreSQL
- **ORM:** Prisma
- **Authentication:** JWT
- **Validation:** Joi


## 📁 Project Structure

```
project-management/
├── frontend/
│   ├── src/
│   │   ├── components/      # Reusable React components
│   │   ├── pages/          # Page components
│   │   ├── redux/          # Redux store and slices
│   │   ├── services/       # API service functions
│   │   ├── utils/          # Helper functions
│   │   └── App.js          # Main app component
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── controllers/    # Route controllers
│   │   ├── models/         # Database models (Prisma)
│   │   ├── routes/         # API routes
│   │   ├── middleware/     # Custom middleware
│   │   ├── utils/          # Helper functions
│   │   └── server.js       # Express server
│   ├── prisma/
│   │   └── schema.prisma   # Database schema
│   └── package.json
│
└── README.md
```

## 🗄️ Database Schema

### Main Tables
- **Users** - User accounts and authentication
- **Workspaces** - Workspace containers
- **Projects** - Projects within workspaces
- **Tasks** - Individual tasks
- **WorkspaceMembers** - User-workspace relationships
- **ProjectMembers** - User-project assignments

## 🔒 Security Features

- JWT-based authentication
- Password hashing with bcrypt
- Role-based access control (RBAC)
- Input validation and sanitization
- CORS configuration
- SQL injection prevention via Prisma

