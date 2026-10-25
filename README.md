# CS-Portfolio
SNHU CS Program Portfolio


## CS 255 System Analysis and Design

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client was DriverPass, a company that wanted to help students prepare for their driving tests. They needed a system that would allow customers to access online lessons, take practice tests, and schedule driving lessons. The system also needed to help employees manage appointments, customer information, and training progress.

### What did you do particularly well?

I think I did well at organizing the client’s requirements and connecting them to the system design. Breaking the system into different users and use cases helped me understand what each person needed to do. I also used UML diagrams to show the system’s structure and how its processes would work.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise my activity diagrams to show more detail about situations where a process cannot be completed normally. For example, I would make sure the scheduling process clearly explains what happens when a requested appointment is unavailable. This would make the diagrams more complete and give developers clearer guidance. In general, making diagrams clearer is a goal.

### How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?

I interpreted the user’s needs by reviewing the DriverPass interview and identifying the tasks customers and employees needed to complete. I used those needs to develop requirements and create diagrams showing features such as scheduling lessons and accessing training materials. Considering user needs is important because a system must support the people using it and solve the problems that led the client to request it.

### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I approach software design by first understanding the problem and identifying the users, requirements, and limitations. Then I break the system into smaller processes and use diagrams to organize how the parts will work together. In the future, I would continue using interviews, use cases, and UML diagrams while reviewing the design with stakeholders to catch missing requirements and clarify assumptions before development begins.





## CS 230 Operating Platforms

### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client was The Gaming Room, a company that wanted to expand its Android game, Draw It or Lose It, into a web application that could run across multiple platforms. The application needed to support multiple games, teams, and players while keeping game and team names unique. The design also needed to address scalability, security, and the management of shared game data.

### What did you do particularly well in developing this documentation?

I think I did well at comparing operating platforms and explaining how their strengths and limitations affected the application. I connected my recommendations to the client's requirements and considered factors such as memory, storage, security, and scalability. This helped explain the reasoning behind my design choices.

### What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand how the application's classes and requirements fit together before making changes to the code. The UML diagram clarified the relationships between games, teams, and players. Having this structure made it easier to organize the code and understand how design patterns supported the application's requirements.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the platform evaluation section to make the comparisons more specific to Draw It or Lose It. I would include clearer examples of how each platform would affect deployment, maintenance, and the ability to support more users. This would make my recommendations more useful to the client.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I interpreted the client's needs by identifying the features and restrictions that the application needed to support. For example, the requirement for a single game service instance guided the use of the Singleton pattern, while checking existing names helped prevent duplicate games and teams. Considering user needs is important because the software must solve the client's problems and provide a reliable experience for its users.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the design by reviewing the requirements, identifying the main objects, and considering how the application would operate across different platforms. I used UML diagrams and platform comparisons to organize the design and support my recommendations. In the future, I would also use prototypes, review assumptions with the client, and test important design decisions early to identify problems before development progresses.
