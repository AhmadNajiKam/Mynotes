- ## Define software engineering and explain the responsibilities of a software engineer.
 * **Software Engineering Definition**: The systematic approach to designing and developing software.
 - **Responsibilities of Software Engineers**: Includes designing, building, maintaining software systems, writing and testing code, and consulting with stakeholders.
 - **Software Development Lifecycle (SDLC)**: A framework guiding the steps needed to develop high-quality software.
 - **Differences Between Software Engineers and Developers**: Engineers focus on the broader system, while developers implement specific functionalities.
   
- ## Discuss key advantages of applying the software development lifecycle (SDLC) when developing enterprise software.

* ***Software Development Life Cycle (SDLC)** is a systematic process for developing high-quality software within a predictable timeframe and budget. Key points include:

- **Phases of SDLC**: It includes planning, design, and development, which can be iterative.
- **History**: Developed in the mid-1960s to manage complex software projects, initially using the "waterfall method."
- **Advantages**:
    - Provides a structured process, improving efficiency and reducing risks.
    - Clearly defined phases enhance communication among stakeholders.
    - Allows for iteration, accommodating changing requirements.
    - Clearly defined roles for team members reduce conflicts.

- ## Describe each phase of the SDLC
1. **Planning**: Requirements are gathered, analyzed, and documented. Prototypes may be created to clarify requirements.
2. **Design**: The software architecture is developed based on the requirements, and a design document is created.
3. **Development**: Coding begins using the design document, with tasks assigned to developers.
4. **Testing**: The code is tested for stability and security, with bugs reported and fixed.
5. **Deployment**: The application is released to users, often in stages.
6. **Maintenance**: Post-deployment, feedback is collected, and any issues or enhancements are addressed.

- Analyze common software engineering processes required for building-high quality software.
* **Requirements Gathering**: Collecting and documenting software requirements, including functional and non-functional categories.
- **Design**: Transforming requirements into a structured solution that developers can implement.
- **Coding for Quality**: Following coding practices to ensure maintainability, readability, and efficiency.
- **Testing**: Verifying that the software 2er acceptance).
- **Releases**: Different types of software releases (alpha, beta, general availability) for various audiences.
- **Documentation**: Providing both technical and user documentation to explain software functionality.

- Explain the requirement gathering process.
  - **Requirement Gathering Process**: This involves six steps: identifying stakeholders, establishing goals and objectives, eliciting requirements, documenting them, analyzing and confirming, and prioritizing requirements.
  **Requirement** gathering steps are : 
  1. **Identifying Stakeholders**:
    
    - **What it means**: Find out who will be affected by the software. This includes people like decision-makers, end-users, and support staff.
    - **Why it matters**: Involving the right people ensures that all perspectives are considered.
2. **Establishing Goals and Objectives**:
    
    - **What it means**: Define what you want to achieve with the software.
        - **Goals**: Broad outcomes (e.g., improve customer satisfaction).
        - **Objectives**: Specific actions to reach those goals (e.g., reduce response time by 20%).
    - **Why it matters**: Clear goals and objectives guide the project and help measure success.
3. **Eliciting Requirements**:
    
    - **What it means**: Gather detailed needs and expectations from stakeholders through methods like interviews, surveys, or questionnaires.
    - **Why it matters**: This step helps to understand what features and functions the software must have.
4. **Documenting Requirements**:
    
    - **What it means**: Write down the gathered requirements in a clear and organized way.
    - **Why it matters**: Documentation ensures everyone has a reference point and understands what is needed.
5. **Analyzing and Confirming Requirements**:
    
    - **What it means**: Review the documented requirements to check for clarity, consistency, and completeness. Share them with stakeholders for approval.
    - **Why it matters**: This step ensures that everyone agrees on what the software should do before moving forward.
6. **Prioritizing Requirements**:
    - **What it means**: Rank the requirements based on their importance (e.g., "must-have," "highly desired," "nice to have").
    - **Why it matters**: Prioritization helps focus on the most critical features first, especially if time or resources are limited.

- Differentiate between a User Requirement Specification (URS), a Software Requirement Specification (SRS), and a System Requirement Specification (SysRS) document.
  
  
- **Types of Specifications**:
    
    - **User Requirement Specification (URS)**: Captures user stories and expectations.
    - **Software Requirement Specification (SRS)**: Details functionalities, performance benchmarks, and requirements categorized into functional, external interface, system features, and non-functional requirements.
    - **System Requirement Specification (SysRS)**: Outlines broader system capabilities, interfaces, and requirements beyond just software.
- **Goals vs. Objectives**: Goals are broad, long-term outcomes, while objectives are specific, measurable actions to achieve those goals.
  
- Compare and contrast waterfall, V-shape model, and agile methods of software development.
  - **Software Development Methodologies**: The course discusses three common approaches: **Waterfall**, **V-shape model**, and **Agile**.
    
- **Waterfall Method**:
    
    - **Sequential**: Each phase must be completed before the next begins.
    - **Pros**: Easy to understand and plan; clear roles for team members.
    - **Cons**: Lacks flexibility; difficult to accommodate changes once phases are completed.
- **V-shape Model**:
    
    - **Sequential**: Similar to Waterfall but emphasizes verification and validation phases.
    - **Pros**: Simple and structured; saves time on testing.
    - **Cons**: Rigid; changes are hard to implement after testing begins.
- **Agile Method**:
    
    - **Iterative**: Focuses on short cycles (sprints) for development and feedback.
    - **Pros**: Flexible; accommodates changing requirements; continuous stakeholder feedback.
    - **Cons**: Challenging upfront planning; scope may be unclear.
- **Key Differences**: Traditional methods (Waterfall and V-shape) are sequential, while Agile is iterative, allowing for ongoing adjustments and customer involvement.

  ## Software versioning 
  - **Software Versioning**: Indicates the history of changes, updates, and patches to software.
- **Version Number Format**: Typically consists of 2 to 4 number sets separated by periods (e.g., 1.0, 2.3.1.4).
    - **Major Changes**: First number (e.g., 2.x).
    - **Minor Changes**: Second number (e.g., x.3).
    - **Patches**: Third number (e.g., x.x.1).
    - **Build Number**: Fourth number (e.g., x.x.x.4).
- **Beta Versions**: May have numbers lower than 1 (e.g., 0.9).
- **Compatibility Issues**: Newer versions may not always be compatible with older ones, but some software is designed to be backwards compatible.

- Distinguish between functional, non-functional, and regression testing.
  - **Definition of Software Testing**:
    
    - Integrates quality checks throughout the software development cycle.
    - Ensures software matches expected requirements and is error-free.
- **Test Cases**:
    
    - Written to verify functionality and ensure requirements are satisfied.
    - Contains steps, inputs, data, and expected outputs.
    - Should be written after requirements are finalized.
- **Types of Testing**:
    
    - **Functional Testing**:
        - Involves black box testing (no access to source code).
        - Focuses on inputs and corresponding outputs.
        - Ensures usability and accessibility.
    - **Non-Functional Testing**:
        - Tests attributes like performance, security, scalability, and availability.
        - Answers questions about application behavior under stress, user load, and disaster recovery.
    - **Regression Testing**:
        - Confirms recent changes do not adversely affect existing functionality.
        - Conducted when there are changes in requirements or defects are fixed.
- **Testing Levels**:
    - **Unit Testing**:
        - Verifies functionality of specific code sections (function level).
        - Performed by developers during the development phase.
    - **Integration Testing**:
        - Identifies errors when combining independent code modules.
        - Exposes bugs in communication between modules.
    - **System Testing**:
        - Conducted on a complete, integrated system.
        - Validates compliance with specified requirements.
    - **Acceptance Testing**:
        - Formal testing against user needs and business processes.
        - Usually performed by customers or stakeholders.
- Identify and describe different types of documentation.
1. **Product Documentation**: Relates to the functionality of the software product. It includes:
    
    - **Requirements Documentation**: Describes expected features and functionality, intended for the development team.
    - **Design Documentation**: Explains how the software will be built, including conceptual and technical designs.
    - **Technical Documentation**: Contains comments in the code and working papers that explain how the code works.
    - **Quality Assurance Documentation**: Pertains to the testing strategy, including test plans and metrics.
    - **User Documentation**: Aimed at end-users, explaining how to operate the software, including manuals and FAQs.
2. **Process Documentation**: Describes how to complete a task and includes **Standard Operating Procedures (SOPs)**, which provide detailed, step-by-step instructions for specific tasks within an organization.

- Compare and contrast the common roles and responsibilities on a software engineering project.
  1. **Project Manager / Scrum Master**
    
    - **Responsibilities:**
        - Ensures smooth project execution.
        - Facilitates communication among team members.
        - Focuses on planning, scheduling, and budgeting (Project Manager).
        - Ensures team success and facilitates Agile processes (Scrum Master).
2. **Stakeholder**
    
    - **Responsibilities:**
        - Defines project requirements.
        - Provides feedback and clarification on requirements.
        - May participate in testing phases.
3. **System / Software Architect**
    
    - **Responsibilities:**
        - Designs the architecture of the software.
        - Communicates technical aspects to the team.
        - Provides technical support throughout the SDLC.
4. **UX Designer**
    
    - **Responsibilities:**
        - Balances software intuitiveness with robustness.
        - Defines user interactions and software behavior from the user's perspective.
5. **Software Developer**
    
    - **Responsibilities:**
        - Writes code based on design documents.
        - Implements architecture and requirements.
        - Collaborates with UX designers to meet user needs.
6. **Tester / QA Engineer**
    
    - **Responsibilities:**
        - Ensures product quality meets customer requirements.
        - Writes and executes test cases to identify bugs.
        - Provides feedback to development teams.
7. **Site Reliability Engineer (SRE) / Ops Engineer**
    
    - **Responsibilities:**
        - Bridges development and operations.
        - Automates systems and ensures reliability.
        - Facilitates incident tracking and troubleshooting.
8. **Product Manager / Product Owner**
    
    - **Responsibilities:**
        - Defines the product vision and requirements.
        - Leads development efforts to ensure value delivery to stakeholders.
9. **Technical Writer / Information Developer**
    - **Responsibilities:**
        - Writes documentation for end-users.
        - Creates user manuals and technical reports.

Key Differences

- **Focus Areas:**
    
    - Project Managers focus on overall project management, while Scrum Masters emphasize team dynamics and Agile practices.
    - Developers focus on coding, whereas UX Designers concentrate on user experience.
- **Interaction with Stakeholders:**
    
    - Stakeholders provide requirements and feedback, while Product Managers translate these into actionable tasks for the team.
- **Quality Assurance:**
    - Testers are dedicated to ensuring quality, while Developers are responsible for writing code that meets those quality standards.3