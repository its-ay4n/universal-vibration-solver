# Universal Vibration Solver 🧮

A master analytical suite designed for mechanical engineering students and professionals to calculate, analyze, and optimize free damped vibration systems. This web application handles calculations in multiple directions, adapting to whether you have physical component specs, experimental graph data, or specific design targets.

## ✨ Core Analytical Engines

### 1. Forward Analysis (Physical Properties)
Calculates the complete dynamic behavior of a system based on known physical components.
*   **Inputs:** Mass ($m$), Stiffness ($k$), Damping Coefficient ($c$)
*   **Outputs:** Natural Frequency ($\omega_n$), Critical Damping ($c_c$), Damping Ratio ($\zeta$), Damped Frequency ($\omega_d$), Logarithmic Decrement ($\delta$), and System Regime classification.

### 2. Inverse Analysis (Experimental Data Solver)
Processes physical test data (like oscilloscope graphs) to uncover hidden mechanical properties using a multi-cycle Logarithmic Decrement algorithm.
*   **Inputs:** System Mass ($m$), Start Peak ($X_1$), End Peak ($X_n$), Number of Cycles ($n$), and Time ($t$).
*   **Outputs:** Extrapolates the exact Spring Stiffness ($k$) and Damping Coefficient ($c$) of the tested system.

### 3. Design Targeting (Frequency Wizard)
Acts as a reverse-engineering design assistant for component selection.
*   **Inputs:** Target Natural Frequency ($f_n$ in Hz) and one known physical parameter (either $m$ or $k$).
*   **Outputs:** Calculates the exact required value of the missing component to achieve the target resonant frequency.

## 🛠️ Technology Stack
*   **HTML5 / CSS3:** Modern, responsive "glassmorphism" dashboard interface.
*   **Vanilla JavaScript:** Lightweight, client-side mathematical computation engine requiring no backend processing.

## 👨‍💻 Developer

**SHEKH AYAN R.**  
*Mechanical Engineering*  
*Government Engineering College, Patan*

This project serves as a comprehensive mathematical companion to 3D kinematics and vibration simulations, bridging the gap between theoretical dynamics and applied mechanical design.
