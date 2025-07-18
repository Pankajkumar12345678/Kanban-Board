# 📋 Kanban Task Management Application

A full-featured **Kanban application** for efficient task management and workflow visualization. This application supports user registration, login, task assignments, and a responsive, drag-and-drop interface for managing tasks across customizable boards and lists.

---

## 🌟 Features

- **🔐 User Authentication**
  - User registration and login/logout
  - Personalized dashboards and Kanban boards

- **🗂️ Kanban Boards**
  - Create multiple boards for different projects or workflows
  - Each board contains customizable lists and draggable cards

- **📝 Task Management**
  - Create cards with:
    - Titles
    - Descriptions
    - Due dates
    - File attachments
    - Assigned users
  - Move cards between lists using drag-and-drop functionality

- **🖱️ Drag and Drop**
  - Smooth drag-and-drop interface for reordering cards within and across lists

- **📱 Responsive UI/UX**
  - Works seamlessly across desktop, tablet, and mobile devices
  - Modern, clean, and intuitive design

---



### 📦 Installation

```bash
git clone https://github.com/Pankajkumar12345678/Kanban-Board.git
cd Kanban-Board
npm install
```

Create a `.env.local` file in the root directory with the following variables:
```bash
# MongoDB connection string
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/kanban

# JWT Secret for authentication
JWT_SECRET=your_jwt_secret

# Next.js environment variable
NEXT_PUBLIC_API_URL=http://localhost:3000
   
```

Run the development server:
```bash
npm run dev
```
