
#Smart HVAC with Reinforcement Learning Simulation

This project is an interactive, single-file web application that simulates a smart HVAC (Heating, Ventilation, and Air Conditioning) system controlled by a simplified reinforcement learning (RL) agent. The primary objective of the AI is to learn how to maintain an optimal room environment by balancing user comfort with energy efficiency.

The entire application is contained within a single index.html file, which makes it incredibly easy to deploy and share directly from a web server or GitHub Pages without any complex build steps.

Key Features
Real-Time Simulation: Observe how the room's temperature and humidity dynamically respond to environmental changes and the AI's actions.

Reinforcement Learning Agent: A simplified agent learns to make better decisions over time, aiming to maximize its "reward" by keeping the room comfortable while minimizing energy usage.

Performance Metrics: The interface provides a live view of key metrics such as cumulative reward, energy consumption, and the AI's learning progress.

Data Visualization: Custom SVG charts provide a clear, real-time visualization of temperature changes and the AI's learning curve, demonstrating the simulation's progress.

Fully Responsive Design: The application's layout is optimized to look and function perfectly on all devices, from desktop computers to mobile phones.

How to Run the Project
Due to its single-file structure, this project requires no installation or build process.

Running Locally
Clone or download this repository to your local machine.

Open the index.html file directly in any modern web browser.

Deploying with GitHub Pages
Ensure the index.html file is in the root directory of your GitHub repository.

Go to Settings > Pages.

Select the main branch as the deployment source and ensure the folder is set to / (root).

Save your changes. GitHub will automatically deploy your site, and a live URL will be provided.

Technologies Used
HTML: Provides the document structure.

React: A powerful JavaScript library for building the dynamic user interface.

Babel: Used for in-browser transpilation of modern React and JSX syntax.

Tailwind CSS: A utility-first framework for all styling and responsive design.

SVG: Utilized for creating lightweight, custom, and scalable data charts.

This project serves as a practical demonstration of modern web development and a conceptual model of AI in a real-world application.
