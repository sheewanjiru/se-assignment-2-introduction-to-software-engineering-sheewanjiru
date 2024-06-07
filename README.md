[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15228126&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering: 
What is software engineering, and how does it differ from traditional programming?

It is the systematic application of engineering principles, methods and tools to the development and maintainance 
    of high quality softwar systems.

It differs from traditioal programming in that, software engineering  uses structured methodologies such as Waterfall and Agile
    to ensure a systematic approach to development (Documentation,formal testing and integration) while traditional pprogramming
    often follows an ad-hoc approach without a formalized process where individual programmers write and test code independently.
Softwafe engineering has comprehensive documentation which includes design specification, requirements documents, user manuals
    and maintainance guides while traditional programming has its documentation minimal where it focuses on the code itself.

Software Development Life Cycle (SDLC):
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

PHASES:
        Requirements-Involves gathering and documenting user needs and system requirements.
        Design- This is creating high level and detailed design for user interface.
        Implementation- Involves writing code and buiding the software according to the design specification.
        Testing- Conducting various tests to ensure the software meets quality standards and functional requirements.
        Deployment- This is releasing the software to the customers.
        Maintainance- Providing necessary supports and updates.

Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

MODELS
    Agile uses an iterative and incremental approach focused on flexibility, collaboration and responding to change and is used for large and more complex projects.
    Waterfall follows a sequential and linear approach with distinct phases which should be completed one after another and is suitable for short-term projects.

DIFERENCES
    Agile uses an iterative and incremental approach focused on flexibility, collaboration and responding to change where development is broken into smaller cycles while Waterfall follows a sequential and linear approach with distinct phases which should be completed one after another.
    Agile is preferred for projects that are large and more complex while waterfall is preferred for smaller and less complex projects that require frequent changes over time.

Requirements Engineering:
What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirement engineering is a phase in software development that involves the systematic identification, documentation and management of the requirements for software system to ensure it meets the users needs.

PROCESS
    Requirement elicitation- Involves gathering information ofwhat is needed from the software through interviews, surveys and questionnaries.
    Requirement analysis- Important to refine and structure the information gathered where feasibility and risk analysis are done.
    Requirement specification- To document the requirements in a clear and detailed manner.
    Requirement validation- To ensure the requirements are accurate and feasible through reviews, inspection and prototyping.
    Requirement management- To handle changes to the requirements throughout the project lifecycle.

IMPORTANCE
    Helps ensure a clear understanding of what the software will achieve.
    Assist in scope management where it prevents additional features to be added without corresponding increases in time, budget or resources.
    Ensures cost and time efficiency where accurate requirements help ensure that the project stays within the budget and on schedule.
    Through careful analysis and validation, requrement engineering helps identify potentialrisks as early as possible.
    Clear and detailed requirements provide a solid foundation for the subsequent phases for design, development and testing.

Software design principles:
Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

MODULARITY
    It is a practice of dividing a software system into separate independent modules where each module is encapsulates a specific piece of functionality.
    Each module should have a single, well-defined purpose or responsibity.
    Modules should have minimal dependancieson each other.
    Modules interact with each other through well defined interfaces thus changes that happen on one module do not affect another.

IMPROVEMENT ON MAINTAINABILITY
    It ensures that changes that happen on one module do not affect other modules hence reducing the risk of introducing bugs when modification is done.
    Helps in easy debugging and testing where modules are tested independently and makes it eay to identify and fix the bugs.
    Modules that are well defined can be reused across different projects reducing redudancy and promoting consistency.

IMPROVEMENT ON SCALABILITY
    Development is done separately where different teams work on separate modules simultaneously speeding the development process.
    Modules can be developed, tested and deployed incremently.
    Module system is flexible and adaptable where it adopt easily to changes in requirements and technology. 
    
Testing in Software Engineering:
Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

LEVELS OF SOFTWARE TESTING
    Unit testing - Test individual units or components of the software to ensure that each unit fuction is correct. 
    Intergration testing - Test the interaction between intergrated units or components where they ensure that units work together as intended.
    System testing - Test the entire intergrated software systemas a whole to ensure that the system meets the specified requirements. 
    Acceptance testing - Conducted to determine if the system meets the acceptance criteria and is ready for deployment.
                        Performed by the end-users.

Testing is crucial in that;
    Ensures that the software meets the specified requirements and behave as expected, works correctly and integrates well with all other parts.
    Testing helps identify defects and bugs in the software that could easily cause a fail where developers repair them.
    Testing helps ensure that the software is stable under different conditions and usage scenarios, providing a reliable experience for users.
    Security testing identifies potential vulnerabilities and weakness in the software that could be exploited by attackers.
    Testing provides valuable feedback to developers, allowing them to improve the code continuously.

Version Control Systems:
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version control system is a software tool that for tracking changes of source code overtime and coordinating work between team members.

IMPORTANCE
    Allows developers to track what changes were made, who made them and why thus maintainance of history and tracking of them.
    Enable multiple developers to work on the same project simultaneouslywithout overwriting on each other's work.
    Allows developers to create branches, which are independent lines of development which is useful for working with new features and experimenting them.
    It helps provide a safety net for storing allversions of the project.

EXAMPLES 
     GIT
        Distributed version control.
        Allows easy creation, management, and merging of branches.
        Operations for git are very fast since they are performed locally.
        Git supports various workflows,including centralized and distributed models.
    SUBVERSION(SVN)
        Centralised version control which is asingle central repository that users interact with.
        Allows users to lock their files, preventing others from editting them without consent.
    MERCURIAL 
        Allows every developer to have a complete copy of the repository like git.
        Designed for performance, especially  for large repositories.

Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

ROLES
    Project planning and scheduling -They define project scope, goals, create detailed plans and estimate time, cost and effort required.
    They carry out the assembling and leading the team where they assign them tasks and ensure they have the necessary tools.
    They identify potential risks and develop mitigation strategies to help assist solve the risk and also avoid them.
    Serve as the primary point of contact between the project team and the stakeholders.
    They track project progress against milestone and deliverables, prepare and present the reports to stakeholders.
    Managing stakeholder expectationsand ensuring theirneeds are met.

CHALLENGES
    Issues arise in managing changes in the project scope without disrupting the project timeline and budget.
    Resource constrains- Balancing the limited resources and ensuring optimal allocation of resources.
    Keeping up with rapidly evolving technologies and incorporating relevant updates into the project.
    Issues of identifying and managing unforseen risks that could impact project success.
    Time management - Ensuring projects timelines are adhered to  where managing deadlines might be difficult and ensuring timely delivery of the project phases.

Software Maintenance:
Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

 Software maintenance is the modification of a software after it has been deliveredto the customers to correct faults, improve performance and adapt the the product to a changed environment.

TYPES OF MAINTAINANCE ACTIVITIES
    Corrective Maintenance - Fixes bugs and errors found after a software is deployed.
    Adaptive maintenance - Modifies the software to work in a new and changed environment.
    Perfective maintenance - Enhances the software to improve performance or maintanability.
    Preventive maintenance - Modifies the software to detect and correct faults and enhancing security measures to prevent future issues.

IMPORTANCE OF MAINTAINANCE
    Ensures that the softwareremains useful and relevant as user needs and environment changes.
    Regular maintenance addresses user-reported bugs and improves the user experience by adding enhancement and new features.
    Maintenance helps address security vulnerablities that emerge over time, protecting the software and its users from potential risks.
    Maintenance activities improve the performance, reliability, and quality of the software ensuring it meets the required standard.
    Regular maintenance helps manage technical debt by addressing minor issues before they escalate into more difficult problems.

Ethical Considerations in Software Engineering:
What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

ETHICAL ISSUES
    Privacy and data security - It involves handling sensitive user data responsibly, ensuring it is protected against misuse where they ensure data cannot be shared without users consent.
    They should respect intellectual property rights by avoiding the use of pirated software, copying code without permission and violating open-source licenses.
    They need to ensure that the algorithm and AI systems are free from bias and do not discriminate against any individuals.
    The need to ensure that the software systems are secure and do not pose risks to users .
    They must provide users with control over their data and ensure that users understand how their data will be used.

HOW THEY ENSURE THEY ADHERE TO THE EHICAL STANDARDS
    Software engineers should regularly review and incorporate professional codes of ethics such as ACM in their daily practices.
    They should participate in ongoing ethical training and foster a culture of ethical awareness within their organization.
    They must communicate clearly with users about data usage, privacy policies, and potential risks associated with their software.
    They should conduct regular ehical reviews and  audits of their projects to identify and address ethical concerns.
    Adopting security best practices, such as regular audits and encryption, is essential for protecting user data.
    Establishing mechanisms for reporting unethical practices, such as anonymous reporting systems, helps maintain integrity and accounability. 

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
