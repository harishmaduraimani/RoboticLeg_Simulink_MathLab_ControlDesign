# Robotic Leg Operation — MATLAB & Simulink

This subsystem models the **operation and control of a single robotic leg** using MATLAB and Simulink. It focuses on controlling leg-joint movement through a simplified dynamic model and PID-based feedback control.

## ⚙️ Operation

The subsystem receives a desired joint angle and compares it with the actual joint position.

```text
Desired Angle
      ↓
    Error
      ↓
 PID Controller
      ↓
  Joint Torque
      ↓
Robotic Leg Dynamics
      ↓
Actual Joint Angle
      ↺
   Feedback
```

## 🔧 Main Functions

* Generates the required joint movement.
* Models inertia, damping, and gravitational effects.
* Uses PID control for accurate position tracking.
* Provides feedback from the actual joint angle.
* Reduces steady-state error and unwanted oscillations.
* Can be integrated as one subsystem within a complete robotic-leg or robotic system.

## 🛠️ Tools

* **MATLAB**
* **Simulink**
* **PID Controller**
* **Mathematical Dynamic Modeling**

## 📌 Subsystem Role

This subsystem provides **controlled robotic-leg joint operation** and can be connected to higher-level trajectory planning or motion-control systems.
