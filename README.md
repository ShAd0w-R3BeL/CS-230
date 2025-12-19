CS 230 Project Portfolio: The Gaming Room
Project Overview
In this project, I acted as a consultant for The Gaming Room to transition their existing Android game, Draw It or Lose It, into a modern, web-based, multi-platform environment. My role was to design a scalable architecture using Java and specific Design Patterns to ensure data consistency and a seamless user experience across diverse devices.





Reflection
1. Client and Software Requirements
The client is The Gaming Room, a company looking to expand their "Draw It or Lose It" game from a limited Android-only app to a distributed web service. They required a system that supports multiple teams, each containing multiple players. Key technical requirements included enforcing unique names for all games and teams and ensuring that only one instance of the game management service exists in memory at any time to maintain a unified game state.




2. Successes in Documentation
I believe I effectively utilized Design Patterns to solve complex architectural constraints. Specifically, I clearly documented how the Singleton Pattern would be applied to the GameService to prevent data inconsistencies. I also integrated the Iterator Pattern as a mandatory mechanism for entity creation, which provides a professional and efficient solution for validating unique naming requirements.





3. Design Document Benefits for Coding
The design document served as a critical blueprint during the refactoring process. Defining the Domain Model and Inheritance structure (using an Entity base class) allowed me to establish a consistent way to manage IDs and names across different objects before writing the first line of code. This pre-planning ensured that encapsulation and immutability were "baked into" the system's foundation.





4. Areas for Revision and Improvement
If I were to revise this work, I would expand on the Data Tier. While I identified the need for a database, providing a specific schema or choosing between SQL and NoSQL would have made the transition to development even smoother. I would improve this by creating a detailed Entity-Relationship Diagram (ERD) to match the class diagrams provided.


5. Interpreting and Implementing User Needs
I interpreted the user’s need for a "distributed" experience by proposing a Three-Tier Architecture. This allows users on web browsers, mobile apps, and different operating systems to all connect to a single Application Tier. Considering user needs is vital because it dictates the platform choice; for instance, recognizing that users need access from varied devices led me to recommend a responsive web design approach.





6. Software Design Approach and Future Strategies
My approach relied heavily on Object-Oriented Programming (OOP) principles and the use of the Singleton and Iterator patterns. In the future, I would use Docker containers and Load Balancers as a standard strategy for similar applications. These tools allow the software to be modular and resilient, ensuring that even if one server instance fails, the game state—managed by a high-speed cache like Redis—remains consistent for the user.




Course Competencies Demonstrated

CS-30406: Utilized the Singleton and Iterator patterns to solve memory consistency and unique naming problems.



CS-30407: Analyzed Three-Tier and Distributed architectures to facilitate multi-platform game expansion.



CS-30408: Evaluated Linux, Windows, and Mac platforms, ultimately recommending Ubuntu Server for its stability and cost-effectiveness.

git clone https://github.com/ShAd0w-R3BeL/CS-250.git

Each project's folder will contain a README file with specific instructions on how to compile and run the code.

Contact Feel free to reach out to me with any questions or feedback.

Name: Matthew Wood

Email: matthew.wood16@snhu.edu

LinkedIn: https://www.linkedin.com/in/matthew-r-wood-56b3b44b/
