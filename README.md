# Project Priority Board – Blazor Application

A simple **project priority board** built with **Blazor (Razor Components)**.  
The application demonstrates component-based UI design, parent–child communication, and dynamic list reordering to simulate basic project management workflows.

---

## 🚀 Features

- 📋 **Project Cards**
  - Display project name, deadline, and status
  - Clear visual status indicators

- 🔼🔽 **Priority Reordering**
  - Move projects up and down the list
  - Buttons are conditionally rendered based on position
  - Prevents invalid actions for first and last items

- 🎨 **Conditional Styling**
  - Active projects are visually highlighted
  - Different styles for Planning and On Hold statuses

- 🧩 **Component-Based Architecture**
  - Reusable `ProjectCard` component
  - Clean separation of UI and logic

- 📖 **About Page**
  - Explains the project management approach
  - Describes how a priority board supports development teams

---

## 🛠 Technologies Used

- **Blazor (Razor Components)**
- **C#**
- **EventCallback**
- **Conditional Rendering**
- **CSS for styling**

---

## 🔄 How It Works

- The `Home` component maintains a list of projects
- Each project is rendered using a `ProjectCard` component
- `EventCallback` is used to notify the parent when a card requests to move
- Project order updates dynamically based on user interaction
- Buttons are shown or hidden depending on the card’s position in the list

---

## 🎯 Learning Goals

This project was created to practice and demonstrate:

- Blazor component communication
- Passing parameters and callbacks
- Managing state in a parent component
- Conditional rendering and styling
- Building interactive UI without JavaScript

---

## 📌 Notes

- The project uses an in-memory list (no database)
- Designed as a learning and portfolio project
- Easily extendable with persistence, drag & drop, or authentication

---

## 👨‍💻 Author

Final-year **Game Development student**  
Learning **Blazor and ASP.NET** with a focus on clean architecture, UI logic, and interactive components.

---

## 📄 License

This project is intended for educational and portfolio use.
