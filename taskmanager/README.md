# 📝 Laravel Task Management Application

This is a **simple Laravel web application** for **managing tasks** with project-based filtering.  
Users can **create, edit, delete, and reorder tasks with drag-and-drop functionality**.

---

## 📌 Features:
✔ Create, Edit, Delete Tasks  
✔ Drag & Drop Reordering (Auto-updates priority)  
✔ Tasks Linked to Projects  
✔ Store & Retrieve Data from MySQL  
✔ API Endpoints Available  

---

## 📌 Requirements:
Before running the application, ensure you have the following installed:

1. [XAMPP](https://www.apachefriends.org/download.html) (for Apache & MySQL)
2. [Composer](https://getcomposer.org/) (for Laravel dependencies)
3. [Node.js](https://nodejs.org/) (for frontend dependencies, if needed)
4. Laravel (Installed via Composer)
5. Update the database details in the `.env` file.

---

## 📌 Project Structure:
📂 app/
├── Http/Controllers/
│   ├── ProjectController.php   # Handles project creation & retrieval
│   ├── TaskController.php      # Handles CRUD operations for tasks
│
├── Models/
│   ├── Project.php             # Defines project model
│   ├── Task.php                # Defines task model
│
📂 database/
├── migrations/                 # Table structures for projects and tasks
├── seeders/                    # Adds default test data
│
📂 routes/
├── api.php                     # Defines API endpoints for tasks & projects
│
📂 resources/views/
├── welcome.blade.php           # Frontend UI (Dropdown, task list, JavaScript interactivity)
│
📂 public/
├── css/                        # Frontend styles
├── js/                         # Frontend scripts
