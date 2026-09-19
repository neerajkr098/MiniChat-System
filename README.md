# MongoMessenger 💬

A lightweight, full-stack chat application built with **Node.js, Express, and MongoDB**. 

This project demonstrates core backend web development concepts including RESTful routing, MVC architecture, MongoDB database operations (CRUD), and server-side rendering with EJS.

## 🚀 Features

*   **View Chats:** See a timeline of all messages between users.
*   **Create Chats:** Send new messages specifying the sender, receiver, and content.
*   **Edit Chats:** Update existing messages.
*   **Delete Chats:** Remove messages from the database.
*   **Modular Styling:** Clean, lightweight UI with separate CSS files for each view to keep the codebase organized.
*   **Error Handling:** Asynchronous route handling for robust database interactions.

## 🛠️ Technologies Used

*   **Backend:** Node.js, Express.js
*   **Database:** MongoDB, Mongoose (ODM)
*   **Frontend Views:** EJS (Embedded JavaScript templating), HTML5, CSS3
*   **Routing:** RESTful API design, `method-override` for PUT and DELETE requests

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <your-repository-url>
   cd mongoDB-EXPRESS
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start MongoDB:**
   Make sure your local MongoDB server is running on `mongodb://127.0.0.1:27017`.

4. **Seed the database (Optional):**
   If you want to start with some dummy data, run the initialization script:
   ```bash
   node init.js
   ```

5. **Start the server:**
   ```bash
   node index.js
   ```
   The server will start listening on port `8080`.

6. **View the app:**
   Open your browser and navigate to `http://localhost:8080/chats`
