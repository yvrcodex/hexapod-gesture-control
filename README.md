# Hexapod Gesture Control Project

[![License](https://shields.io/badge/license-MIT-informational)](https://github.com/yvrcodex/hexapod-gesture-control/blob/main/LICENSE) ![Version](https://img.shields.io/badge/version-v0--alpha-orange) ![Status](https://img.shields.io/badge/status-active-green)

---

## Project Progress

- [Project ToDo List](./docs/instructions/TODO.md) - This document contains the list of tasks and their status for the Hexapod Project.

- [Structure Guides](./docs/instructions/GUIDES.md) - Basic info about scope of structures

- [References](./docs/instructions/REFERENCES.md) - References support

- [Workflow](./diagrams/WORKFLOW.md) - Detailed workflow of the project.

```mermaid

flowchart LR

                    %% Estruturar o Projeto %%

voids(["start"])
style voids fill:#750075,color:#750075,stroke-width: 3px,stroke:#000000;

voidi["-------------"]
style voidi fill:#000080,color:#000080,stroke-width: 3px,stroke:#000000;

void1["-  -  ------   --"]
style void1 fill:#b05800,color:#b05800,stroke-width: 3px,stroke:#000000;

void2["----     ---"]
style void2 fill:#007900,color:#007900,stroke-width: 3px,stroke:#000000;



void4(["0"])
style void4 fill:#ecec00,color:#ecec00,stroke-width: 3px,stroke:#000000;

void5{"1"}
style void5 fill:#00ffff,color:#00ffff,stroke-width: 3px,stroke:#000000;

void6[("2")]
style void6 fill:#000080,color:#000080,stroke-width: 3px,stroke:#000000;

void7>"3"]
style void7 fill:#ffff00,color:#ffff00,stroke-width: 3px,stroke:#000000;

void8((("4")))
style void8 fill:#ff0000,color:#ff0000,stroke-width: 3px,stroke:#000000;

void9["-------------"]
style void9 fill:#000080,color:#000080,stroke-width: 3px,stroke:#000000;

voidf(["start"])
style voidf fill:#750075,color:#750075,stroke-width: 3px,stroke:#000000;


voids --> voidi
voidi --> void1
voidi --> void2

void1 --> void4 --> void5 --- void7
void5 --- void8
void5 --- 

void2 --> void6 --> void7

void7 --> void9 --> voidf

void8 -.-> void1


                    %% Repositorio

```
---

## **Table of Contents**

- [Description](#description)
- [Key Features](#key-features)
- [Future Applications](#future-applications)
- [Documentation](#documentation)
- [Contribution Guide](./docs/instructions/CONTRIBUTING.md)
- [License](#license)

## **Description**

Welcome to the Hexapod Gesture Control project, developed as part of the academic curriculum at the Pontifical Catholic University of Minas Gerais (PUC Minas), in the Electronics and Telecommunication Engineering course. This project aims to create a hexapod robot that can be controlled using gesture-based inputs, leveraging motors, RF communication, and a Microcontroller Unit (MCU).

The ultimate goal of this project is to explore the potential of gesture-based control in robotics and develop a platform that can assist society in various domains, such as search and rescue operations during accidents or fires, construction activities, and more. The hexapod's versatility and mobility make it an ideal candidate for diverse real-world applications.

## **Key Features**

- **Gesture Control:** The hexapod robot will be capable of recognizing and responding to hand gestures, allowing for intuitive and natural control.
- **Robust Mechanism:** The hexapod will feature a sturdy mechanical design with six legs, ensuring stability and maneuverability across various terrains.
- **Wireless Communication:** RF communication will enable remote control of the hexapod, offering flexibility and extended range.
- **MCU Programming:** The hexapod's behavior and motion patterns will be programmed using the Microcontroller Unit (MCU).
- **Research Impact:** The project aims to pave the way for future advancements in gesture-based robotics, contributing to the field of human-robot interaction and automation.

## **Future Applications**

In the long term, this project envisions a future where gesture-controlled robots can play a vital role in different scenarios, including:

1. **Search and Rescue:** Deploying hexapods in disaster-stricken areas to locate and assist victims during rescue missions.
2. **Firefighting Support:** Using hexapods to navigate hazardous environments and support firefighting efforts.
3. **Construction Assistance:** Hexapods could aid in construction projects, carrying materials, and performing tasks in hard-to-reach areas.
4. **Agriculture and Inspection:** Hexapods can be employed for agricultural purposes and inspection tasks, such as monitoring crops or inspecting infrastructure.

We believe that gesture-controlled hexapods have the potential to revolutionize robotics and contribute positively to society. As we progress through this project, we hope to create a platform that inspires future innovations in the field of robotics and automation.

## **Documentation**

For detailed documentation and technical information, please refer to the [Documentation](./docs) folder.

## **Contribution Guide**

If you wish to contribute to the project, follow the guidelines described in the [Contribution Guide](./docs/instructions/CONTRIBUING.md).

## **License**

This project is licensed under the [MIT License](./LICENSE) - you can view the full license terms there.
