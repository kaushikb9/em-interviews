# Engineering Leadership Interviews
Repository of interview questions for Engineering Leadership roles - Engineering Manager, Director of Engineering, VP Engineering and also senior IC roles

## Table of Contents
- [Roles and Expectations](#roles-and-expectations)
- [Interview Rounds](#interview-rounds)
    - [Screening](#screening)
    - [Programming](#programming)
    - [System Design](#design)
    - [Architecture](#architecture)
    - [Product Thinking](#product-thinking-and-execution)
    - [Management](#management)
    - [Culture Fit](#culture-fit)
    - [Offer](#offer)
- [More Reading](#more-reading)

## Roles and Expectations

**Early-stage, Seed Startups** - 5-30 engineers
- will be hiring you as their first EM, Head of Engineering or VP Engineering. You will be responsible for leading the entire tech team and be the key person for all tech decisioning including architecture, team structure and hiring strategy
- expect you to be extremely hands-on with programming because you will be their first senior management level hire. You will be seen as a pseudo CTO

**Series A/B Startups** - 30-100 engineers
- more like a tech lead with a lot of focus on delivery and also play the role of an architect whenever needed

**Series C/D Startups** - 100-500 engineers
- focus on lot more on overall understanding of system design, people management, processes and past experiences
- Lot of emphasis on scale, crushing business goals. There will be a lot of good structure in place with proper managment frameworks like OKRs

# Interview Rounds

## Screening
**Conducted by**: A peer or your future manager

- Brief introduction of the panel and candidate
- What was the best thing you built?
- What was the worst thing you built?
- How would you do it if you had to do it all over again?
- What was your team structure like? How did it change over time?
- How does code get deployed in your company? Who owns this?
- What are you looking for in your next job?

## Programming
**Conducted by**: Tech Leads

- [Find the smallest positive number missing from an unsorted array](problems/smallest-positive-number.md)
- [Build a travesal alogorithm to lookup for valid words in a matrix](problems/matrix-traversal-words.md)
- [Find the row in a matrix with minimum number of Os](problems/matrix-min-zeros.md)

## Design
**Conducted by**: Sr. Engineers, Architects, Principal Engineers

### Brainstorm with the Interviewer

- [Design a ledger app for shops](problems/ledger-app.md)
- Implement a data structure that will get preferences for the 100 recent users on your app. [Similar Problem](https://www.geeksforgeeks.org/lru-cache-implementation/)
- What would be the data structure to find top 10 hashtags in Twitter of any particular date?
- How would you implement a system that generates unique IDs for various objects in Twitter considering this is a highly distributed system? [Real life implementation](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html)
- How would you go about building a distributed load balancer from scratch?
- Assuming different lines of business, how will you build a unified dashbard for management financial metrics
- Build a system that will manage sale of limited products in e-commerce campaigns (Example - OnePlus, Redmi launches in Amazom)
- Build a URL shortner for an event management product that will be used to send ticket links in SMS
- Build a central notification system for a large e-commerce player
- Build a central distributed cache system for a large e-commerce player

### Take Home Problem Statements
These are usually projects which we need to implement at our own time and pace. Timelines are usually 3-5 days depending on complexity
- How would you implement Fast.com from scratch? Write a detailed Tech Spec
- Build a rule engine that will manage the workflows of a logistics company - implement the APIs
- Build discoverability capabilities for a data lake

## Architecture
**Conducted by**: CTO, Architects, Principal Engineers

### Concepts and Experience
- Challenging problems you worked on as an IC
- Monolith vs microservices. Pros and Cons. When to use what?
    - How is microservices better or worse purely based on scalibility (and not agility)
- DB sharding - what all should be tried out before you have to shard
- NoSQL vs RDBMS - What will be your strategy to choose a specific type of DB
- What are some examples of how you managed a P0 incident? What steps you took to ensure it is resolved and not repeated again
- Define the architecture to build an offline-first mobile-first data collection platform

## Product Thinking and Execution
**Conducted by**: Product Managers

### Product Problems
- As a PM in a cab hailing company, what would you build into the product so that you are ready for lockdown kind of situations if Covid 2.0 were to happen
- As a PM in a low cost Airline, what is the research that you will do to start a new route for your airline? How would you make the pitch? What would you go about measuring P&L and how would you price the ticket?

### Execution
- How do you prioritise between business requirements and tech debt?
- How do you plan - OKRs / Quarterly / Sprints?
- How do you measure the success of a project?
- How do you deal with production issues?

## Management
**Conducted by**: Founders, PMs, Hiring Manager

**Note**: This round is super critical for leadership roles. This is what differentiates managers from Senior IC Engineers

### You
- How did you get into leadership? What excites you about management?
- What is a event where you stepped up?
- As a manger, what is something you are extremely proud of?
- As a manger, what has been a difficult situation you had to deal with?
- Do you want to be an entrepreneur? What is stopping you right now?

### Team
- What was the composition of your team? According to what is an ideal team?
- Did you have to manage people more experienced than you?
- Have you hired people? What rounds would you conduct?
- What are some traits you would you look for when hiring?
- Are there examples of people in your team not performing? What action did you take?
- Were there instances when you had to let go of people?
- What are some of the things you did to build ownership?
- What are some of the things you tried to build ownership but failed?
- How do you give and take feedback?
- How do you decide which problems you need to jump on to - team vs yourself?

### Deliveries
- How do you manage multiple priorities?
- How do you deal with delays in timelines?

## Culture Fit 
**Conducted by**: Founders, HRBP

- How did people grow in your team? What are some good examples?
- What is a feedback you have received from the team?
- What is a feedback you have received from your manager?
- What is something you are proud of as an EM?
- How do you deal with a star performer who is too arrogant to adopt the new processes you have introduced

## Offer
- Your offer will always have a mix of fixed, variable and ESOPs
- Try to negotiate for overall value depending on the stage of the company. In case of ESOPs ask for number of options and current valuation
