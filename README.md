CS-255-System-Analysis-and-Design 🚗📋

Welcome to my portfolio repository for CS 255: System Analysis and Design. This repo showcases my work designing a scheduling and practice test platform for DriverPass, a driving school client, from initial requirements gathering all the way through full system design.

📁 What's In This Repository
Business Requirements Document — Project One deliverable, covering DriverPass's functional and nonfunctional requirements
System Design Document — Project Two deliverable, including UML use case, activity, sequence, and class diagrams, plus a full technical requirements breakdown

Together, these documents show my ability to collect requirements directly from a client and translate them into a complete, working system design.

💭 Reflection

Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client for this project was Liam, the owner of DriverPass, a driving school that needed a system to help customers find and book suitable times to learn and test for their license, with as little hassle as possible. My job was to design a cloud based scheduling and practice test platform that would let DriverPass run day to day operations, appointment booking, driver and vehicle assignment, practice testing, and DMV syncing, all in one place. Just as important as the features themselves was building a solid foundation from the start, one that would keep the business's IT and cybersecurity concerns to a minimum rather than something addressed as an afterthought.

What did you do particularly well?

I feel like I was able to really get into the head of both the business owner and the customers who would use DriverPass day to day. On the customer side, this shows up in the Schedule Appointment activity diagram, instead of designing a system that just fails if a driver or vehicle isn't available, I built in a loop that sends the customer back to pick a different time, so they always have a clear next step instead of hitting a dead end. On the owner's side, this shows up in the class diagram, where I gave Secretary, IT Officer, and Owner their own distinct access levels (schedule access, system access, and report access) instead of treating all staff the same. That reflects actually thinking about how Liam's business runs day to day, not just what the system technically needed to function.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work, I would choose the Technical Requirements section. Looking back, I would go deeper into explaining not just what the requirements are, but why each one matters and how it connects to the rest of the system, so that both the developers building it and Liam as the client walk away with a clearer picture of how to actually use and maintain what they are paying for. Right now the section covers the necessary hardware, software, tools, and infrastructure, but I think it would benefit from more real world context, explaining what could go wrong without each requirement in place, so the reasoning behind each decision is just as clear as the requirement itself.

How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?

My approach was to really understand what DriverPass was trying to offer as a service, and then ask myself, "what would I want as a tool while doing this job?" For example, when I thought about the Secretary's day to day, I pictured someone who needs to quickly assign a driver and vehicle to a new appointment without digging through a mess of information, so that shaped how I approached the Assign Driver and Vehicle use case. Considering the user's needs is so important because a system built purely on assumptions ends up solving problems nobody actually has, while missing the ones people deal with every day. When you actually dig into what the end user needs, the system becomes something people want to use instead of something they're forced to tolerate.

How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

My approach to designing software starts with listening before building anything. I gather requirements directly from the people who will actually use and run the system, rather than assuming I already know what they need. From there, I like to map things out visually before writing a single line of code or technical spec, using process models to understand the flow of information and object models to understand the structure of the system itself. Going forward, I plan to keep using this combination of interviews, visual modeling, and constantly circling back to ask "does this actually serve the user," since that habit kept my designs grounded in real needs instead of assumptions throughout this project. I also plan to build in feedback loops early, checking my design against stakeholder needs at each stage rather than waiting until the end to find out something was misunderstood.
