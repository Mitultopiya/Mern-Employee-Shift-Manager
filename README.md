# Employee Shift Management App

**Employee Shift Management App** is a fullstack web application designed to streamline and centralize employee scheduling. Built with a modern React frontend and an Express/MongoDB backend, the app offers a seamless interface for creating, updating, and tracking employee shifts in a collaborative environment.

## Admin Pages

|            Dashboard (View Mode)             |            Dashboard (Edit Mode)             |
| :------------------------------------------: | :------------------------------------------: |
| ![](./images/DashboardViewMode.png?raw=true) | ![](./images/DashboardEditMode.png?raw=true) |

|            Create a New Shifts             |              View Statistics              |
| :----------------------------------------: | :---------------------------------------: |
| ![](./images/CreateNewShifts.png?raw=true) | ![](./images/ViewStatistics.png?raw=true) |

|          Create a New Team Member          |         View and Edit Team Members         |
| :----------------------------------------: | :----------------------------------------: |
| ![](./images/CreateNewMember.png?raw=true) | ![](./images/ViewAndEditTeam.png?raw=true) |

## User Pages

|                Dashboard                 |              View Statistics              |
| :--------------------------------------: | :---------------------------------------: |
| ![](./images/UserDashboard.png?raw=true) | ![](./images/UserStatistics.png?raw=true) |

## 🚀 Features

- 📅 **Drag-and-Drop Calendar Interface** powered by **ScheduleX**
- 🌍 **Timezone-Aware Scheduling** with `moment-timezone`
- 🔐 **JWT-based Authentication and Authorization**
- 📊 **Interactive Charts and Statistics** using **Recharts**
- 🧠 **Smart Shift Visualization** and management tools
- 💡 **Fully Responsive Design** with **Tailwind CSS**
- ⚙️ RESTful API with secure endpoints for user and shift data

## 🧱 Tech Stack

### Frontend

- **React 19** + **React Router 7**
- **Tailwind CSS 4**
- **ScheduleX Calendar Suite**
- **Recharts**
- **Axios** for API communication
- **Vite** for blazing-fast development
- **React Compiler** for optimize React applications

### Backend

- **Express.js** (v5)
- **MongoDB + Mongoose**
- **JWT** for authentication
- **dotenv** for environment configuration
- **bcryptjs** for password hashing
- **moment-timezone** for accurate time tracking

### ERD Diagram

![](/images/erd-diagram.png?raw=true)

## 📦 Installation

### Clone the Repository

```bash
git clone https://github.com/Mitultopiya/Mern-Employee-Shift-Manager.git
cd mern-employee-shift-manager
```

### Backend Setup

```bash
cd backend
npm install
cp .env.example .env   # Add your Mongo URI and JWT secret here
npm start
```

### Frontend Setup

```bash
cd ../frontend
pnpm install
pnpm dev
```

