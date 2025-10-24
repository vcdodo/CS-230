# The Gaming Room Project

**Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**
The client, The Gaming Room, wanted to develop a web-based game based on their current Draw It or Lose It game. It was already available on Android but they wanted it to be made available on all platforms.

**The client had very specific technical requirements for the game, and they were that:**
- as already mentioned, that the game should be made available for all software operating system platforms
- a game should have the ability to have multipole teams assigned to it
- a team should have the ability to have multiple players assigned to it
- game and team names should be unique
- only one instance of the game should exist in memory.

**What did you do particularly well in developing this documentation?**
I am strong with UML diagrams so I did particularly well with that section, but it also helped with two other aspects of this project, and that is:
-  combined with the requirements, it helped me to translate the requirements into a design specification that could be understood by both technical and non-technical stakeholders
- it aided with code development in that it created an outline for coding; all I then had to do, was the implementation.


**What about the process of working through a design document did you find helpful when developing the code?**
I found the design document to be almost a blueprint, or roadmap, to developing the code. It provided me with the basics of the logic that had to be implemented in the code. It was then 
left up to me as to how I wanted to implement that logic. 

Specific requirements such as, the game service had to be a unique instance, led me to the singleton software design pattern. In addition, requirements such as a game could have multiple teams, and teams could have multiple players, gave me an insight to what type of data structures would be required for these objects.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**
I would pick the Evaluation section. This section was restricted to bullet points, which does not necessarily serve as a comprehensive explanation of those points. I would improve on it by expanding those points into detailed explanations.

**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**
I focused on the substance(the what) of the user requirements and translated them into a design specification. 

It is important to focus the design specification on the user's needs because that is what the developed system would eventually have to deliver. Delivering software based on user requirements also reduces rework.

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**
My initial approach was to focus on the user requirements, translate them into both a UML diagram and a design specification, and then to use those documents for code implementation. 

In future though, I would use the tried-and-tested steps of:
- understanding the problem space by
    - clarifying requirements
    - defining the scope and constraints of the project
    - identifying use cases
- modeling the sustem conceptually
- choosing an architectuak design
- designing components and interfaces
- planning for testing and validation
- developing a prototype for early testing
- comprehensive documention and communication 

