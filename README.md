# Drawing App

## Description

The Drawing App is an interactive platform where users can collaborate in real-time by drawing and writing on a shared canvas. The host creates a room with a unique ID, and other participants can join by providing their name and the room ID. The host can use the canvas to explain ideas, draw shapes, and annotate for others to see. The app leverages Rough.js for hand-drawn shapes, React.js for the user interface, and Socket.io for seamless real-time communication. This project aims to provide a simple and intuitive tool for creative collaboration.

## Features

- Room Creation & Joining: Hosts can create a room with a unique ID, and others can join by providing their name and the generated room ID.

- Real-Time Collaboration: Multiple users can draw and interact on the same canvas in real-time.

- Hand-Drawn Shapes: Hosts can draw shapes and write text using Rough.js, simulating hand-drawn annotations.

- Notifications: Users receive real-time notifications for various actions, such as when someone joins or leaves the room, using Toast.

- Responsive Design: The app is fully responsive, ensuring a smooth experience across devices, styled using Bootstrap.

- Live Connection: Socket.io ensures seamless and low-latency connection sharing for smooth collaboration.

- Simple Backend: The backend is built with Node.js and Express, handling room creation and user connections with ease.

- Cross-Origin Resource Sharing: CORS is used to handle requests between the frontend and backend securely.

## Prerequisites

Make sure you have the following installed:

- Node.js (for running the backend server)

- Yarn (for managing dependencies)

- Browser (for accessing the frontend UI)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/drawing-app.git
   ```
