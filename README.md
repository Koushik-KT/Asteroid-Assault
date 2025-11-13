# 🚀 Asteroid Assault: The Cosmic Collector PWA

> **Live Demo:** https://koushik-kt.github.io/Asteroid-Assault/


A fully responsive, retro-style arcade shooter game where you pilot a spacecraft to collect stars and dodge enemy fire and asteroids built using pure HTML5 Canvas and JavaScript. This project showcases proficiency in core web development fundamentals, persistent data management, and Progressive Web Application (PWA) architecture. It features a persistent global leaderboard powered by Firebase and supports offline play.

---

## ✨ Key Technical Features

This project was developed to demonstrate expertise in the following areas:

| Feature | Technology Demonstrated | Resume Value |
| :--- | :--- | :--- |
| **Real-Time Database** | **Google Firebase/Firestore** | Implemented asynchronous functions to save user scores and load the **persistent global leaderboard** in real-time. |
| **Offline Functionality (PWA)** | **Service Workers, Web Manifest** | Configured the application as a PWA, registering an embedded Service Worker to enable **full offline gameplay** and device installation. |
| **Core Game Engine** | **HTML5 Canvas, Vanilla JavaScript** | Custom-built the entire game loop, object physics (movement, spawning), and state management (`menu`, `running`, `gameover`) without external game libraries. |
| **Frame-Rate Independence**| **Delta Time (ΔT) Calculation** | Implemented a reliable `deltaTime` logic in the main loop, ensuring game speed remains constant regardless of the user's device performance. |
| **Responsive Input** | **Touch/Mouse Handlers** | Designed the player control system to respond accurately to both mouse movement (desktop) and touch swipes (mobile). |
| **Secure Authentication** | **Firebase Auth Integration** | Handled user authentication (anonymous/custom token) to securely link high scores to a unique user ID. |

---

## 🎮 How to Play

1.  **Pilot:** Control the ship's horizontal position using your mouse cursor or by dragging your finger across the bottom of the screen.
2.  **Objective:** Collect the **Yellow Stars** (10 points each).
3.  **Dangers:** Avoid the **Orange Asteroids** and **Magenta Enemy Ships/Projectiles**. Collisions cost lives.
4.  **Lives:** You start with 3 lives. Colliding with an enemy ship is instant game over.
5.  **Install:** This game is a PWA! You can install it directly onto your desktop or mobile device for a dedicated, offline experience.

## ⚙️ Setup and Deployment

This is a static web application that can be deployed instantly.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Koushik-KT/Asteroid-Assault/
    ```
2.  **Open:** Open `index.html` directly in your browser, or deploy the files to **GitHub Pages** (recommended for live demo).

---
*Developed by Koushik Tripathy • November 14 2025*
