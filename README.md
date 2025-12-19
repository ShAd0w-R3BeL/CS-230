CS 230: Operating Platforms - Portfolio Project
Software Design Document: The Gaming Room
Project Overview
This repository contains the Software Design Document (SDD) for The Gaming Room, developed as part of the CS 230 course at Southern New Hampshire University. This project focuses on transitioning a local game, "Draw It," to a modern, web-based platform capable of supporting multiple teams and concurrent sessions.

Reflection and Analysis
1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design? The client, The Gaming Room, sought to expand their "Draw It" game from a single-machine application to a distributed web-based platform. The primary requirements included the ability to support multiple simultaneous games, unique team/player identifiers, and cross-platform compatibility to reach a broader audience.

2. What did you do particularly well in developing this documentation? (Example Answer: Replace with your own) I believe I excelled at translating the abstract needs of the client into concrete UML Diagrams. Specifically, ensuring that the Singleton pattern was clearly defined to manage the game service helped bridge the gap between high-level requirements and technical implementation.

3. What about the process of working through a design document did you find helpful when developing the code? The design document acted as a roadmap. Having a predefined Entity-Relationship Diagram (ERD) or Class Diagram allowed me to write the Java code for the game engine without second-guessing the relationships between the Game, Team, and Player classes.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it? I would choose to revise the Security and Memory Management sections. While I addressed the basics, I would like to provide more specific details on how the operating platform handles memory allocation for concurrent game threads to ensure the system doesn't crash under high load.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing? I interpreted the need for "uniqueness" (no two teams having the same name) by implementing a service-layer check within the code design. Considering user needs is vital because a system that functions perfectly but doesn't solve the user's problem is a failed project. Design must always serve the end-user's experience.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application? I approached this using Design Patterns, specifically the Singleton Pattern, to ensure a centralized point of control for game instances. In the future, I would utilize more robust automated modeling tools and perform a deeper "platform analysis" to evaluate the specific strengths and weaknesses of the target operating system before finalizing the architecture.

Course Competencies Demonstrated
Through this project, I have demonstrated the following competencies:

CS-30406: Utilized software design templates and patterns (Singleton) to solve architectural problems.

CS-30407: Analyzed system architectures to support multi-client web environments.

CS-30408: Evaluated platform characteristics to ensure cross-platform compatibility.

git clone https://github.com/ShAd0w-R3BeL/CS-250.git

Each project's folder will contain a README file with specific instructions on how to compile and run the code.

Contact Feel free to reach out to me with any questions or feedback.

Name: Matthew Wood

Email: matthew.wood16@snhu.edu

LinkedIn: https://www.linkedin.com/in/matthew-r-wood-56b3b44b/
