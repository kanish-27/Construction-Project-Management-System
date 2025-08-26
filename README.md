# Construction-Project-Management-System
📌 The Construction Project Management System is a console-based Java application that helps manage construction projects in an efficient and structured manner. It enables users to add projects with details such as site, budget, and duration, assign contractors and workers, record and track expenses, and update project progress using a simple menu-driven interface. The system ensures effective monitoring of budgets, resources, and project status. Its key features include: adding new projects, assigning contractors/workers, updating project progress, recording expenses and comparing with budgets, and viewing detailed reports of all projects with resources and status. Built using core Java concepts like classes and object.


🔹 OOP Concepts Used

1.Encapsulation 🛡️

Each entity (Project, Contractor, Worker, Expense) can be represented as a class with private fields and public getters/setters.

Example: Project class with fields like siteName, budget, duration.

2.Abstraction 🎭

You can create abstract classes or interfaces to hide implementation details and expose only necessary methods.

Example: DatabaseOperations interface with methods addProject(), updateProject(), deleteProject().

3.Inheritance 🧬

Common properties can be inherited.

Example: Person class → inherited by Contractor and Worker.

4.Polymorphism 🔄

Same method name but different implementations.

Example: displayDetails() method in Project, Worker, and Contractor classes showing customized details.
