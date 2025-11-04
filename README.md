# Class-D-amplifier
All the files related to the circuit can be found here
# Overview
This project focuses on designing and simulating a Class D audio amplifier, a highly efficient switching amplifier that converts an analog input signal into a pulse-width modulated (PWM) output. The amplifier then reconstructs the amplified analog signal using a low-pass LC filter. Class D amplifiers are known for their impressive efficiency—often exceeding 90%—and their ability to deliver high power output with minimal heat dissipation, making them ideal for compact and battery-powered system.
# Design approach
The design process began with studying the working principles of Class D amplifiers—specifically how analog signals are converted into PWM waveforms and then filtered back into amplified audio. I chose to use Proteus as the simulation platform because it offers a good balance between circuit analysis and waveform visualization, which helped me observe both the PWM generation and the filtered output waveforms in real time. My goal was to achieve a clean, stable signal conversion using discrete transistors for the modulator stage and an op-amp for feedback and correction.
Once the circuit simulation was successfully tested in Proteus, I moved on to preparing the PCB layout using KiCad. This step helped translate the theoretical design into a practical hardware layout while optimizing component placement and trace routing for signal integrity. The focus was on keeping the design compact, ensuring short feedback paths, and minimizing noise coupling—key aspects for achieving good performance in a Class D amplifier.
# Tools
Proteus-https://www.labcenter.com/
kiCad- https://www.kicad.org/
