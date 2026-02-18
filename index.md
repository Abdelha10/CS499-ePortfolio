# Welcome to My CS499 ePortfolio

This site showcases my CS499 projects.

This repository showcases two application projects developed during my Computer Science coursework and personal learning. Together, these projects demonstrate my ability to design software systems using appropriate algorithms, data structures, and modern programming practices, while solving real-world problems.

The projects focus on different but complementary aspects of software engineering: data persistence and safety, efficient data organization, and clean architectural design. One project emphasizes mobile application development and database integrity, while the other highlights algorithmic decision-making and data structure selection for managing complex relationships.

---

## Table of Contents

- [Weight Tracking Android Application](#-weight-tracking-android-application)
- [Clientele Management Application](#-clientele-management-application)
- [Purpose of These Projects](#-purpose-of-these-projects)
- [Projects](#projects)
- [Code Review](#code-review)
- [Professional Self-Assessment](#professional-self-assessment)
  
## Professional Self-Assessment

Developing this ePortfolio and completing my computer science program has helped me clearly define my strengths, professional values, and career direction. My strongest areas are building practical software that balances usability, data integrity, and maintainability. Across coursework and enhancement projects, I learned to approach software as a full lifecycle process: requirements, implementation, testing, iteration, and communication. This process has prepared me to enter the field as a more employable developer who can contribute technically and collaborate effectively.

I grew significantly in **team collaboration** by working through milestone-based projects, peer feedback cycles, and code review activities. Even when projects were individually implemented, the workflow mirrored team practice: writing testable code, documenting decisions, and refining implementations after critique. For example, in my enhanced work, I used iterative refactoring and validation to improve reliability and maintainability rather than treating the first solution as final. This reflects how I plan to work in professional engineering teams: transparent, iterative, and quality-focused.

My ability to **communicate with stakeholders** improved through project narratives, milestone submissions, and technical explanations designed for both technical and non-technical audiences. I practiced translating implementation details into outcomes stakeholders care about, such as reliability, performance, and user experience. Outside the two ePortfolio artifacts, my Wear OS task-capture project and supporting documentation (scope, requirements, risk register, and feasibility analysis) strengthened this skill by requiring clear tradeoff communication around battery, responsiveness, and usability.

In **data structures and algorithms**, I demonstrated intentional structure selection based on problem constraints. In the clientele management artifact, I used `HashMap`-based services to enforce unique IDs and improve lookup efficiency over linear searches. In the weight tracking work, I focused on controlled list handling, ordering, and data validation to ensure consistent behavior in user-facing operations. These experiences reinforced my ability to reason about complexity, correctness, and scalability in real applications.

In **software engineering and database design**, I built and enhanced applications with clear separation of concerns between UI, business logic, and persistence. The weight tracking artifact demonstrates this with Android/Kotlin components and SQLite-backed data operations for user and weight-entry management. Beyond the artifact itself, my recent Wear OS work expanded this competency through MVVM architecture, Room-based data modeling, repository patterns, and incremental feature delivery. Together, these examples show readiness to design systems that are maintainable and evolvable.

For **security**, I developed a stronger habit of minimizing risk through validation, permission handling, and defensive programming. In my projects, I enforced uniqueness constraints, validated user input, and handled permission-sensitive features (such as notifications and SMS-related workflows) with explicit user consent paths. In newer work, I also applied secure mobile practices such as immutable pending intents, non-exported receivers, and constrained alarm/notification behavior. These choices reflect my professional value of building trustworthy software by default.

As a whole, the portfolio artifacts fit together as a progression of my computer science capabilities. The clientele management artifact highlights algorithm and data-structure reasoning; the weight tracking artifact demonstrates applied software engineering, persistence, and user-focused mobile design; and my additional enhancement work broadens the picture with modern architecture, risk-aware planning, and security-conscious implementation. Together, they present a complete profile: I can analyze requirements, choose appropriate technical strategies, implement and test robust solutions, and communicate those solutions effectively to stakeholders.

## 📱 Weight Tracking Android Application

The first project is an Android weight tracking application, originally developed in Java and later fully migrated to Kotlin. The app allows users to create an account, log in, or continue as a guest, and securely record weight entries that are permanently stored in a local SQLite database. Users can review their historical data to track progress over time and delete entries when needed.

### Key Features & Technologies:
- **Modern Android development** using Kotlin
- **Algorithms and data structures**, including controlled use of lists and immutability
- **Database design and persistence** with SQLite
- **Improved safety and reliability** through Kotlin's null-safety and read-only collection interfaces
- **Separation of concerns** between data storage, business logic, and UI

### Migration Benefits:
The migration from Java to Kotlin significantly improved the application's robustness, readability, and maintainability while reducing the risk of runtime errors and unintended data modification.

---

## 👥 Clientele Management Application

The second project is a clientele management application designed to manage clients, tasks, services, and appointments. This application focuses on efficient data access and organization using HashMaps to associate unique identifiers with domain objects.

### Key Features & Technologies:
Rather than relying on sequential searches through lists, this project uses HashMaps to:
- **Enforce unique identifiers** for clients, tasks, and appointments
- **Enable fast data retrieval** with constant-time average lookup
- **Model real-world relationships** between entities in a scalable way
- **Prevent duplicate or inconsistent** data entries

This project highlights my understanding of algorithmic efficiency, data modeling, and the practical trade-offs involved in selecting the right data structures for a given problem.

---

## 🎯 Purpose of These Projects

Together, these applications demonstrate my ability to:
- **Apply algorithms and data structures** to real software problems
- **Choose appropriate data structures** based on performance and design constraints
- **Write safer, more maintainable code** using modern language features
- **Design applications** that balance usability, integrity, and efficiency

## Projects
### Original Artifacts
- [Download and View Artifact One Code](Original%20Artifacts/Client%20Management%20-%20Original.zip)
- [Download and View Artifact Two Code]("Original%20Artifacts/Weight%20Tracking%20-%20Original.zip")

  
### Enhanced Artifacts
- [Download and View Artifact One Code]("Enhanced%20Artifacts/Client%20Management%20-%20Enhanced.zip")
- [Download and View Artifact Two Code]("Enhanced%20Artifacts/Weight%20Tracking%20-%20Enhanced.zip")
- [Download/View Documentation]("CS499")

## Code Review 
- [Watch my code review here](https://youtu.be/pjm5ZuDR_iM)
