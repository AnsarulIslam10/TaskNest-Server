# TaskNest

## 📝 Short Description  
**TaskNest** is a task management application that allows users to add, edit, delete, and reorder tasks using a drag-and-drop interface. Tasks are categorized into three sections: **To-Do, In Progress, and Done**. Changes are saved instantly to the database for persistence.

---

## 🚀 Live Links  
- **Live Demo:** [TaskNest Live](https://tasknest-d4a44.web.app)

---

## 🏗️ Technologies Used
- Node.js
- Express.js
- MongoDB
- CORS
- Dotenv


## 📦 Dependencies  
TaskNest Backend relies on the following dependencies:

- `cors ^2.8.5` – Enables Cross-Origin Resource Sharing  
- `dotenv ^16.4.7` – Loads environment variables  
- `express ^4.21.2` – Web framework for Node.js  
- `mongodb ^6.13.0` – MongoDB driver for database interaction  

---

## 🛠️ Installation  

### Prerequisites  
Ensure you have **Node.js** and **MongoDB** installed on your system.

### Steps  
1. **Clone the repository**  
   ```
   git clone https://github.com/AnsarulIslam10/TaskNest-Server.git
   ```
2. **Install dependencies**  
   ```
   npm install
   ```
3. **Set up environment variables**  
   Create a `.env` file in the root directory and add:  
   ```env
   DB_USER=your_database_username
   DB_PASS=your_database_password
   ```
4. **Add your MongoDB URI**
5. **Run the server with Nodemon** (for development)  
   ```
   nodemon index.js
   ```
---