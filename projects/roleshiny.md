---
layout: project
type: project
image: img/roleLogo.png
title: "RoLE Model GUI"
date: 2025
published: true
labels:
  - R
  - Shiny
  - GUI
  - Data Visualization
summary: "An R Shiny-based interface that visualizes complex eco-evolutionary simulations from the RoLE Model"
---

### Overview
The **RoLE Model Graphical User Interface (GUI)** was developed to make an existing eco-evolutionary simulation model accessible to researchers and students without programming or command-line experience.  
Originally, running the model required manual input and interpretation of raw, unformatted output data. Our team’s goal was to create an **interactive, visual front end** that would present the results clearly and intuitively, allowing users of all skill levels to explore biodiversity dynamics through simulation.

---

### Purpose
The GUI, built with **R Shiny**, enables users to adjust key simulation parameters—such as speciation rate and dispersal probability—through interactive sliders. After setting the parameters, users can run simulations with a single click. The interface then generates two synchronized graphs representing biodiversity data over time, accompanied by a timeline slider that lets users move through different generations and observe how species abundance and traits evolve.

This transformation of command-line output into an interactive visualization significantly improves the usability and accessibility of the RoLE Model for educational and research purposes.

---

### Tech Stack and Frameworks
- **R** – Primary language powering the GUI and model integration  
- **Shiny** – Web framework providing interactivity and layout  
- **ggplot2** and **plotly** – Data visualization and graph animation tools  
- **dplyr** – Efficient data manipulation and formatting of simulation results  
- **shinyBS** – Interface enhancements and tooltips for better usability  

---

### My Contributions
- Implemented **dynamic graph generation and animation** using ggplot2 and plotly to visualize simulation results
- Created the interactive simulation controls such as the parameter sliders and run button
- Developed the logic to **consolidate all slider inputs into a single parameter object**, which was then passed into the RoLE Model for simulation  
- Ensured that the model **returned accurate and synchronized data** based on user-defined parameters  
- Collaborated closely with teammates to integrate front-end components with the existing backend simulation model  

---

### Features
- Real-time simulation control via parameter sliders  
- Automated generation of animated, interactive biodiversity graphs  
- Timeline slider to visualize results across generations  
- Accessible design for both researchers and students  

---

### Skills Gained
- R programming and Shiny application development  
- Data visualization using ggplot2 and plotly  
- Understanding and integrating existing codebases  
- Collaboration and problem-solving in interdisciplinary projects  

---

### Biggest Challenge
The biggest challenge was **deciphering and integrating the existing RoLE Model code**, which was written entirely in R—a language none of us had prior experience with. Understanding the model’s structure and logic was essential to ensure that our GUI communicated with it correctly and returned accurate simulation results. Overcoming this learning curve taught us how to work effectively with unfamiliar technologies and complex scientific codebases.

---

### Summary
This project focused on building an accessible, interactive interface for the **RoLE eco-evolutionary model**, transforming a command-line research tool into an intuitive visualization platform. By combining R’s analytical capabilities with Shiny’s interactivity and ggplot2’s dynamic visualizations, our team made complex biodiversity simulations approachable for a wider scientific audience.

---

### Source Code
- [GitHub Repository](https://github.com/role-model/roleShiny/tree/dev-prayag-das)
