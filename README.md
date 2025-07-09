# DC Motor Speed Control using PID Controller (Simulink)

This project demonstrates a closed-loop speed control system for a DC motor using a manually implemented PID controller in MATLAB Simulink. It highlights fundamental control theory principles such as feedback, gain tuning, and system stability — all without using the Control System Toolbox.

---

## 🎯 Objective

To simulate a DC motor system using a first-order transfer function and design a PID controller (built from basic blocks) that ensures the motor accurately tracks a desired speed setpoint.

---

## 🧰 Tools & Techniques Used

- **MATLAB Simulink** (Trial Version)
- **Transfer Function Modeling**
- **Manual PID Implementation** using:
  - Gain blocks (Proportional, Integral, Derivative)
  - Integrator & Derivative blocks
- **Scope** for output visualization
- **Step input** to simulate setpoint changes
- **Feedback loop** for error correction

---

## 🔧 PID Tuning Values

After several test iterations, the final gains used are:
- **P (Proportional)** = 5  
- **I (Integral)** = 8 
- **D (Derivative)** = 0.1

These values ensured:
- Quick rise time
- Minimal overshoot
- Steady-state error ≈ 0

---

## 📈 Simulation Result

The motor speed smoothly reaches the desired value of **10 rad/s** with good transient response and zero steady-state error.

*You can view the simulation result in the attached Scope screenshot.*

---

## 📁 Files in This Repository

- `dc_motor_pid_manual.slx` – Simulink model file
- `scope_output.png` – Screenshot of motor speed response
- `README.md` – Project description

---

## ✍️ Author

**Sadaf Tanvir**  
Electrical and Electronics Engineering Student  
MATLAB & Simulink , Control Systems Learner

---

## 📜 License

This project is for  learning purposes only. You are free to reference, modify, or build upon it for non-commercial use.
