# Draw It or Lose It

## Software Design Document Reflection

### Overview
This project was completed for The Gaming Room, a client that originally developed Draw It or Lose It as an Android game and wanted to expand it into a web based, distributed application. Their requirements included supporting multiple teams and players, enforcing unique names for all game entities, and ensuring that only one instance of a game could exist in memory at a time. My role was to design the software architecture, document the system, and recommend the most appropriate operating platform and technologies for deployment.

### What I Did Well
I translated the client’s requirements into clear technical constraints and explained how those constraints shaped the architecture. My evaluation of operating platforms such as Linux, macOS, Windows, and mobile was thorough and grounded in real world considerations like scalability, cost, and deployment flexibility.

### Value of the Design Process
Working through a full design document before writing any code helped me think through system structure, object relationships, and constraints early in the process. This made the eventual coding more organized and intentional. Defining the Domain Model and identifying OOP principles such as inheritance, encapsulation, and composition ensured that the codebase would be modular, maintainable, and aligned with the game’s rules.

### What I Would Revise
If I were to revise one part of the document, I would refine the Design Constraints section by tying each constraint more directly to the user experience. For example, explaining how unique naming prevents gameplay confusion or how a single game instance ensures fairness would strengthen the connection between technical decisions and user outcomes.

### Understanding and Implementing User Needs
Interpreting the user’s needs required balancing business goals, technical feasibility, and player experience. I focused on what the client ultimately wanted, which was an accessible, scalable, and consistent multiplayer game, and ensured that the design supported those goals. Considering user needs is essential because software architecture decisions directly affect usability, performance, and long-term maintainability.

### Approach to Software Design
My approach centered on breaking the system into clear components, identifying shared behaviors, and using OOP principles to reduce duplication. In future projects, I would continue using techniques such as UML modeling, requirements to constraints mapping, and platform evaluation. These strategies help ensure that the design is technically sound and aligned with the client’s vision.
