# CS-230-Gaming-Room-Project
Final iteration for SNHU CS-230 The Gaming Room software design project 

REFLECTION 
The client for this project was The Gaming Room, a company that wanted to expand their existing Android game, Draw It or Lose It, into a web-based application that could run across multiple platforms. The main goal was to design software that supports multiple teams and players, ensures unique names for games and teams, and allows only one instance of the game service to exist in memory at a time. The focus was on creating a scalable and accessible design that could work on different operating systems and devices through a browser.

One area I feel I did particularly well in was organizing the software design using object-oriented principles. Creating and using the Entity base class helped simplify the structure by allowing Game, Team, and Player to share common attributes like ID and name. This made the code cleaner and easier to manage. I also think I did well applying the singleton pattern in the GameService class to ensure only one instance existed, which directly met one of the core requirements.

Working through the design document before coding was really helpful because it gave me a clear plan to follow. The UML diagram especially made it easier to understand how the classes should relate to each other and what responsibilities each one should have. This made the coding process smoother since I already had a structure in mind instead of figuring everything out as I went.

If I could revise one part of my work, I would improve the level of detail in the early design stages, especially when describing how the system would operate in a distributed environment. I think adding more detail about networking, real-time communication, and how users interact across devices would make the design stronger and more complete.

To interpret the user’s needs, I focused on the requirements given, such as supporting multiple teams and players, enforcing unique names, and making the application accessible across platforms. I translated these needs into specific design decisions, like using lists to manage collections of objects and adding validation logic to prevent duplicate names. Considering the user’s needs is important because it ensures the final product is functional, user-friendly, and meets expectations instead of just being technically correct.

When approaching the design, I focused on breaking the problem into smaller parts and mapping those parts to classes and responsibilities. I used object-oriented design, UML diagrams, and design patterns like the singleton pattern to guide my decisions. In the future, I would continue using these strategies, along with more planning around scalability and real-time features, to design similar applications more effectively.
