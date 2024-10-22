# Barracuda Marine - Fishing Equipment Store

Welcome to **Barracuda Marine**, an innovative online platform specializing in fishing equipment, designed for professional and amateur fishermen alike. This repository contains the codebase for developing the **Barracuda Marine** web application, utilizing a visually immersive experience with interactive elements and an intuitive circular design.

## Project Overview

The **Barracuda Marine** web app is built to offer a seamless and engaging experience for users, featuring:

- **Circular Design**: The application utilizes an interactive central circular layout where products and models move around a main central circle. This provides an intuitive browsing experience for users.
- **Fishing Equipment Simulation**: The application includes an interactive simulation feature where users can explore different fishing gear combinations.
- **3D Visuals and Animations**: Products are represented with detailed imagery, animated within the circle for smooth transitions.
- **Voice Navigation**: Users can interact with the website using voice commands, enhancing accessibility.

## Technologies Used

This project is built using modern web development technologies to ensure high performance and smooth user experience:
- **Next.js** for the frontend framework
- **React** for UI components
- **Framer Motion** and **Three.js** for animations and 3D interactions
- **Prisma** and **PostgreSQL** for database management
- **Google OAuth** for authentication
- **Dialogflow** for AI voice assistant integration
- **Node.js** for backend logic

## Features

### 1. Home Page
The home page presents an immersive layout featuring:
- A 3D Barracuda fish skeleton animation at the center.
- Circular navigation buttons for quick access to pages like **Products**, **Offers**, **Rewards**, etc.
- An inspiring call to action: "دش بحر باراكودا" (Dive into Barracuda Sea).

### 2. Product Page
- Central product focus: When a product is selected, it moves to the center with detailed specifications, pricing, and availability displayed around it.
- Model Exploration: Surrounding the product are smaller circles representing different models with animations for smooth transitions between models.
- Add to Cart: Easily add products to the cart from the product page.

### 3. Fishing Gear Simulation
- Users can select different fishing rods, reels, and lines to see specifications on either side of the screen.
- The simulation provides an interactive experience allowing users to explore various combinations.
- The layout reverts back to the original circle-based design once the simulation is completed.

## Getting Started

### Prerequisites
Make sure you have the following tools installed:
- Node.js
- npm or yarn
- PostgreSQL

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/username/barracuda-marine.git
