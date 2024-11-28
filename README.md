Kanban Board with Drag-and-Drop
Description
This project is a Kanban board built with React, TypeScript, and drag-and-drop functionality using the @dnd-kit/core library. It allows users to manage tasks by dragging and dropping them across different columns, providing a smooth, interactive experience.

Features
Create, update, and delete columns and tasks.
Drag and drop tasks between columns.
Persistent state with local storage (tasks and columns).
Responsive design and keyboard accessibility.
Setup Instructions
Prerequisites
Ensure you have the following tools installed:

Node.js (LTS version recommended)
npm or yarn
Installation
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <project-directory>
Install dependencies:

If you’re using npm:

bash
Copy code
npm install
Or if you’re using yarn:

bash
Copy code
yarn install
Run the application locally:

Start the development server:

bash
Copy code
npm start
Or:

bash
Copy code
yarn start
The application should now be running at http://localhost:3000.

Technology Choices and Rationale
React
We chose React due to its efficiency in handling dynamic and interactive UIs, making it an ideal choice for a Kanban board application.

TypeScript
TypeScript was used to provide static typing, making the development process more robust and less prone to runtime errors. This also improves the maintainability of the project.

@dnd-kit/core
The drag-and-drop functionality is implemented using the @dnd-kit/core library, which is highly customizable and provides a great user experience for drag-and-drop interactions. It is lightweight and doesn’t add unnecessary complexity to the application.

Local Storage
Local Storage is used to persist the state of columns and tasks, so even after a page refresh, the user can continue working where they left off.

Known Limitations/Trade-offs
Limited drag-and-drop customization: The current drag-and-drop implementation provides basic functionality but doesn’t support advanced features like snapping or conditional dragging.

No backend integration: The data persistence is handled locally in the browser using localStorage. There is no server-side storage, meaning that if the browser’s local storage is cleared, the data will be lost.

Responsiveness: While the board is functional on mobile and desktop, some minor UI tweaks might be needed for smaller screens.

Live Demo Link
You can view a live demo of the Kanban board https://vritinternkanbanboard.netlify.app/.

Future Improvements
Backend Integration: Implement a backend using a service like Firebase or a custom REST API to store columns and tasks persistently across devices.

Authentication: Adding user authentication to enable personalized boards and tasks for multiple users.

Enhanced Drag-and-Drop Features: Implement features like task prioritization, task snapping, or drag-and-drop between multiple boards.




Time Spent on the Project
Initial Setup: 20 min
Drag-and-Drop Implementation: 2 hours
TypeScript Integration: 1 hours
Local Storage Persistence: 1 min
UI/UX Design: 1 hours
Documentation (README): 1 hours
Total Time Spent: 4 hour 21min
