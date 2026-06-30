# TaskFlow AI - SaaS AI Project Management Tool

<p align="center">

<img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=white" />

<img src="https://img.shields.io/badge/Django-Backend-092E20?style=for-the-badge&logo=django&logoColor=white" />

<img src="https://img.shields.io/badge/Django_REST_Framework-API-red?style=for-the-badge" />

<img src="https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white" />

<img src="https://img.shields.io/badge/JWT-Authentication-orange?style=for-the-badge" />

<img src="https://img.shields.io/badge/Djoser-Authentication-success?style=for-the-badge" />

<img src="https://img.shields.io/badge/Groq-AI-000000?style=for-the-badge" />

<img src="https://img.shields.io/badge/Llama_3.3-LLM-blueviolet?style=for-the-badge" />

<img src="https://img.shields.io/badge/Kanban-Project_Management-0052CC?style=for-the-badge" />

<img src="https://img.shields.io/badge/SaaS-Multi_Tenant-4CAF50?style=for-the-badge" />

</p>

<p align="center">

<img src="https://img.shields.io/badge/AI-Powered-purple?style=flat-square" />

<img src="https://img.shields.io/badge/Role_Based_Access_Control-blue?style=flat-square" />

<img src="https://img.shields.io/badge/Workspace_Management-success?style=flat-square" />

<img src="https://img.shields.io/badge/Project_Management-orange?style=flat-square" />

<img src="https://img.shields.io/badge/Real_Time_Collaboration-red?style=flat-square" />

<img src="https://img.shields.io/badge/Natural_Language_AI-black?style=flat-square" />

<img src="https://img.shields.io/badge/Team_Analytics-brightgreen?style=flat-square" />

</p>

Transform Traditional Project Management into an AI-Powered Collaborative Workspace.

🔗 Live Application: https://saa-s-ai-project-management-tool.vercel.app

SaaS AI Project Management Tool is a modern, enterprise-ready project management platform that combines collaborative workspaces, intelligent task management, secure role-based access control, and AI-powered productivity tools into a unified SaaS application.

The platform goes beyond conventional Kanban software by integrating Large Language Models directly into project workflows. From intelligent task creation and contextual project insights to predictive workload analysis, the application demonstrates how Artificial Intelligence can improve team collaboration without disrupting existing workflows.

Designed with scalable backend architecture, secure authentication, collaborative messaging, and enterprise-grade permission management, this platform showcases the implementation of modern SaaS engineering principles alongside practical AI integrations.

---

# 🌟 Why This Project?

Managing software teams involves far more than organizing tasks. Modern organizations require secure collaboration, intelligent automation, workload balancing, and real-time communication—all within a single platform.

This project addresses these challenges by combining traditional project management with modern AI capabilities.

Key Benefits:

✅ Secure multi-user SaaS architecture

✅ Intelligent AI-powered project assistant

✅ Natural language task creation

✅ Enterprise Role-Based Access Control (RBAC)

✅ Workspace and multi-project organization

✅ Real-time collaboration and messaging

✅ Burnout prediction through workload analytics

✅ Responsive modern user experience

Whether managing personal projects, startup teams, or enterprise software development, this platform centralizes collaboration while allowing AI to automate repetitive management tasks.

---

# 🚀 Core Platform Highlights

## 🔐 Enterprise Authentication & User Management

The platform provides a secure authentication system powered by JWT and Djoser.

Features include:

- Secure Sign In / Sign Up

- JWT Authentication

- Password Reset Workflow

- User Profile Management

- Personalized Dashboards

- Secure Session Management

---

## 🏢 Multi-Tenant Workspace Organization

Projects are organized using a scalable hierarchy.

Features include:

- Multiple Workspaces

- Multiple Projects per Workspace

- Organized Project Separation

- Collaborative Team Structure

- Workspace-Level Management

---

## 📋 Advanced Kanban Task Management

The application includes a complete project execution workflow.

Features include:

- Drag-and-Drop Kanban Board

- To Do / In Progress / Done Columns

- Task Priorities

- Due Dates

- Detailed Descriptions

- Subtasks

- File Attachments

- Threaded Task Discussions

---

## 💬 Collaboration & Messaging

Built-in communication tools eliminate the need for external messaging platforms.

Features include:

- Direct Messaging

- Conversation History

- Automatic Conversation Detection

- Duplicate Prevention

- Conversation Deletion

- Global User Search

- Server-side Search Optimization

- Debounced Search Requests

---

## 👥 Global User Discovery

The platform supports organization-wide collaboration.

Capabilities include:

- Search Users by Username

- Search Users by Email

- Assign Users to Tasks

- Invite Members into Projects

- High-performance Searchable Dropdowns

---

## 🎨 Premium User Experience

The application emphasizes modern SaaS design principles.

Highlights include:

- Responsive Layout

- Mobile-first Messaging Interface

- Slide-out Navigation

- Dark Theme Design

- Smooth UI Transitions

- Premium Typography

- Clean Dashboard Experience

---

# 🤖 AI Platform Highlights

Unlike traditional project management software, this platform embeds AI directly into project workflows.

Three dedicated AI modules power the intelligent features of the application:

- AI Project Intelligence Assistant

- Burnout & Workload Risk Detector

- Natural Language Task Creator

All AI functionality is powered by Groq's high-speed inference platform using Meta's Llama 3.3 Large Language Model.

---

# 🛠 Technology Stack

## Frontend Engineering

React

Provides a modern component-based frontend architecture focused on responsiveness and scalability.

Axios

Handles secure communication between frontend and backend services.

Lucide Icons

Delivers a clean, modern visual experience.

Custom TailwindCSS-inspired Styling

Creates a premium enterprise-grade user interface.

---

## Backend Engineering

Django

Provides the core backend architecture responsible for authentication, workspaces, projects, messaging, and AI integrations.

Django REST Framework

Builds scalable REST APIs consumed by the React frontend.

PostgreSQL

Stores all persistent platform data including users, workspaces, projects, tasks, conversations, and permissions.

---

## Authentication & Security

JWT Authentication

Modern token-based authentication for secure user sessions.

Djoser

Handles user registration, password management, authentication workflows, and recovery mechanisms.

---

# 🤖 AI-Powered Platform Modules

Artificial Intelligence is deeply integrated into the platform rather than being treated as a standalone chatbot. Each AI module is designed to improve productivity, automate repetitive workflows, and provide managers with actionable insights based on live project data.

---

## 🧠 AI Project Intelligence Assistant

The AI Project Intelligence Assistant acts as a context-aware project analyst capable of understanding the current state of the entire platform.

Instead of responding with generic answers, the assistant retrieves live platform data and provides intelligent responses based on actual project information.

### Key Capabilities

- Context-aware project analytics

- Real-time access to active workspaces and projects

- Task workload analysis

- Priority-aware project summaries

- Deadline monitoring

- Team workload insights

- Natural language interaction

- Actionable project recommendations

Example questions include:

- *"What's blocking the frontend team?"*

- *"Who is assigned to the most high-priority tasks?"*

- *"Which projects have overdue tasks?"*

- *"Show me the current workload distribution."*

---

## 📊 Burnout & Workload Risk Detector

Managing workload effectively is essential for maintaining healthy software teams.

The Burnout & Workload Risk Detector continuously evaluates assignments across all projects to identify potential overload situations before they impact productivity.

Instead of simply counting assigned tasks, the platform calculates a weighted workload score by considering:

- Number of assigned tasks

- Priority level

- Due date proximity

- Overall workload distribution

### Workload Scoring

Priority Weights:

- High Priority → 3x

- Medium Priority → 2x

- Low Priority → Standard Weight

Each user is categorized into one of four workload levels:

- Low Risk

- Medium Risk

- High Risk

- Critical Risk

Managers receive AI-generated recommendations such as:

> "John has 5 high-priority tasks due this week; recommend reassigning 2 to Sarah who has available capacity."

Additional features include:

- Color-coded workload indicators

- Progress bars

- Team health dashboard

- AI-generated recommendations

- Instant workload visualization

---

## ✨ Natural Language Task Creator

Creating tasks traditionally requires filling multiple form fields.

The Natural Language Task Creator simplifies this workflow by allowing users to describe tasks using plain English.

Example:

> "Create a high-priority task for Naruto to fix the login bug by this Friday."

The AI automatically extracts:

- Task Title

- Description

- Assignee

- Priority

- Due Date

without requiring manual form completion.

### Intelligent Features

- Natural language understanding

- Automatic field extraction

- Relative date interpretation

- Calendar date conversion

- Instant Kanban board updates

- Inline success notifications

- Automatic error handling

Examples of supported date expressions include:

- Tomorrow

- This Friday

- Next Week

---

# 🔐 Enterprise Role-Based Access Control (RBAC)

One of the platform's core engineering features is its enterprise-grade Role-Based Access Control system.

Rather than relying on simple ownership models, every workspace supports multiple user roles with clearly defined permission boundaries.

---

## 👑 Administrator

Administrators have complete control over workspace management.

Capabilities include:

- Manage workspace members

- Assign or modify user roles

- Create projects

- Delete projects

- Delete tasks

- Manage permissions

- Full workspace administration

Administrators are the only users authorized to perform destructive operations within the workspace.

---

## 👨‍💼 Manager

Managers are responsible for coordinating project execution while operating within administrative boundaries.

Capabilities include:

- Invite users to workspaces

- Create projects

- Edit all project tasks

- Resolve workflow bottlenecks

- Coordinate team activities

Managers cannot perform destructive actions such as deleting projects or changing workspace ownership.

---

## 👨‍💻 Member

Members focus solely on task execution.

Capabilities include:

- Edit tasks assigned to themselves

- Update task progress

- Collaborate through comments

- Upload task attachments

If a member opens a task assigned to another user, the application automatically switches into **View Only Mode**, preventing unauthorized modifications.

---

## 🛡 Secure Backend Enforcement

Permission checks are enforced at the backend rather than relying solely on frontend restrictions.

Every API request undergoes permission validation to ensure users can only access resources explicitly granted to their assigned role.

This approach protects against unauthorized API requests and maintains strict workspace isolation.

---

# 🔄 End-to-End Workflow

## 1️⃣ Secure User Authentication

Users create an account or sign in using JWT-based authentication.

The backend validates credentials, issues secure access tokens, and initializes personalized user sessions.

---

## 2️⃣ Workspace Creation

Authenticated users create dedicated workspaces for organizing projects.

Examples include:

- Personal Projects

- Startup Teams

- Enterprise Development

Each workspace acts as an isolated collaborative environment.

---

## 3️⃣ Project Organization

Within each workspace, users create multiple projects to organize different goals and initiatives.

Projects become the central location for task management, collaboration, AI assistance, and team coordination.

---

## 4️⃣ Team Collaboration

Workspace administrators and managers invite members using the global searchable user interface.

The platform automatically applies workspace permissions based on assigned roles.

---

## 5️⃣ Task Planning

Tasks are created using either:

- Traditional task forms

- AI-powered natural language commands

Each task includes:

- Title

- Description

- Priority

- Due Date

- Assignee

- Subtasks

- Attachments

- Comments

---

## 6️⃣ Project Execution

Teams collaborate using:

- Kanban Boards

- Drag-and-drop task movement

- Comments

- Attachments

- Direct Messaging

Project progress updates instantly as tasks move across workflow stages.

---

## 7️⃣ AI Project Analysis

The AI Assistant continuously analyzes platform data and provides insights regarding:

- Project health

- Team workload

- Task priorities

- Deadlines

- Current blockers

- Resource allocation

Managers can ask questions in natural language and receive context-aware responses.

---

## 8️⃣ Team Health Monitoring

The Burnout Detector evaluates team workload using weighted scoring models.

If overload conditions are identified, the AI recommends workload redistribution before productivity is affected.

Result:

Project management becomes proactive rather than reactive, helping teams maintain balanced workloads while improving delivery efficiency.

---

# 🎨 Premium SaaS User Experience

The platform has been designed with a modern SaaS-first philosophy, delivering an intuitive and responsive experience for both individual users and collaborative teams.

Every interface has been optimized to minimize friction while maintaining enterprise-grade functionality.

### User Experience Highlights

- Responsive desktop and mobile layouts

- Modern dark-themed interface with premium typography

- Smooth page transitions and interactive UI elements

- Mobile-friendly messaging experience

- Slide-out sidebar navigation

- Clean dashboard organization

- Optimized Kanban workflow

- Searchable user selectors with debounced server-side search

- Context-aware AI interactions

- Real-time board updates after task creation

- Visual workload indicators with progress bars

- Role-aware interface rendering based on user permissions

The result is a polished experience that combines enterprise productivity with modern SaaS usability, allowing teams to collaborate efficiently while leveraging AI-assisted workflows.

---

# 📸 Platform Preview

## 1. Landing Page

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/59d7e965-f816-42c7-99f7-d3f388a8608b" />

---

## 2. Features of Website in Landing Page

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/4432b2b8-6789-41e0-a2f1-b385775fdf1b" />

---

## 3. Overview in Landing Page

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/777b46ee-ade5-4fcc-8238-5186f12b0064" />

---

## 4. RBAC Features in Landing Page

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/aa569f09-73a2-4508-836d-0a0271fc2e77" />

---

## 5. Sign In Page

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/1eb17dba-7936-47a2-a57d-c37b415ad6a7" />

---

## 6. Workspace Overview

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/bc55c060-080c-4f5d-a634-eb0128df91be" />

---

## 7. Projects Within a Workspace

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/7c5d2725-cc88-4a77-8be0-548c45ba10f4" />

---

## 8. Adding Project Members

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/8433d321-b508-4749-a976-f338c263f9dd" />

---

## 9. Natural Language Task Creation

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/ae6d7d31-c35a-4cc2-98ab-cd134ba03049" />

---

## 10. Creation of New Task

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/9aad77f1-4a28-428a-ba71-3828c3fef07b" />

---

## 11. Dragging and Dropping Tasks on the Kanban Board

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/10d14687-612f-4be2-a12d-f8992939be2f" />

---

## 12. Global Task Viewer

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/4e89c979-d450-4ce3-8b25-c9330f41836f" />

---

## 13. AI Assistant for Overall Project Summary

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/80171472-da02-4663-b47e-8b25ffd6ded9" />

---

## 14. Direct User Messaging

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/19bb664e-5654-47e2-a929-64e1c46f6cc0" />

---

## 15. Burnout & Team Health Detector

<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/b132eaec-5f9c-4197-bbef-85d552416139" />

---

# 💡 Key Engineering Concepts Demonstrated

- Software as a Service (SaaS) Architecture

- Multi-Tenant Workspace Management

- Enterprise Role-Based Access Control (RBAC)

- JWT Authentication & Authorization

- RESTful API Development with Django REST Framework

- PostgreSQL Database Design

- React-Based Single Page Application Development

- Secure User Authentication with Djoser

- Kanban-Based Project Management

- Drag-and-Drop User Interfaces

- Natural Language Processing for Task Creation

- Large Language Model (LLM) Integration

- AI-Assisted Project Analytics

- AI-Powered Workload Prediction

- Burnout Risk Detection

- Context-Aware AI Assistants

- Groq API Integration

- Meta Llama 3.3 Inference

- Real-Time Team Collaboration

- Global User Search & Assignment

- Scalable Workspace Organization

- Secure Permission Enforcement

- Backend Access Control Validation

- Threaded Task Discussions

- File Attachment Management

- Direct User Messaging

- Responsive SaaS UI/UX Design

- Mobile-First Interface Design

- Modern Dashboard Engineering

- Component-Based Frontend Architecture

- Enterprise Project Management Workflows

- AI-Augmented Productivity Systems

---

### 🚀 Built to showcase modern Full-Stack, SaaS, AI, and Enterprise Software Engineering practices.
