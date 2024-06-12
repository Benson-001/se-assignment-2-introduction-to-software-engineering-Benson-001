[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15247274&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software Engineering is a discipline that involves applying engineering principles and systematic approaches to the development, operation, and maintenance of software systems. It encompasses a set of methods, tools, and techniques used to design, implement, test, and manage software projects efficiently and reliably throughout their lifecycle.

What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC):
Software Engineering is the application of engineering principles to software development.

Software Development Life Cycle (SDLC) includes:

Requirements Gathering
Design
Implementation
Testing
Deployment
Maintenance

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:
Software Development Life Cycle (SDLC) Phases:

Requirements Gathering: In this phase, requirements are collected from stakeholders. It involves understanding what the software should do and documenting these requirements.

Design: The design phase involves creating a blueprint of how the software will be structured and function based on the gathered requirements. It includes architectural design, database design, and user interface design.

Implementation: During this phase, actual coding and development of the software occur based on the design specifications from the previous phase.

Testing: In the testing phase, the software is tested to ensure that it meets requirements and functions correctly. Testing includes unit testing, integration testing, system testing, and acceptance testing.

Deployment: Once the software is tested and approved, it is deployed to the production environment for end-users to use.

Maintenance: The maintenance phase involves making changes, fixing bugs, and updating the software to ensure it remains usable and relevant over time.

Agile vs. Waterfall Models:

Waterfall Model:

Sequential Approach: Waterfall follows a sequential approach where each phase (requirements, design, implementation, testing, deployment) flows downwards like a waterfall, and progress is made phase by phase.
Rigid Structure: Each phase is completed before moving to the next, making it less adaptable to changes once the project starts.
Requirements Defined Early: Requirements are gathered and defined upfront at the beginning of the project.
Documentation Heavy: Emphasizes extensive documentation for each phase.
Suitable for Well-Understood Projects: Best suited for projects where requirements are well-understood and unlikely to change significantly.
Agile Model:

Iterative and Incremental: Agile breaks the development process into small iterations or sprints. It focuses on delivering working software in shorter cycles.
Flexible and Adaptive: Agile allows for changes and adaptations throughout the development process based on feedback.
Collaborative: Encourages collaboration among cross-functional teams including developers, testers, and stakeholders.
Continuous Delivery: Software is delivered incrementally, with each iteration adding new features or enhancements.
Customer Feedback: Focuses on frequent customer feedback to ensure the delivered software meets customer needs.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Requirements Engineering:
Agile vs. Waterfall Models:

Agile Model:

Approach: Agile follows an iterative and incremental approach to software development.
Flexibility: Agile is highly flexible and allows for changes throughout the development process.
Iterations: Development is done in short iterations or sprints, with working software delivered at the end of each iteration.
Customer Involvement: Customer feedback is solicited and incorporated regularly.
Adaptability: Well-suited for projects where requirements are not fully known upfront or likely to change.
Preferred for: Projects with evolving requirements, startups, projects requiring quick releases and frequent customer feedback.
Waterfall Model:

Approach: Waterfall follows a sequential, linear approach to software development.
Phases: Progression through distinct phases: requirements, design, implementation, testing, deployment.
Rigidity: Less flexible, changes are difficult and costly once a phase is completed.
Documentation: Emphasizes extensive documentation at each phase.
Suitable for: Projects with well-understood and stable requirements, large-scale projects with clear milestones and deliverables, projects with regulatory compliance requirements.
Key Differences:

Flexibility: Agile is flexible and allows changes, while Waterfall is more rigid with changes being difficult once a phase is completed.
Customer Involvement: Agile involves frequent customer interaction, while Waterfall has less customer involvement after the initial requirements phase.
Iterations: Agile works in iterative cycles, while Waterfall progresses linearly through phases.
Documentation: Waterfall requires extensive documentation at each phase, while Agile focuses more on working software over documentation.
Preferred Scenarios:

Agile: Preferred for projects with changing or not fully known requirements, where rapid iterations and frequent customer feedback are crucial.
Waterfall: Preferred for projects with stable and well-understood requirements, where a sequential approach with extensive documentation is necessary, such as large-scale enterprise projects or projects with regulatory compliance requirements.
Requirements Engineering:

Requirements Engineering is the process of eliciting, documenting, validating, and managing software requirements throughout the project lifecycle.

Elicitation: Involves gathering requirements from stakeholders through interviews, workshops, surveys, etc.
Documentation: Requirements are documented in detail to ensure a clear understanding of what the software should do.
Validation: Ensuring that gathered requirements are complete, consistent, and meet stakeholders' needs.
Management: Tracking changes to requirements, prioritizing them, and ensuring they are implemented correctly.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:
Requirements Engineering:

Requirements Engineering is the process of eliciting, documenting, validating, and managing requirements for software systems. It's a crucial phase in the software development lifecycle where the needs and constraints of stakeholders are identified and translated into a set of clear and concise requirements for the software to be developed.

Process:

Elicitation: Gathering requirements from stakeholders including customers, users, and other relevant parties. Techniques like interviews, surveys, workshops, and observations are used to understand their needs.

Analysis: Analyzing gathered requirements to ensure they are clear, complete, consistent, and feasible. This involves identifying any conflicts or ambiguities in requirements.

Specification: Documenting requirements in a formal and structured way. This may include use cases, user stories, functional and non-functional requirements, etc.

Validation: Validating requirements to ensure they meet the needs of stakeholders. This involves reviewing requirements with stakeholders and getting their confirmation.

Management: Managing changes to requirements throughout the project lifecycle. This includes tracking changes, prioritizing requirements, and ensuring that implemented features align with the agreed-upon requirements.

Importance in the Software Development Lifecycle:

Understanding User Needs: Requirements engineering ensures a clear understanding of what the software should accomplish from the perspective of users and stakeholders.

Basis for Development: Requirements serve as the foundation for software design, implementation, and testing. They guide the entire development process.

Minimizing Rework: Clear and well-defined requirements help in reducing rework and costly changes later in the development process.

Communication: It facilitates communication between stakeholders, developers, and testers by providing a common understanding of what needs to be built.

Risk Management: Properly managed requirements help in identifying and mitigating risks early in the project.

Customer Satisfaction: Meeting the stated requirements increases the likelihood of delivering a product that satisfies customers.

Software Design Principles:

Software Design Principles are fundamental concepts used to guide software design to produce maintainable, modular, and efficient software systems.

Some key software design principles include:

DRY (Don't Repeat Yourself): Avoid duplication of code by abstracting common functionality into reusable components or functions.

SOLID Principles:

S - Single Responsibility Principle: A class should have only one reason to change.
O - Open/Closed Principle: Software entities should be open for extension but closed for modification.
L - Liskov Substitution Principle: Subtypes should be substitutable for their base types.
I - Interface Segregation Principle: Clients should not be forced to depend on interfaces they do not use.
D - Dependency Inversion Principle: High-level modules should not depend on low-level modules; both should depend on abstractions.
KISS (Keep It Simple, Stupid): Keep the design simple and straightforward. Complex solutions should be avoided unless absolutely necessary.

YAGNI (You Ain't Gonna Need It): Do not add functionality until it's actually needed. Avoid speculative or premature features.

Separation of Concerns: Divide the software into distinct features/modules with each addressing a separate concern.

Abstraction: Hide complex implementation details behind simple interfaces or abstraction layers.

Encapsulation: Encapsulate related data and behavior into classes and hide internal details from outside.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:
Modularity in Software Design:

Modularity in software design is the practice of dividing a software system into separate, independent modules or components, each responsible for a specific functionality or feature. Each module should have well-defined interfaces that allow it to interact with other modules.

Key aspects of modularity:

Encapsulation: Modules encapsulate related data and behavior, hiding internal details and exposing only necessary interfaces to interact with other modules.

High Cohesion: Modules should have high cohesion, meaning that elements within the module are closely related and focused on a single task or responsibility.

Low Coupling: Modules should be loosely coupled, meaning they are independent of each other and changes in one module should have minimal impact on others.

Benefits of Modularity:

Maintainability: Modularity makes it easier to maintain software because changes can be localized to specific modules without affecting the entire system. Developers can focus on modifying or fixing a particular module without worrying about the entire codebase.

Scalability: Modularity facilitates scalability by allowing the system to grow by adding or modifying modules as needed. New features can be implemented by adding new modules without extensively modifying existing code.

Reusability: Modular design encourages reusability of code. Well-defined modules can be reused in different parts of the software or even in other projects, saving time and effort in development.

Parallel Development: Different teams or developers can work on different modules simultaneously without interfering with each other, speeding up the development process.

Debugging and Testing: Modular systems are easier to debug and test since each module can be tested independently, leading to more reliable software.

Improving Maintainability and Scalability:

Maintainability: Modularity allows for easier maintenance by isolating changes within specific modules, reducing the risk of unintended side effects. Developers can understand, update, and debug smaller, well-defined modules more efficiently.

Scalability: Modularity enables easier scalability as new features can be added by creating new modules or extending existing ones. It also allows for easier distribution of work across teams, promoting parallel development efforts.

Testing in Software Engineering:

Testing in Software Engineering involves the process of verifying and validating that a software system meets requirements and behaves as expected.

Types of Testing:

Unit Testing: Testing individual units or components of the software in isolation to ensure they work correctly.

Integration Testing: Testing the interaction between integrated units or components to ensure they work together as expected.

System Testing: Testing the entire system as a whole to verify that it meets specified requirements.

Acceptance Testing: Testing to verify if the software meets the acceptance criteria and is ready for deployment.

Importance of Testing:

Bug Detection: Testing helps in identifying and fixing bugs and errors in the software early in the development process.

Quality Assurance: Testing ensures that the software meets quality standards and behaves as expected under different conditions.

Customer Satisfaction: Thorough testing leads to higher-quality software, which increases customer satisfaction.

Risk Reduction: Testing helps in reducing risks associated with software failures or malfunctions.

Maintenance: Well-tested software is easier to maintain and modify over time.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Version Control Systems:
Levels of Software Testing:

Unit Testing:

Purpose: Testing individual units or components of the software in isolation.
Scope: Tests focus on small, specific parts of the code, such as functions or methods.
Tools: Automated testing frameworks like JUnit, NUnit, or pytest are commonly used.
Benefits: Helps in identifying bugs early, ensures individual units work as expected, and facilitates refactoring.
Integration Testing:

Purpose: Testing the interaction between integrated units or components.
Scope: Tests focus on verifying communication and data exchange between modules.
Tools: Integration testing frameworks, mocking libraries, and APIs are used.
Benefits: Ensures that integrated modules work together correctly, detects interface errors, and validates system behavior.
System Testing:

Purpose: Testing the entire software system as a whole.
Scope: Tests cover end-to-end functionality, including user interfaces, databases, and external dependencies.
Tools: Automated testing tools, manual testing procedures, and user acceptance testing (UAT).
Benefits: Verifies that the system meets specified requirements, identifies functional and non-functional issues, and ensures system readiness for deployment.
Acceptance Testing:

Purpose: Testing to verify if the software meets user acceptance criteria.
Scope: Tests are based on real-world scenarios and user workflows.
Tools: Often manual testing is used, but automated acceptance testing frameworks like Selenium may be employed.
Benefits: Validates that the software meets user expectations, ensures it aligns with business goals, and confirms readiness for deployment.
Why Testing is Crucial in Software Development:

Bug Detection: Testing helps in identifying and fixing bugs and errors in the software, preventing issues from reaching production.

Quality Assurance: Ensures that the software meets quality standards and behaves as expected under various conditions.

Risk Reduction: Testing reduces the risk of software failures, security vulnerabilities, and performance issues.

Customer Satisfaction: Thorough testing leads to higher-quality software, which increases customer satisfaction and trust in the product.

Cost-Effectiveness: Detecting and fixing defects early in the development process is more cost-effective than addressing them later or after deployment.

Compliance: Testing ensures that software meets regulatory and compliance requirements.

Continuous Improvement: Testing provides feedback for continuous improvement of the software development process.

Version Control Systems:

Version Control Systems (VCS) are tools used to manage changes to source code over time. They track modifications, facilitate collaboration among developers, and enable reverting to previous versions if needed.

Key Concepts:

Repository: A central storage location where all versions of files are kept along with metadata.

Commit: Saving changes to the repository along with a descriptive message.

Branching: Creating a separate line of development to work on features or fixes independently.

Merging: Combining changes from one branch into another.

Conflict Resolution: Handling conflicts that occur when changes overlap between branches or contributors.

Benefits of Version Control Systems:

History Tracking: VCS keeps a complete history of changes, who made them, and when, allowing easy rollback if needed.

Collaboration: Multiple developers can work on the same codebase concurrently without interfering with each other's work.

Code Backup: Acts as a backup mechanism, ensuring that code is not lost even if a local copy is deleted.

Experimentation: Developers can create branches to experiment with new features or fixes without affecting the main codebase.

Code Reviews: Facilitates code reviews by providing a platform to view and discuss changes before they are merged into the main codebase.

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Software Project Management:
Version Control Systems (VCS):

Version Control Systems (VCS) are tools that help manage changes to source code over time. They track modifications, enable collaboration among developers, and provide mechanisms to revert to previous versions if needed.

Importance in Software Development:

History Tracking: VCS keeps a history of changes, who made them, and when, allowing developers to understand the evolution of the codebase.

Collaboration: Multiple developers can work on the same project concurrently without conflicts, as VCS manages merging changes.

Backup and Recovery: Acts as a backup mechanism, ensuring that code is not lost even if local copies are damaged or deleted.

Experimentation: Developers can create branches to work on new features or experiments without affecting the main codebase.

Code Reviews: Facilitates code reviews by providing a platform to view, comment, and discuss changes before they are merged.

Popular Version Control Systems:

Git:

Features: Distributed version control, branching and merging capabilities, lightweight branching, offline support, fast performance.
Examples: GitHub, GitLab, Bitbucket.
Subversion (SVN):

Features: Centralized version control, atomic commits, directory versioning, tagging and branching.
Examples: Apache Subversion.
Mercurial (Hg):

Features: Distributed version control, easy to learn, fast performance, branching and merging.
Examples: Bitbucket, Kiln.
Perforce (Helix Core):

Features: Centralized version control, support for large binary files, fine-grained access control.
Examples: Perforce Helix Core.
Microsoft Team Foundation Version Control (TFVC):

Features: Centralized version control integrated with Azure DevOps, branching and merging, code reviews.
Examples: Azure DevOps Services (formerly known as Visual Studio Team Services).
Software Project Management:

Software Project Management involves planning, organizing, and controlling resources to successfully complete software development projects within constraints like time, budget, and scope.

Key Aspects:

Planning: Defining project objectives, scope, requirements, schedule, and resources needed.

Scheduling: Creating timelines, milestones, and allocating tasks to team members.

Resource Management: Assigning roles and responsibilities, managing human resources, and ensuring availability of tools and infrastructure.

Risk Management: Identifying, analyzing, and mitigating risks that may impact project success.

Communication: Facilitating communication among team members, stakeholders, and clients.

Quality Assurance: Ensuring that the software meets quality standards and adheres to requirements.

Monitoring and Control: Tracking project progress, managing changes, and making adjustments as needed to keep the project on track.

Tools and Techniques:

Project Management Software: Tools like Jira, Trello, Asana.
Agile Methodologies: Scrum, Kanban, XP.
Documentation: Project plans, schedules, requirements documents.
Communication Tools: Slack, Microsoft Teams.
Version Control Systems: Git, SVN.

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:
Role of a Software Project Manager:

A Software Project Manager plays a crucial role in overseeing the planning, execution, and delivery of software projects. They are responsible for ensuring that projects are completed successfully within scope, time, and budget constraints while meeting quality standards and stakeholder expectations.

Key Responsibilities:

Project Planning: Define project scope, objectives, requirements, and create a detailed project plan including timelines, milestones, and resource allocation.

Resource Management: Assign tasks, allocate resources, and manage the project team to ensure everyone is working effectively towards project goals.

Risk Management: Identify potential risks, develop risk mitigation strategies, and monitor and control risks throughout the project lifecycle.

Communication: Facilitate communication among team members, stakeholders, and clients, providing regular updates on project progress, milestones, and issues.

Quality Assurance: Ensure that the software meets quality standards by implementing quality control processes and conducting reviews and testing.

Budget and Cost Management: Monitor project budget, track expenses, and ensure that the project stays within budgetary constraints.

Stakeholder Management: Manage relationships with stakeholders, gather requirements, address concerns, and ensure stakeholder satisfaction.

Change Management: Handle change requests effectively, assess their impact on project scope, schedule, and budget, and communicate changes to relevant stakeholders.

Challenges Faced:

Scope Creep: Managing changes in project scope without affecting the project timeline and budget.

Resource Allocation: Balancing resource availability and project demands, especially in large teams or with distributed teams.

Time Management: Ensuring that the project stays on schedule despite unexpected delays or changes.

Risk Management: Identifying and mitigating risks that may impact project success, such as technical challenges, resource constraints, or external dependencies.

Communication: Keeping all stakeholders informed and engaged, managing expectations, and resolving conflicts.

Quality Control: Ensuring that the software meets quality standards while balancing time and resource constraints.

Adapting to Change: Managing changes in requirements, technology, or market conditions while keeping the project on track.

Team Collaboration: Fostering collaboration and teamwork among team members, especially in distributed or remote teams.

Software Maintenance:

Software Maintenance involves modifying, updating, and enhancing software to ensure it continues to meet user needs and remains relevant over time.

Types of Software Maintenance:

Corrective Maintenance: Fixing bugs and errors discovered in the software during its use.

Adaptive Maintenance: Making changes to the software to adapt it to new environments, platforms, or requirements.

Perfective Maintenance: Enhancing the software to improve performance, usability, or add new features based on user feedback.

Preventive Maintenance: Making changes to prevent future problems or improve maintainability.

Importance of Software Maintenance:

Bug Fixing: Ensures that software remains functional and reliable by fixing issues as they arise.

Enhancements: Keeps the software competitive and up-to-date by adding new features or improving existing ones.

Customer Satisfaction: Maintains user satisfaction by addressing their needs and concerns.

Security: Updates and patches help in addressing security vulnerabilities and keeping the software secure.

Longevity: Extends the life of software systems, maximizing return on investment.

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Ethical Considerations in Software Engineering:
Software Maintenance:

Software Maintenance involves the modification, updating, and enhancement of software to ensure it continues to meet user needs and remains effective over time. It is an essential part of the software lifecycle aimed at preserving and improving software after it has been deployed.

Types of Maintenance Activities:

Corrective Maintenance:

Purpose: Fixing bugs and errors discovered during the use of the software.
Activities: Identifying, diagnosing, and repairing defects to restore the software to its intended functionality.
Adaptive Maintenance:

Purpose: Modifying the software to adapt it to changes in the environment, platforms, or external dependencies.
Activities: Making changes to support new hardware, software platforms, operating systems, or regulatory requirements.
Perfective Maintenance:

Purpose: Enhancing the software to improve performance, usability, or add new features based on user feedback.
Activities: Adding new features, optimizing performance, enhancing user interface, and improving user experience.
Preventive Maintenance:

Purpose: Making changes to prevent future problems, improve maintainability, and avoid potential issues.
Activities: Refactoring code, improving documentation, optimizing resources, and addressing known risks.
Importance of Maintenance in the Software Lifecycle:

Sustaining Functionality: Maintenance ensures that software remains functional and reliable by fixing bugs and errors discovered during its use.

Adapting to Change: It allows software to adapt to changing environments, technologies, and user needs over time.

Enhancing Value: Maintenance adds value to software by adding new features, improving performance, and enhancing user experience, making it more competitive in the market.

Security: Regular maintenance helps in addressing security vulnerabilities and applying patches to keep the software secure from potential threats.

Longevity: Maintenance extends the life of software systems, maximizing return on investment and reducing the need for costly replacements.

Customer Satisfaction: By addressing issues promptly and continuously improving the software, maintenance contributes to higher customer satisfaction and loyalty.

Ethical Considerations in Software Engineering:

Ethical considerations in software engineering involve recognizing and addressing ethical implications and responsibilities in the development and use of software.

Key Ethical Considerations:

Privacy: Respecting users' privacy rights and protecting their personal data from unauthorized access or misuse.

Security: Ensuring that software systems are secure and resilient against cyber threats to protect user data and prevent harm.

Transparency: Providing transparency about how user data is collected, stored, and used within software applications.

Fairness: Ensuring that software does not discriminate against users based on factors such as race, gender, religion, or nationality.

Accuracy: Striving for accuracy and reliability in software outputs, especially in critical systems like medical or financial software.

Intellectual Property: Respecting intellectual property rights, including proper use of open source software and avoiding plagiarism or unauthorized use of code.

Accessibility: Ensuring that software is accessible to all users, including those with disabilities, and does not create barriers to access.

Environmental Impact: Considering the environmental impact of software development practices and optimizing energy usage where possible.

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Submission Guidelines:
Ethical Issues in Software Engineering:

Privacy Concerns: Collecting and handling user data without appropriate consent or protecting sensitive information inadequately.

Security Vulnerabilities: Developing software with known security flaws or backdoors that can be exploited by malicious actors.

Bias in Algorithms: Designing algorithms that perpetuate biases based on race, gender, or other protected characteristics, leading to unfair outcomes.

Intellectual Property: Violating intellectual property rights, such as using copyrighted code without permission or improperly licensing software.

Deceptive Practices: Misleading marketing practices, false advertising, or hiding information about the software's capabilities or limitations.

Unintended Consequences: Creating software that may have unintended negative consequences, such as job displacement or environmental harm.

Surveillance and Monitoring: Developing software used for surveillance purposes without adequate safeguards for privacy and civil liberties.

Accessibility: Failing to make software accessible to users with disabilities, excluding them from full participation.

Environmental Impact: Ignoring the environmental impact of software development practices, such as excessive energy consumption or e-waste generation.

Adhering to Ethical Standards:

Education and Awareness: Stay informed about ethical issues in software engineering through education, training, and staying updated with industry standards and guidelines.

Ethical Guidelines: Adhere to established ethical guidelines and codes of conduct, such as ACM's Code of Ethics and Professional Conduct or IEEE's Code of Ethics.

User Privacy and Data Protection: Prioritize user privacy and data protection by implementing strong security measures, obtaining user consent for data collection, and anonymizing data whenever possible.

Bias Mitigation: Actively work to identify and mitigate biases in algorithms and software systems to ensure fair and equitable outcomes.

Open Communication: Foster open communication with stakeholders and team members about ethical concerns and advocate for ethical practices within the organization.

Transparency: Be transparent about software capabilities, limitations, and potential risks to users and stakeholders.

Regular Ethics Reviews: Conduct regular ethics reviews of software projects to identify and address potential ethical issues early in the development process.

Continuous Learning: Stay updated on ethical issues, best practices, and emerging technologies to ensure ethical decision-making throughout the software development lifecycle.

Whistleblowing: Speak up if you become aware of unethical practices within your organization and report concerns through proper channels.

Submission Guidelines:

Your submission should be clear, concise, and relevant to the topic.
Ensure your submission is free from offensive or inappropriate content.
Provide accurate information and avoid speculation or unsupported claims.
Feel free to ask if you need further clarification or have specific questions

Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
