
# Keeper App

Keeper App is a React-based application that mimics a simple note-keeping tool. It allows users to add and delete notes dynamically. The project is designed to provide hands-on experience with React concepts such as functional components, hooks, and state management.

----------

## Features

-   **Add Notes:** Users can add a new note by entering a title and content, then clicking the "Add" button.
-   **Delete Notes:** Each note has a delete button that removes it from the list.
-   **Dynamic UI Updates:** The app updates in real-time without requiring a page refresh.

----------

## Learning Outcomes

While building this app, the following React concepts were learned and applied:

1.  **Functional Components:**
    
    -   Used functional components for modular and reusable code structure.
    -   Components include `App`, `Header`, `Footer`, `Note`, and `CreateArea`.
2.  **React Hooks:**
    
    -   Leveraged the `useState` hook for state management.
    -   Example: Maintaining the list of notes and input field states.
3.  **Component State:**
    
    -   Implemented local component states to handle user input and dynamic changes in the app.
4.  **Props:**
    
    -   Passed data between components using props for effective communication.

----------

## Technologies Used

-   **React**: Front-end library for building user interfaces.
-   **JavaScript (ES6+)**: For application logic.
-   **CSS**: For styling the components.

----------

## Installation and Usage

1.  Clone the repository:
    
    ```bash
    git clone https://github.com/sheftechdad/keeper-app.git
    
    ```
    
2.  Navigate to the project directory:
    
    ```bash
    cd keeper-app
    
    ```
    
3.  Install dependencies:
    
    ```bash
    npm install
    
    ```
    
4.  Start the development server:
    
    ```bash
    npm run dev
    
    ```
    
5.  Open the app in your browser:
    
    ```
    http://localhost:5173
    
    ```
    

----------

## File Structure

```
keeper-app/
├── src/
│   ├── components/
│   │   ├── App.jsx
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── Note.jsx
│   │   └── CreateArea.jsx
│   ├── index.js
│   └── styles.css
├── package.json
└── README.md

```

----------

## Future Enhancements

-   Add user authentication to save notes for specific users.
-   Implement categories or tags for better organization of notes.
-   Allow editing of existing notes.

----------
