# 🚀 Team Task Manager - Full Stack Application

A complete team task management system with role-based access control (Admin/Member), project management, task assignment, and real-time progress tracking.

## 📋 Project Overview

Team Task Manager is a full-stack web application that allows teams to:
- Create and manage projects
- Assign tasks to team members
- Track task progress with status updates
- Monitor overdue tasks
- Role-based access (Admin can create projects/tasks, Members can update status)

## 🛠️ Tech Stack

### Frontend
- **React 18** - UI Framework
- **Vite** - Build tool and dev server
- **React Router DOM v6** - Navigation and routing
- **Axios** - HTTP client for API calls
- **React Hot Toast** - Toast notifications

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MySQL** - Database
- **JWT** - Authentication
- **Bcryptjs** - Password hashing

### Deployment
- **Railway** - Backend + MySQL hosting
- **Vercel** - Frontend hosting (recommended)

## ✨ Features

### Authentication
- User signup with role selection (Admin/Member)
- User login with JWT token
- "Remember Me" functionality
- Password encryption with bcrypt

### Role-Based Access Control (RBAC)

#### Admin Can:
- ✅ Create projects
- ✅ Add/remove team members
- ✅ Create tasks
- ✅ Assign tasks to members
- ✅ Update any task status
- ✅ View all projects and tasks

#### Member Can:
- ✅ View projects they're part of
- ✅ View tasks assigned to them
- ✅ Update their own task status (pending → in-progress → completed)
- ✅ View dashboard stats

### Project Management
- Create new projects
- View all accessible projects
- Add members to projects
- See project statistics (member count, task count)

### Task Management
- Create tasks with title, description, due date
- Assign tasks to specific members
- Filter tasks by project and status
- Status flow: pending → in-progress → completed
- Priority indicators (Normal, Soon, Urgent, Overdue)
- Task details modal

### Dashboard
- Welcome message with time-based greeting
- Statistics cards (Total, Completed, In Progress, Pending, Overdue)
- Progress bar showing completion rate
- Recent tasks list
- Quick action buttons

### Responsive Design
- Mobile-first design
- Collapsible navigation menu on mobile
- Touch-friendly buttons (44px minimum)
- Fluid typography using clamp()
- Responsive grid layouts
- Works on desktop, tablet, and mobile

## 📁 Project Structure
