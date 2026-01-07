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

## Repository
Source code is maintained in a private Git repository and available upon request for academic review.

## Author
Jim Joel Almonte  
Computer Science Capstone Project  
