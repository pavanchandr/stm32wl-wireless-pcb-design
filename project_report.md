# Project Report
## Overview
During my hardware engineering internship at EMS Fire Cell (Kiddie Global Solutions, UK), I contributed to the redesign and optimisation of an industrial wireless fire safety communication device. The project focused on upgrading the existing hardware platform due to processor obsolescence and increasing component costs while maintaining compatibility with the existing PCB dimensions and mechanical enclosure.
The redesign involved migrating the existing design to the integrated wireless MCU platform, PCB modifications, component optimisation, RF-aware routing improvements, power system updates, and manufacturing-oriented design changes. 
## Initial Problems Identified
### Processor Obsolescence & Cost Increase
- The Original design used two separate processors for system control and RF communication.
- Existing processors were becoming obsolete and increasingly expensive for production.
### Battery Limitations
- A new battery system was proposed to improve long-term device performance and reliability.
- Suitable SMD battery contacts for the new battery were not commercially available.
### Hardware Integration Requirements
- Migration to the STM32WLxx integrated wireless MCU required additional supporting circuitry based on datasheet specifications.
- New updated SMPS circuitry and an additional crystal oscillator needed to be integrated into the existing PCB design.
### PCB Design Constraints
- The redesign needed to maintain existing PCB dimensions and mechanical enclosure compatibility while integrating the updated hardware architecture.
## Proposed Engineering Approach
### Hardware Architecture Simplification
- Replace the existing controller and radio architecture with the new technology STM32WLxx integrated wireless MCU platform.
- Reduce cost, component count, long-term production cost and increased space on board.
### Power System Optimisation
- Transition from existing battery to 3V CR123A battery system to improve device operational life and reliability.
- Replace old battery contacts with commercially available through-hole battery contacts.
### PCB Redesign & Integration
- Update PCB layout and routing to support the STM32WL architecture while maintaining existing board dimensions and enclosure compatibility.
- Integrate required (Switch Mode Power Supply)SMPS circuitry and additional crystal oscillator based on MCU datasheet hardware design requirements.
- Improve hardware maintainability, component availability, and manufacturing robustness while preserving existing system functionality.
## My Technical Contributions
### System Planning & Hardware Coordination
- Collaborated with the software engineering team to finalise MCU pin configuration based on STM32WL datasheet requirements and system fucntionality.
- Updated system block diagrams to support the new integrated wireless MCU architecture.
- Integrated required SMPS circuitry and additional crystal oscillator based on datasheet recommendations.
### Component Selection & Library Development
- Created custom STM32WL MCU symbol and footprint in Altium Designer and added all the details to the company library.
- Created and added custom Altium symbols and footprints for components not available in the existing company library as per IPC standards.
### PCB Redesign & Layout Optimisation
- Redesigned PCB layout while maintaining existing board dimensions and compatibility.
- Worked under strict design constraints to preserve existing test points locations to avoid additional manufacturing costs associated with redesigning the production test jig.
### RF Routing & Signal Integrity Improvements
- Studied RF layout techniques and microstrip line routing to support RF signal performance.
- Optimised placement and routing of RF inductors and capacitors while maintaining straight line RF path requirements
- Implemented routing improvements balancing RF considerations, and existing layout constraints.
### Cross-Team Collaboration & Validation
- Participated in design reviews with hardware and test engineering teams to validate layout decisions.
- Worked closely with test team to implement layout adjustments and improve compatibility with existing testing infrastructure on board.
- Applied iterative design improvements based on engineering feedback and validation discussions.
## Tools & Technologies Used
### PCB Design & Hardware Development
- Altium Designer
- Schematic capture & PCB layout
- Custom component symbol and footprint creation
- 2-layer PCB design and routing
### Embedded Hardware
- STM32WL Wireless MCU
- Embedded system architecture
- SMPS integration
- Crystal oscillator integration
- Battery power system redesign
### RF Design & Signal Integrity
- RF aware PCB layout techniques
- Microstrip line routing
- RF component placement optimisation
- Signal integrity considerations
### Engineering & Collaboration
- Datasheet-driven hardware development
- Cross-functional collaboration with software and test teams
- Design review and iterative engineering improvements
- Manufacturability and cost optimisation
## Project Outcomes
- Strengthened hands-on expertise in embedded hardware redesign, PCB optimisation, RF routing, and datasheet driven engineering development.
- Collaborated across software, hardware, mechanical, test engineering teams in an iterative industrial development environment.
- Improved manufacturability and cost efficiency through practical hardware and assembly-focused design decisions.
- Applied RF-aware PCB layout techniques while preserving existing production testing infrastructure.
- Delivered a prototype-stage redesign of an industrial wireless embedded hardware platform under real-world manufacturing and layout constraints.

## Confidentiality Notice
Due to company confidentiality and intellectual property agreements, detailed schematic, firmware, and complete PCB design files are not publicly shared. Limited visuals and high-level technical descriptions are provided for professional portfolio purposes only.
