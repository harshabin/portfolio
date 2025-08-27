# Harsha Vardhan.n - Personal Portfolio 

Welcome to the source code for my personal portfolio website. This project was built from the ground up not just as a portfolio, but as a comprehensive showcase of modern full-stack development.


<img width="1920" height="925" alt="image" src="https://github.com/user-attachments/assets/9bf7b102-62a3-414f-b08b-f68c048f9eeb" />


**Live Demo:** [**harsha's.vercel.app**](https://portfolio-fr39.vercel.app/)

---

## ✨ Features

This portfolio is a fully interactive, single-page application (SPA) with a focus on modern UI/UX and creative animations.

- **Dynamic Hero Section:** Features a multilingual greeting changer and an auto-typing effect, all managed with React hooks (`useEffect`, `useState`).
- **Interactive Background:** Includes multiple roaming animated elements (`ghost`, `spacecraft`) and a `tsParticles` background for a lively, space-themed feel.
- **Scroll Snapping & Full-Screen Layout:** Each section snaps to the viewport for a clean, app-like scrolling experience.
- **Responsive Design:** A custom mobile-first layout ensures a great user experience on all devices, from phones to desktops.
    - Includes a slide-in "hamburger" menu for mobile navigation.
    - Swaps complex desktop animations for clean, performant mobile layouts.
- **"Solar System" Project Showcase:** A unique, interactive way to display projects using pure CSS for orbits and animations. Planets pause on hover to reveal project info.
- **Flip-Card Education Timeline:** Education history is displayed on interactive 3D flip cards on desktop and clean, simple cards on mobile.
- **Functional Contact Form:** A live contact form integrated with Formspree that sends submissions directly to my email.
- **MERN Architecture:** Built with a separate Node.js/Express backend and a React frontend, making the application scalable and ready for future database integration.

---

## 💻 Tech Stack

This project leverages a wide range of modern web technologies to create a performant and maintainable application.

-   **Frontend:**
    -   **React.js:** For building the dynamic user interface.
    -   **Vite:** As the next-generation frontend tooling for a fast development experience.
    -   **CSS3:** For all styling, including advanced animations, Flexbox, and Grid layouts.
    -   **Libraries:** `react-tsparticles`, `@fortawesome/react-fontawesome`.

-   **Backend:**
    -   **Node.js:** As the JavaScript runtime environment.
    -   **Express.js:** For the server framework (prepared for API expansion).
    -   **CORS:** To handle cross-origin requests between the client and server.

-   **Deployment & Version Control:**
    -   **Vercel:** For seamless, automated deployment of the frontend and serverless backend.
    -   **Git & GitHub:** For version control and source code management.

---

## 🚀 Getting Started

To run this project on your local machine, please follow these steps.

### Prerequisites

-   **Node.js:** Make sure you have a modern version of Node.js installed (v18.x or v20.x recommended). You can use [nvm](https://github.com/nvm-sh/nvm) or [NodeSource](https://github.com/nodesource/distributions) to manage versions.
-   **Git:** You will need Git installed to clone the repository.

### Local Setup & Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/punithbr27/portfolio.git
    cd portfolio
    ```

2.  **Install Backend Dependencies:**
    ```bash
    cd server
    npm install
    ```

3.  **Install Frontend Dependencies:**
    ```bash
    cd ../client
    npm install
    ```

4.  **Set Up Environment Variables:**
    This project uses Formspree for the contact form. You'll need your own Formspree endpoint. Create a file named `.env` in the `client` directory if you wish to manage any frontend environment variables.

### Running the Application

You will need to run both the frontend and backend servers concurrently in separate terminals.

1.  **Start the Backend Server:**
    -   Open a terminal in the `/server` directory.
    -   Run the command:
        ```bash
        node index.js
        ```
    -   The server will be running on `http://localhost:5000`.

2.  **Start the Frontend Development Server:**
    -   Open a *second* terminal in the `/client` directory.
    -   Run the command:
        ```bash
        npm run dev
        ```
    -   Open your browser and navigate to `http://localhost:5173` to see the application live.

---

## 📞 Contact

Punith BR - [@LinkedIn](https://www.linkedin.com/in/punith-br/) - punithawesome123@gmail.com
