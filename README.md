# Perceptual Rift
Single-Player Optical Illusion Puzzle Game

## Project Overview
Perceptual Rift is a single-player puzzle game developed in Unreal Engine 5.6 that challenges players to solve perspective-based optical illusion puzzles. The core mechanic requires players to align illusion elements from a precise viewpoint. When alignment is held for a short duration, hidden geometry is revealed and enables progression.

This project focuses on correctness, traceability, and engineering discipline rather than feature volume.

## Project Justification
Optical illusion puzzles rely on human perception rather than reflexes or memorization. This project explores how visual cognition principles can be translated into interactive gameplay systems. The goal was to create a technically sound vertical slice that demonstrates feasibility, stability, and thoughtful design.

## Core Features
- Perspective-based alignment puzzles
- Stable hold confirmation to prevent accidental solves
- Dynamic removal of illusion blocks
- Hidden bridge reveal with collision control
- Fully functional Main Menu
- Fully functional Pause Menu

## Technologies Used
- Unreal Engine 5.6
- Blueprint Visual Scripting
- Windows PC platform
- Git version control

## Design Process
An Agile-inspired iterative process was used. Core mechanics were implemented in small increments, validated through testing, and refined before expanding scope. Emphasis was placed on traceability between requirements, design artifacts, code modules, and test cases.

## Testing Summary
Testing was conducted at multiple levels:
- Component testing of core Blueprints
- Integration testing between puzzle logic, collision, and UI
- System testing validating the full gameplay loop

All implemented requirements were tested and passed.

## Code Highlights
A notable challenge was implementing stable perspective alignment using screen-space projection. This required projecting multiple anchor points into screen coordinates, calculating distances, and confirming alignment stability over time before triggering a solve event.

## How to Run the Project
1. Open the project in Unreal Engine 5.6
2. Play the StartMenuMap level
3. Select Start Game

## Visual Architecture and Design Artifacts

The following diagrams and visuals document the system architecture, gameplay logic, and user interface flow for the project. These artifacts support the traceability between requirements, design, implementation, and testing.

---

### UML Class Diagrams

These UML diagrams represent the primary Blueprint classes and their responsibilities within the system.

#### BP_IllusionGroup
![BP_IllusionGroup UML](screenshots/BP_IllusionGroup%20UML.png)

*Figure 1: UML diagram for BP_IllusionGroup showing alignment detection and solve logic.*

---

#### BP_Block
![BP_Block UML](screenshots/BP_Block%20UML.png)

*Figure 2: UML diagram for BP_Block showing visibility and collision behavior.*

---

#### BP_MergedBridge
![BP_MergedBridge UML](screenshots/BP_MergedBridge%20UML.png)

*Figure 3: UML diagram for BP_MergedBridge showing reveal and collision enablement.*

---

### Activity Diagram: Puzzle Solve Flow

This activity diagram illustrates the gameplay flow from player alignment through puzzle solve and bridge reveal.

![Puzzle Solve Activity Diagram](screenshots/Puzzle%20Solve%20Activity%20Diagram.png)

*Figure 4: Activity diagram showing the puzzle solve workflow.*

---

### UI Flow Diagram

The UI flow diagram shows navigation between the Main Menu, Gameplay, and Pause Menu states.

![UI Flow Diagram](screenshots/UI%20Flowchart.png)

*Figure 5: User interface flow diagram.*

---

### Capstone Showcase Poster

The following poster was created for the Technology Capstone Showcase and summarizes the project at a high level.

> Note: The poster is provided as a PowerPoint file in the repository.

[CST-452 Showcase Poster](screenshots/CST_452_ShowcasePoster.pptx)

## Final Project Demonstration

The final project demonstration video presents the completed vertical slice of the *Perceptual Rift* optical illusion puzzle game. The video demonstrates core gameplay functionality, user interface behavior, and completed testing aligned with the project requirements.

🎥 **Final Presentation Video**  
[CST_452 Final Presentation.mp4]([CST_452_Final_Presentation.mp4](https://mygcuedu6961-my.sharepoint.com/:v:/r/personal/jalmonte3_my_gcu_edu/Documents/CST_452%20Final%20Presentation.mp4?csf=1&web=1&e=UogcmK&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D))

## Repository
Source code is maintained in a private Git repository and available upon request for academic review.

## Author
Jim Joel Almonte  
Computer Science Capstone Project  
