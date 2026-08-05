# Investigation Influences of Pulling Speed on Stripe Pattern Formation of Peeled Tape

 **National Chung Cheng University | Final Project for Experiments on Fundamental Physics 2B | 2026 Joint Physics Education Meeting of ROC**

##  About The Project

This project features a web-based **Interactive Physics Simulator** designed to visualize the dynamic behavior and stripe pattern formation that occurs when transparent tape is peeled off at varying speeds. 

The simulation allows users to adjust the pulling speed (via step delay) and observe the real-time transition of the tape's adhesive state, bridging the gap between theoretical macroscopic dynamics and microscopic polymer physics.

##  Key Features

*   **Interactive Simulation Console:** A visual representation of the mechanical setup, including a motor, cart, pulleys, and a tape dispenser.
*   **Adjustable Pulling Speed:** Users can input a "Step Delay" (in milliseconds) to control the speed of the motor. The system dynamically calculates and displays the resulting pulling speed in `mm/s`.
*   **Real-time Micro-Camera View:** A simulated camera feed that visualizes the stripe patterns left on the tape based on the current peeling speed.
*   **Dynamic State Transitions:**
    *   **Low Speed (High Delay):** Generates a continuous solid **White Zone**.
    *   **High Speed (Low Delay):** Generates a nearly clear **Transparent Zone**.
    *   **Intermediate Speed:** Simulates the periodic **Stick-Slip** instability, generating alternating white and gray/transparent stripes.

## Physics Concepts Demonstrated

The simulator visualizes the two primary states of polymer adhesive during peeling:

1.  **White Zone (Stick):** 
    An opaque band caused by polymer fibrillation. At lower speeds, the polymer chains have time to stretch and deform (rubbery state), creating microscopic fibrils that scatter light and appear white.
2.  **Transparent Zone (Slip):** 
    A clear band resulting from rapid, clean detachment. At higher speeds, the adhesive undergoes brittle fracture (glassy state) due to lack of relaxation time, leaving a flat, transparent surface.

##  How to Use

1.  Clone or download this repository to your local machine.
2.  Ensure all image assets (`bg1.png`, `bg2.png`, `cart.png`, `pulley-bottom.png`, `wheel.png`, etc.) are located in the same directory as the HTML file.
3.  Open `index.html` in any modern web browser (Google Chrome, Firefox, Safari, Edge).
4.  In the **Simulation Console**, enter a numerical value in the **Step Delay** input field.
5.  Click **Start** to run the simulation and observe the mechanical movement and the resulting tape patterns in the **Micro-Camera** panel.

## Team & Credits


*   **Researchers:** Chang-yu Wu, Zheng-Da Tsai, Zhung-Rui Zhang
*   **Advisor:** Prof. Pi-Hui Tuan
*   **Institution:** National Chung Cheng University
*   **Event:** Prepared for the 2026 Joint Physics Education Meeting of ROC

---
*© 2026 Chang-Yu Wu, Zheng-Da Tsai, and Zhung-Rui Zhang. All rights reserved.*
