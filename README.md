# Micromouse Sensor Subsystem

This repository contains the necessary resources and documentation for building the sensor subsystem of a micromouse. The sensor subsystem is responsible for detecting obstacles and walls in the maze, allowing the micromouse to navigate effectively.

## Useful Resources
- [YouTube Playlist](https://www.youtube.com/watch?v=UHWE3d_au30&list=PLAWsHzw_h0iiPIaGyXAr44G0XfHfyjOe7): Helpful video references on understanding the project, safety, PID control, and more.

## Navigation
- **Schematic Reference**: Shows the schematic of the sensor PCB.
- **Setting Up Arduino and STM32CubeIDE**: Instructions for downloading and setting up the STM32CubeIDE software.
- **Soldering Components**: Instructions for soldering each component onto the PCB.
- **Testing**: Testing components using breadboards.
- **Software**: Programming instructions and suggestions.

## Schematic Reference
The schematic reference provides a detailed view of the sensor PCB, helping you understand the connections and components used in the subsystem.

## Setting Up STM32CubeIDE
Learn how to download and set up the Arduino software and STM32CubeIDE for programming and debugging the sensor subsystem.

## Soldering Components
Follow step-by-step instructions on how to solder each component onto the PCB correctly, ensuring proper functionality of the sensor subsystem.

The components must be soldered in order to maintain a solid electrical connection between two circuit elements. For ease, it's recommended that you follow the order listed below of components to solder. This will help prevent a mess or short circuits.
    On the schematic, the IR Emitters are labeled as D0, D1, D2, and D3. Find the corresponding labels on the PCB. They should be at the front of the board
Place the shorter end of the emitter in the positive throughole of the corresponding pad and the longer end through the negative side. For reference, the D0 pad is shown below.

After inserting the emitter all the way, bend the emitter's leads so that the emitter lines up parallel to the PCB AND it is centered on the emitter sillhouette on the PCB. You can now solder the emitter.
Repeat the same process for the IR Receivers. The receivers are located right next to the emitters, and are labelled as Q0, Q1, Q2, and Q3. For the receivers, the short end is also the positive end
When you're soldering the components, make sure that the LEDs line up with the sillhouettes as much as possible. In other words, the length of the leads above the PCB should be as short as possible. This will ensure that one receiver from one set will not have interference from an emitter of another set.

## Testing
Use breadboards to test the components before soldering them onto the PCB, ensuring they work as expected.

## Software
Here are some useful KiCad Tutorials and STM32CubeIDE for brand-new starters:
KiCad Tutorials: https://www.youtube.com/watch?v=vaCVh2SAZY4&list=PL3bNyZYHcRSUhUXUt51W6nKvxx2ORvUQB
STM32CubeIDE: https://www.youtube.com/watch?v=gL8OoS9E1rw&list=PLnMKNibPkDnFCosVVv98U5dCulE6T3Iy8

## 3D Printed Parts
Additional resources for designing and printing 3D parts for the micromouse, including CAD files and printing instructions.

## Other Resources
- **Git Markdown**: Learn how to format text and documents using Git Markdown.
- **How to Read a Datasheet**: Guide on interpreting and understanding component datasheets for effective use in your project.

## Acknowledgements
- @UCLAIEEE
