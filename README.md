# Project Management App

https://github.com/user-attachments/assets/daf1f040-e43a-4c61-8664-fb840f27abce

The **Project Management App** is a web-based application designed to help users efficiently manage projects, tasks, and team collaboration. Built with a modern tech stack, it offers a user-friendly interface and robust functionality to streamline project workflows.

## Features

- **User Management**: Register, log in, and manage user profiles.
- **Project Management**: Create, edit, and delete projects; manage project members.
- **Task Management**: Add, update, and remove tasks; assign tasks to team members; set priorities and deadlines.
- **Gantt Charts**: Visualize project timelines and task dependencies.
- **Access Control**: Define user roles and permissions for secure collaboration.
- **Dashboard**: Overview of project status, task progress, and activity logs.

## Technology Stack

### Frontend

- **Framework**: Next.js
- **Language**: TypeScript
- **State Management**: Redux Toolkit
- **UI Components**: TailwindCSS

### Backend

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL

## Installation

### Prerequisites

- Node.js and npm installed
- PostgreSQL instance running

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Miran-Ahmad/project-management-app.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd project-management-app
   ```

3. **Install dependencies**:
   ```bash
   # For backend
   cd server
   npm install

   # For frontend
   cd ../client
   npm install
   ```

4. **Configure environment variables**:
   Create a `.env` file in the `server` directory with the following content:
   ```
   DATABASE_URL=your_postgres_connection_string
   PORT=your_port_number
   ```

5. **Start the application**:
   ```bash
   # Start backend
   cd server
   npm run dev

   # Start frontend
   cd ../client
   npm run dev
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.
