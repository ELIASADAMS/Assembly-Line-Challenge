# Assembly Line Challenge - Abandoned Unreal Engine 4 Project

This repository contains an abandoned Unreal Engine 4 project. The original goal was to create an arcade game titled "Assembly Line Challenge," centered around conveyor belts and assembling PCs in a whimsical factory setting. The project challenges players' visual object recognition skills and speed as they try to build computers before they reach the end of a fast-moving conveyor belt. Due to time constraints and shifting priorities, the project was not completed.

## Project Overview

"Assembly Line Challenge" aimed to be a fast-paced arcade game. Players are tasked with quickly and accurately assembling a PC from various components (CPU, GPU, RAM, etc.) as they move along a conveyor belt. Success depends on recognizing the parts and assembling them in the correct order before the PC reaches the end of the line.

**Reason for Abandonment:** Project was discontinued and used as a prototype to learn UE 4.27.

## Project Structure

The project files are organized as a standard Unreal Engine 4 project:

*   **`Config/`:** Contains configuration files for the editor, engine, and game settings.
*   **`Content/`:** Holds all the game assets, including:
    *   **`Maps/`:** Contains the levels created for the game (`NewMap.umap`, `NewMap1.umap`, `Untitled.umap`).
    *   **`Roll/`:** Likely contains assets related to a rolling object (perhaps a test object or a placeholder object). Includes textures (ao, diffuse, height, metallic, normal, smoothness).
    *   **`BP_Conbelt.uasset`:** This is the core component - a Blueprint asset representing a conveyor belt.
    *   **`M_Conbelt.uasset`, `M_Conbelt1.uasset`:** Master materials for the conveyor belts.
    *   **`M_Conbelt_Inst.uasset`, `M_Conbelt1_Inst.uasset`:** Material instances for the conveyor belts.
    *   **`Tiles_*.uasset`:** Tile assets, probably used for the level's flooring or environment.
*   **`Intermediate/`:** Contains intermediate files generated during the build process.
*   **`Saved/`:**  Contains autosaves, logs, and configuration data.
*   **`ALC.uproject`:** The Unreal Engine project file.

## Notable Assets

*   **`Content/BP_Conbelt.uasset`:** The central Blueprint for the conveyor belt functionality. This is the most important asset for anyone interested in understanding the project's mechanics.
*   **`Content/Maps/*.umap`:** The map files contain the level design and arrangement of conveyor belts and other assets.
*   **`Content/M_Conbelt*.uasset`:** The material used to make the conveyor belt animated.

## Intended Use

While the project is incomplete, it may be of interest to:

*   Unreal Engine 4 beginners looking for examples of basic gameplay mechanics.
*   Developers interested in implementing conveyor belt systems.
*   Anyone curious about the process of prototyping a game idea in Unreal Engine.
*   Anyone wants to use whimsical factory setting.

## Running the Project

1.  Ensure you have Unreal Engine 4.27 installed.
2.  Clone or download this repository.
3.  Double-click the `ALC.uproject` file to open the project in Unreal Engine 4.27.
4.  Open one of the maps from the `Content/Maps/` directory (e.g., `NewMap.umap`) to explore the project.
5.  Press the "Play" button in the Unreal Editor to run the game.

**Note:** Due to the incomplete nature of the project, not all features may be fully functional, and there may be bugs or missing assets. Expect also missing assets about PC and assembling
