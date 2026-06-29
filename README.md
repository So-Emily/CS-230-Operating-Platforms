# CS 230 - Operating Platforms
## Final Project Journal 

### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client for this project was The Gaming Room. They wanted to expand their game, *Draw It or Lose It*, from an Android-only application into a web-based game that could support multiple operating systems and devices. The software needed to support multiple games, teams, and players while making sure names stayed unique and that only one GameService instance existed at a time.

### What did you do particularly well in developing this documentation?

I think one thing I did well was connecting the client's requirements to the design decisions I made throughout the project. For example, I used inheritance with the `Entity` class to reduce duplicate code and implemented the Singleton pattern so there would only be one `GameService` instance. I also enjoyed comparing different operating systems and recommending the platform I thought would best support the client's future growth.

### What about the process of working through a design document did you find helpful when developing the code?

I actually found the design document more helpful than I expected. It made me slow down and think about how all of the classes would work together before I started writing code. Once I started coding, I already had a good roadmap to follow because I had worked through the class relationships and design patterns first.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could go back and revise one part, I would probably spend more time refining the operating platform evaluations and recommendations. As I learned more about Linux, cloud environments, memory management, and distributed systems throughout the course, I found myself going back and adding more details. One thing I definitely learned from this project was to read the assignment requirements and rubric more carefully before jumping in. I accidentally completed large parts of later projects while working on Project One because I filled out almost the entire software design document right away. It ended up helping me later, but it also taught me to pay closer attention to exactly what is due for each assignment.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I focused on the requirements the client provided and used those to guide my design decisions. For example, I made sure duplicate names could not be created and used the Singleton pattern to keep only one `GameService` object in memory. Keeping the user's needs in mind is important because the software is being built to solve their problem. If the design doesn't meet those needs, then the software won't be successful no matter how well the code is written.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the project by breaking it into smaller pieces and looking at how the different classes would work together. Using object-oriented programming principles and design patterns helped me keep everything organized before I started writing code. In the future, I would use the same approach by first reviewing the requirements, creating diagrams or models, identifying any useful design patterns, and then writing the code. I found that taking the time to plan first made the development process much smoother.

