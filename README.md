# IndexedDB To-Do List

This project is a basic to-do list application that stores your to-dos directly in your web browser using IndexedDB. You can add, view, and delete to-do items.

**Features:**

*   **Add To-Dos:** Enter a title and description to add a new to-do.
*   **View To-Dos:** See all your saved to-dos in a list.
*   **Delete To-Dos:** Remove individual to-dos from the list.
*   **Persistent Storage:** Your to-dos are saved in your browser, so they'll be there even if you close the browser and come back later.
*   **No To-Do Message:** If you haven't added any to-dos yet, a "No Todo." message will be displayed.

**Prerequisites:**

1.  **Node.js and npm:** You need Node.js installed. npm (Node Package Manager) comes with it.
    *   Check if you have them by opening your terminal and typing:
        ```bash
        node -v
        npm -v
        ```
    *   If you don't have them, download and install Node.js from [https://nodejs.org/](https://nodejs.org/).

**How to Run (Using Git Clone):**

1.  **Clone the Repository:**
    *   Open your terminal or command prompt:
        ```bash
        git clone git@github.com:RoystonDAlmeida/indexed-db-demo.git
        ```

2.  **Navigate to the Project Folder:**
    *   Use the `cd` command to navigate into the newly created project folder:
        ```bash
        cd indexed-db-demo/
        ```

3.  **Install `http-server` (if you don't have it):**
    *   If you haven't used `http-server` before, you need to install it globally:
        ```bash
        npm install -g http-server
        ```

4.  **Start the Server:**
    *   In your terminal (still inside the project folder), start the server:
        ```bash
        http-server
        ```

5.  **Open in Browser:**
    *   Open your web browser and go to the address `http-server` gives you.

6.  **Stop the Server:**
    *   When you are done, press `CTRL+C` in your terminal to stop the server.

**Project Structure:**

The project has the following files:

*   `index.html`: The HTML for the to-do list.
*   `styles.css`: The CSS for the to-do list.
*   `index.js`: The JavaScript code that handles the to-do list logic and interacts with IndexedDB.

**How it Works:**

*   **`http-server`:** This tool creates a simple web server on your computer.
*   **IndexedDB:** This is a database built into your web browser. It's where your to-dos are stored.
*   **JavaScript:** The `index.js` file contains the code that interacts with IndexedDB and updates the to-do list on the page.