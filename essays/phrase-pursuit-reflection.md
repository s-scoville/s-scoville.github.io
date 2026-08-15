---
layout: essay
type: essay
title: "Phrase Pursuit - Reflection Paper"
date: 2026-08-06
published: true
labels:
  - Software Development
  - System Design
  - C#
  - Project Management
---

Developing Phrase Pursuit over the past five weeks has probably been the most challenging programming project I have worked on so far. When I first planned the project, I knew it would push me beyond anything I had built previously, but I underestimated just how much work would go into connecting all of the individual pieces into a complete application. Building individual classes and forms was one thing; getting them all to communicate correctly while maintaining a clean design turned out to be a completely different challenge. There were several points during development where I questioned whether I had taken on more than I could realistically finish in five weeks.

One of the biggest successes of the project was sticking with the Incremental Software Development Life Cycle. Looking back, I think choosing the incremental model was the right decision. Being able to focus on one feature at a time made the project much more manageable. Instead of trying to build everything at once, I was able to complete the user interface, supporting manager classes, gameplay logic, computer opponent behavior, and statistics system individually before bringing everything together. Even though integrating those pieces took much longer than I expected, having each component working beforehand made debugging much easier.

At the same time, I definitely ran into my share of failures and setbacks. The biggest technical hurdle was implementing asynchronous programming with async and await. Before this project, I had almost no experience with asynchronous programming, and understanding how to use it correctly took a lot of research and experimentation. I eventually realized that it was exactly what I needed to keep the Windows Forms interface responsive while the computer players simulated thinking and wheel spin animations. Another challenge was simply getting the overall game flow correct. It seemed like every time I fixed one gameplay issue, I would discover another edge case that needed attention. I spent many hours repeatedly playing the game, finding problems, fixing them, and testing again until the gameplay finally felt stable.

The biggest challenge overall, however, was time. Because of family responsibilities, medical appointments, and chronic back pain, I found myself losing several days of the most important weeks of the development process, which ultimately caused me to submit the project several days after the original due date. As deadlines approached, I found myself spending several late nights (and all-nighters) trying to catch up. Because of that, I had to make some difficult decisions about priorities. Rather than spending time polishing the user interface or adding extra features, I focused on making sure the game itself worked correctly. Looking back, I think that was the right decision. While there are certainly visual improvements I would still like to make, I would rather submit a functional application with a simple interface than a polished application with broken gameplay.

Overall, I am proud of what I accomplished. Phrase Pursuit is by far the largest application I have built, and it gave me experience with concepts that I had very little exposure to before this project, including JSON serialization, asynchronous programming, using Git feature branches, and coordinating communication between multiple classes. More importantly, it showed me that building a larger application is less about writing complicated code and more about organizing the project into manageable pieces and solving one problem at a time.

If I could offer one piece of advice to students choosing a similar project, it would be to keep the scope realistic and start implementing features as early as possible. It is very easy to underestimate how long integration and testing will take. I would also recommend using version control from the very beginning and committing frequently, because being able to track changes and safely experiment with new features made development much less stressful. Finally, I would encourage anyone attempting a larger project not to get discouraged when things stop working. Some of my biggest breakthroughs came after spending hours debugging a problem that initially seemed impossible to solve. Finishing the project reminded me that persistence is just as important as technical knowledge when developing software.