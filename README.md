# CS-230 Operating Platforms

## Course Overview

Throughout CS-230, I learned how operating platforms influence software design, performance, security, and scalability. For this course, I developed a software design document for The Gaming Room and evaluated different operating systems to determine the best approach for expanding their game, Draw It or Lose It, to additional platforms.

## Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was the client for this project. They already had an Android application called Draw It or Lose It and wanted to expand it into a web-based game that could be accessed from multiple operating systems and devices. The application needed to support multiple teams and players, maintain unique game and team names, and assign unique identifiers to games, teams, and players. It also needed to maintain consistent game information across devices while supporting the game's images and timed rounds.

## What did you do particularly well in developing this documentation?

I think one of my strengths was comparing different operating platforms and explaining how each option would affect the application. Rather than focusing only on whether a platform could run the software, I considered licensing costs, scalability, storage, memory management, security, and the experience of users accessing the game from different devices. I also organized my recommendations into separate sections to make the document easier to follow. I believe my recommendation to use Ubuntu Server with a Java backend and PostgreSQL database provided a practical solution that addressed the client's requirements.

## What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand the importance of planning how the application's components should work together before developing the full system. The requirements and UML class diagram helped identify the relationships between games, teams, and players. They also helped explain how inheritance, encapsulation, and the singleton pattern could support the application's design. I found it helpful to have the requirements documented because they provided a reference for how the software should function and how individual components would communicate.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one area, I would expand the system architecture documentation to include a more detailed diagram of how the browser, application servers, database, and image storage would communicate. My document explains these components and their responsibilities, but a visual representation would make the design easier for both the client and development team to understand. I would also include more detail about how the application could scale as additional users begin playing simultaneously. This would help demonstrate how the proposed architecture could support future growth.

## How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I started by identifying what The Gaming Room wanted to accomplish and translating those needs into technical requirements. Because the client wanted the game available on multiple platforms, I recommended a browser-based application with shared server-side functionality rather than developing separate applications for each operating system. I also considered the need for consistent game information, unique identifiers, and support for multiple teams and players. These requirements influenced the design of the application's classes, database, and server architecture.

Considering user needs is important because a technically functional application may still be unsuccessful if it does not meet the client's expectations. Understanding those expectations early helps developers make better design decisions and reduces the need for major changes later.

## How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach was to review the business and technical requirements first, identify the design constraints, and compare possible solutions before making a recommendation. I evaluated Windows, Linux, macOS, and mobile platforms to understand their advantages and limitations. I then considered storage management, memory management, distributed systems, networking, and security to develop a complete recommendation.

For this project, I recommended Ubuntu Server because it supports Java applications, cloud deployment, scalability, and cost-effective hosting. I also recommended PostgreSQL for maintaining shared game information and a browser-based client for cross-platform access.

In future projects, I would continue using requirements analysis, UML diagrams, platform comparisons, and research before beginning development. I would also consider security, scalability, and maintenance early in the design process instead of treating them as issues to address after the application has been developed. This course helped me understand that software design involves more than writing code. It requires planning how the entire system will function and continue meeting user needs over time.
