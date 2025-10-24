# The-Gaming-Room


Project Reflection
Client and Software Requirements

The client for this project was The Gaming Room, a company that wanted to expand their Android-based game Draw It or Lose It into a web-based, multi-platform environment. They needed a distributed application that could support multiple game instances, each with teams, players, and rounds running at the same time. The system had to be scalable, secure, and accessible through web browsers on both desktop and mobile devices. My task was to design the software architecture and prepare it for deployment in a cloud environment.

What I Did Well

I think I did well documenting the software architecture and connecting each design choice to the client’s goals. I made sure the design addressed scalability, authentication, and RESTful communication between the server and clients. My Evaluation and Recommendations sections clearly explained why Linux and cloud-based platforms were the best options for cost and performance.

What Helped During Development

Writing the design document first was extremely helpful because it forced me to think through how the application would function before coding. Defining the server-side components, REST controllers, and authentication logic made development much smoother and reduced debugging time later on.

What I Would Improve

If I could revise one part, I’d expand on distributed systems and network design. I’d include more about using cloud tools like load balancers and caching systems (AWS Elastic Cache, CloudFront) to improve performance and fault tolerance. More visuals or diagrams could also make it clearer.

Interpreting and Implementing User Needs

I focused on scalability, performance, and ease of access — key needs for a multi-player web game. I implemented these by designing REST APIs, adding authentication, and planning for efficient image and memory management. It’s important to consider user needs because software should always align with how people actually use it. A design that prioritizes performance and simplicity helps create a better user experience.

Design Approach and Future Strategies

My main focus was modularity and scalability through a client-server model. Techniques like flow diagrams, pseudocode, and REST endpoint planning helped me organize development. In future projects, I’d use agile methods with short feedback loops, include early prototype testing, and integrate Docker for easier deployment between environments. These strategies will help me build stronger, more maintainable software moving forward.
