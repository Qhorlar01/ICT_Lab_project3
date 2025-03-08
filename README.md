# Three-Phase Induction Motor Control via Indirect Field Orientation  
*Sensorless Speed and Torque Control for Squirrel Cage Induction Motors*  
---

##  Description  
This project implements **indirect field-oriented control (IFOC)** for a three-phase squirrel cage induction motor, inspired by [Waner Wodson's tutorial]. The goal is to achieve precise speed and torque control without direct rotor flux measurement by leveraging:  
- **Slip calculation** based on quadrature/direct (DQ) current decomposition.  
- **Encoder feedback** for mechanical speed measurement (RPM or rad/s).  
- **Space Vector PWM (SVPWM)** for synthesizing three-phase voltages.  
- **PI controllers** for closed-loop current and speed regulation.  

The project includes simulation models (PLECS/PSIM) and DSP code for Texas Instruments C2000 microcontrollers.  

---

##  Key Features  
- **Indirect Field Orientation Control (IFOC)**: Sensorless flux estimation via slip calculation.  
- **DQ Transformation**: Clarke/Park transforms for ABC to DQ current decomposition.  
- **Encoder Integration**: Quadrature encoder for real-time rotor speed feedback.  
- **SVPWM Modulation**: Efficient three-phase voltage synthesis.  
- **Simulation & Validation**: PLECS/PSIM models for a 6-pole motor with asynchronous speed validation.  
