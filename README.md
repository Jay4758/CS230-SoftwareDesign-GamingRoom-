# The Gaming Room: Software Design Document

## Summary of The Gaming Room Client and Software Requirements
The Gaming Room, a client of Creative Technology Solutions, requested the design of a web-based **game management system** for their game *"Draw It or Lose It"*.  
The key requirements included:
- Support for multiple teams with unique team names.
- A single instance of the game in memory (Singleton pattern).
- Scalability to handle many teams, players, and games simultaneously.
- Security to protect user and game data.
- Cross-platform availability to work on web browsers and various devices.

## What I Did Well in Developing This Documentation
In this project, I excelled at clearly identifying and documenting the requirements, design constraints, and object-oriented design patterns (e.g., Singleton and Iterator). I also presented the system architecture using clean and organized sections, making it easy to understand for both clients and developers.

## Helpful Aspects of the Design Document Process
Working through the software design document was extremely helpful in mapping out the system architecture **before writing any code**. It allowed me to anticipate potential challenges, such as concurrency and scalability, and provided a clear plan for implementing the system. This structured approach improved my understanding of the project and simplified the coding process.

## Areas for Improvement
If I were to revise one part of the design document, I would focus on improving the **UML diagrams**. Adding more detailed relationships between classes, such as associations and dependencies, would provide a clearer picture of the system's structure. I would also include more annotations to explain the logic behind each design choice.

## Interpreting and Implementing User Needs
To interpret the user’s needs, I closely analyzed the client’s requirements, such as **unique team names**, **scalability**, and **security**. I implemented these needs using object-oriented principles and design patterns. For instance:
- The **Singleton pattern** ensures only one instance of the game is in memory.
- The **Iterator pattern** prevents duplicate team or game names.
  
Considering user needs is crucial in software design because it ensures the final product aligns with client expectations, improves user satisfaction, and enhances usability.

## My Approach to Designing the Software
I followed a structured design approach, including:
1. **Requirements Analysis**: Clearly identifying functional and non-functional requirements.
2. **System Architecture**: Outlining client-server interactions, database layers, and user interfaces.
3. **Object-Oriented Design**: Using patterns like Singleton, Iterator, and Encapsulation to ensure scalability and maintainability.
4. **Technology Selection**: Choosing tools and frameworks, such as MySQL for storage and Apache Tomcat for hosting.

### Strategies for Future Projects
In future projects, I would incorporate the following strategies:
- **Iterative Prototyping**: Build small prototypes to validate the design with users early on.  
- **User Feedback**: Involve users throughout the design process to ensure their needs are fully met.  
- **Improved Diagramming**: Use advanced UML tools to create more detailed and accurate system diagrams.

This structured approach will help me design similar software applications effectively while improving the overall quality and user alignment of the project.


