# Background Research

Before delving into the technical concepts, I want to first have a general understanding on how Vu-Meters work and where they're applicable in the real world. 

Grasping a macro-understanding of the system will allow me to better perceive how each of the smaller functions work to serve a bigger purpose. In addition, relevance is a huge motivator when it comes to making a product. The "why" is just as, if not more important than the "how" since it asks whether or not this project has potential to benefit someone or something bigger than myself.

## What is it?

A volume (Vu) meter measures the average signal level and visually displays it in dBu (typically one reading every 300 ms). As the name suggest, dBu measures the relative volume of audio input. The louder the audio, the higher the reading display.

## How does it work?

For a Vu meter to work, it must be capable of doing several tasks:
  1. Convert an analog audio input into digital voltage reading that is linear to the sound intensity. This called a **transducer**.
  2. Voltage sent from the transducer has lots of noise, thus needs to be filtered.
  3. The filtered voltage output is then amplified to a level that can be read by an IC device.
  4. The amplified voltages are sent to the IC device which is designed to input incoming voltage levels and then out put a visual representation of the volume(using LEDs). 
  
To help picture the system, I made a flowchart showing the series of processes:

![Vu-Meter Flowchart](Vu-Meter%20Flowchart.PNG)

