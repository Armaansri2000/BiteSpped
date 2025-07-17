# 💬 Chatbot Flow Builder

This project was developed as part of the BiteSpeed Frontend Task. The goal was to build a lightweight and modular chatbot flow builder using **React** and **React Flow**. Users can visually create chatbot workflows by dragging and connecting message nodes. I’ve also added basic **responsive design** so it functions well on mobile devices.

**Tech Stack:** ReactJS, Tailwind CSS, React Flow, React Icons, React Toastify, React Hooks

🔗 **Live Demo:** ---  https://stellular-sable-9bf6a7.netlify.app/

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Code Structure](#code-structure)
- [Components](#components)
- [Future Improvements](#future-improvements)
- [Contact Details](#contact-details)

---

## 🧩 Overview

The Chatbot Flow Builder is a drag-and-drop interface that allows users to visually map out chatbot conversations. It supports adding message nodes, connecting them with edges, and editing content directly via a settings panel. Built on top of React and React Flow, it provides a clean and interactive experience for flow creation.

---

## 🚀 Features

1. **Text Nodes**
   - Easily create and position message nodes on the canvas.
   - Add multiple nodes to form complex flows.

2. **Drag-and-Drop Node Panel**
   - Displays all available node types.
   - Drag items from the panel into the workspace to create them.

3. **Edge Connection**
   - Create connections between nodes with arrows (edges).
   - One outgoing edge per source node is enforced to maintain clarity.

4. **Handles**
   - **Source Handle:** Allows initiating one connection.
   - **Target Handle:** Accepts multiple incoming connections.

5. **Settings Panel**
   - Appears when a node is selected.
   - Lets you modify the text inside that specific message node.

6. **Flow Validation + Save**
   - Save the chatbot flow with one click.
   - Displays validation errors for unconnected nodes during save attempts.

---

## ⚙️ Installation

To run the project locally:

```bash
git clone https://github.com/yourusername/chatbot-flow-builder.git
cd BitWise-Frontend-Task


## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   
   ``` bash
   git clone https://github.com/yourusername/chatbot-flow-builder.git
   cd BitWise-Frontend-Task
   ```
2. Install the dependencies:
   
   ``` bash
   npm install
   ```
3. Start the development server:
   
   ``` bash
   npm run dev
   ```

