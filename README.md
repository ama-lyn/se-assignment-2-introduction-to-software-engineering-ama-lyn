[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15221852&assignment_repo_type=AssignmentRepo)

# SE-Assignment-2

## Assignment: Introduction to Software Engineering

Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:

### Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?

Software engineering is the systematic application of engineering priniciples, methods, and tools to the development and maintenance of high quality software systems. It involves the design, development, testing, deployement, and maintenance of software products on the other hand Traditional programming refers to the act of writing code to create software programs. It focuses on the implementation phase of the software development process and involves translating requirements and designs into executable code using programming languages.

Some differences I noted

| Aspect                      | Software Engineering                                                   | Traditional Programming                                  |
| :-------------------------- | :--------------------------------------------------------------------- | :------------------------------------------------------- |
| Scope                       | Encompasses the entire software lifecycle                              | Focuses mainly on coding and initial testing             |
| Approach                    | Structured, methodical, involving multiple phases                      | Primarily concerned with solving immediate coding tasks  |
| Collaboration               | Involves teamwork among various roles                                  | Often individual-centric or involves a small group       |
| Processes and Methodologies | Utilizes formal processes (e.g., Agile, Scrum, Waterfall)              | May not adhere to formal processes or methodologies      |
| Documentation               | Emphasizes thorough documentation throughout development               | Documentation may be minimal or limited to code comments |
| Focus                       | Includes planning, analysis, design, testing, maintenance              | Focuses on translating requirements into executable code |
| Project Management          | Integral part, including planning, scheduling, and resource management | May not involve extensive project management             |
| Quality Assurance           | Includes dedicated phases for quality assurance and testing            | Testing may be less formal and comprehensive             |

### Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

SDLC defines the steps of developing a system.

1. Identify Problems, Opportunities and Objectives
2. Determine Information Requirements
3. Analyse system needs
4. Design System components
5. Develop and document software
6. Test and maintain
7. Implement and Evaluate system

PHASE 1: <u>Identification of the problems, opportunities and objectives</u>

The system analyst, users and owners work together to identify problems (those that inhibit proper flow of processes), opportunities (what can be capitalized upon) and objectives (if overall goal of organisation can be met). The users say the problems they experience, owners are concerned about the cost and the system analysts come up with a feasibility study. The result in this satge is a feasibility study.

PHASE 2: <u>Determination of Information Requirements</u>

This phase involves extracting necessary information from all levels of workers (operational, manegarial, strategic) The particular users involved. Tools used include sampling and investigating hard data,interviewing, questionnaires, observation and prototyping. The systems analyst needs to know: the who (people involved), the what (business activity), the where (environment in which the work takes place), the when (timing) and the how (current procedures are performed).

PHASE 3: <u>Analyzing of system needs</u>

System analyst analyses the data gathered. The systems analyst prepares a systems proposal summarizing what has been found, provides cost/benefit analysis of alternatives, and makes recommendations on what should be done. Some of the tools used include: Data Flow Diagrams (DFDs) that chart the IPO of business functions in a structured graphical form, data dictionary that lists all data items as well as their specifications.

PHASE 4: <u>Designing of the system components</u>

This statge requires the system analyst and the programmers to work together. logical design is done encompassing accurate data entry procedures, devising user interface, designing files and databases and output
and design controls and backup procedures.

PHASE 5: <u>Developing and documenting software</u>

The SA works with programmers to develop original software. He also works with users to develop effective software documentation including procedure manuals, online help, websites for FAQ, readme files etc.Programmers design code and remove syntactical errors from computer programs. System Analysts verify whether the programmers are doing the right thing.

PHASE 6: <u>Testing and maintenance</u>

Testing is done to catch costly problems before system is passed to users by programmers and SA. Sample data is first applied then actual data. Maintenance is routine throughout the life of the IS

PHASE 7: <u>Implementation and evaluation of the system</u>

The System Analyst helps implement the system including user training and smooth transition from old to new system.Evaluation is carried out almost in every phase. This phase checks whether intended users are in fact using the system

### Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

| Agile Model                                                                                     | Waterfall Model                                                                                                 |
| ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Iterative and incremental approach (Works in small, repeated steps)                             | Linear and sequential approach                                                                                  |
| Highly flexible; changes can be made at any stage hence easy to make changes                    | Rigid; changes are difficult and costly once a phase is completed hence it is hard to make changes once started |
| Continuous customer involvement throughout development                                          | Customer involvement mainly at the beginning and end                                                            |
| Delivers small parts of the product frequently                                                  | Single delivery at the end of the project                                                                       |
| Better risk management through continuous feedback                                              | Higher risk due to late testing and integration                                                                 |
| Testing is integrated throughout the development process                                        | Testing is done after the development phase                                                                     |
| Less emphasis on comprehensive documentation; focus on working software                         | Strong emphasis on comprehensive documentation                                                                  |
| High level of collaboration and communication                                                   | Lower level of collaboration; often follows a top-down approach                                                 |
| Changes are expected and can be incorporated quickly                                            | Changes are discouraged and can be costly to implement                                                          |
| _Best for projects with dynamic requirements, need for quick releases, and continuous feedback_ | _Best for projects with well-defined, stable requirements and where the scope is unlikely to change_            |

### Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirement Engineering is a systematic and strict approach to the definition, creation, and verification of requirements for a software system. To guarantee the effective creation of a software product, the requirements engineering process entails several tasks that help in understanding, recording, and managing the demands of stakeholders.

1. Feasibility Study
2. Requirements elicitation
3. Requirements specification
4. Requirements for verification and validation
5. Requirements management

A. Feasibility Study

The feasibility study is basically the test of the proposed system in the light of its workability, meeting user’s requirements, effective use of resources and of course, the cost effectiveness. These are categorized as technical, operational, economic and schedule feasibility. The main goal of feasibility study is not to solve the problem but to achieve the scope

i. Technical feasibility – the SA must find out whether the current technical resources can be upgraded/added to in a manner that fulfills the request under consideration.

ii. Economic feasibility – The cost and benefit of the project are analyzed. A detailed analysis is carried out will be cost of the project for development which includes all required costs for final development

iii. Operational feasibility – dependant on the human resources available and projecting whether the system will operate and be used once it is installed.

B. Requirements Elicitation

Requirements elicitation is the process of gathering information about the needs and expectations of stakeholders for a software system. This is the first step in the requirements engineering process and it is critical to the success of the software development project. The goal of this step is to understand the problem that the software system is intended to solve and the needs and expectations of the stakeholders who will use the system. Elicitation does not produce formal models of the requirements understood. Instead, it widens the domain knowledge of the analyst and thus helps in providing input to the next stage.

C. Requirements Specification

This activity is used to produce formal software requirement models. All the requirements including the functional as well as the non-functional requirements and the constraints are specified by these models in totality. During specification, more knowledge about the problem may be required which can again trigger the elicitation process. The models used at this stage include ER diagrams, data flow diagrams(DFDs), function decomposition diagrams(FDDs), data dictionaries, etc.

_Requirements specification is the process of documenting the requirements identified in the analysis step in a clear, consistent, and unambiguous manner. This step also involves prioritizing and grouping the requirements into manageable chunks._

Once the requirements are specified, they must be reviewed and validated by the stakeholders and development team to ensure that they are complete, consistent, and accurate.

D. Requirements Verification and Validation

Verification refers to the set of tasks that ensures that the software correctly implements a specific function.

Validation efers to a different set of tasks that ensures that the software that has been built is traceable to customer requirements. If requirements are not validated, errors in the requirement definitions would propagate to the successive stages resulting in a lot of modification and rework. The main steps for this process include:

The requirements should be consistent with all the other requirements i.e. no two requirements should conflict with each other.
The requirements should be complete in every sense.
The requirements should be practically achievable.
Reviews, buddy checks, making test cases, etc. are some of the methods used for this.

Verification and Validation is an iterative process that occurs throughout the software development life cycle. It is important to involve stakeholders and the development team in the V&V process to ensure that the requirements are thoroughly reviewed and tested.
It is not a one-time process, but it should be integrated and continue throughout the software development process and even in the maintenance stage.

E. Requirements Management

Requirements management is the process of managing the requirements throughout the software development life cycle, including tracking and controlling changes, and ensuring that the requirements are still valid and relevant. The goal of requirements management is to ensure that the software system being developed meets the needs and expectations of the stakeholders and that it is developed on time, within budget, and to the required quality.

This is a critical step in the software development life cycle as it helps to ensure that the software system being developed meets the needs and expectations of stakeholders and that it is developed on time, within budget, and to the required quality. It also helps to prevent scope creep and to ensure that the requirements are aligned with the project goals.

### Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modular Development breaks programming into logical, manageable modules and it works well with top-down design because it stresses the inter-module interfaces and does not neglect them until later in systems development. Each module should be functionally cohesive.

Each module is developed independently and simultaneously then intergration testing follows.

_How it improves_

a. Working in manageable modules – allows the users to interact with its key features yet can be built separately from other system modules

b. Modules are easier to write and debug, maintain and grasp.

c.Critical interfaces are tested first.

d. It provide abstraction.

e. It allows multiple programmers to work simultaneously.

f. It allows code reuse.

g. It provides control and improves morale.

h. It makes identifying structure easier.

### Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

1. Unit Testing

Also known as Program Testing, it is a type of testing where the analyst tests or focuses on each program or module independently. It is carried out with the intention of executing each statement of the module at least once. In unit testing, accuracy of program cannot be assured and it is difficult to conduct testing of
various input combination in detail. It identifies maximum errors in a program as compared to other testing techniques.

2. Integration Testing

In Integration Testing, the analyst tests multiple module working together. Testing interactions between different components or subsystems. It is used to find discrepancies between the system and its original objective, current specifications, and systems documentation. Here the analysts are try to find areas where modules have been designed with different specifications for data length, type, and data element name. It verifies that file sizes are adequate and that indices have been built properly.

3. System testing

Testing the entire software system as a whole. This checks for a system’s compliance in accordance with the necessary given requirements. System testing inspects components like performance, load, reliability, and security with the goal of evaluating the end-to-end system specifications.

Typically, this method is done by a professional testing agent on the completed software product before it can be introduced to the market with real users. This step is important because the project is so close to being complete, so it should be tested in an environment similar to what the user will experience once it’s finished.

4. Acceptance testing

Testing the software against user requirements to ensure it meets user needs. It’s conducted by the user or customer since the goal is to find out if the requirements have been met on delivery of the final product. Since acceptance testing is the final phase, it needs to validate the end-to-end business flow and check for things like cosmetic errors, spelling mistakes, and usability.

### Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Sofatware tools for tracking changes to source code and coordinating work among team members (e.g Git, subversion enhance productivity, collaboration, and code quality by providing dev with features such as code editors, version control, debugging tools )

Importance

- There is streamline release management as It helps in maintaining different versions of software releases. These releases encapsulate various enhancements and features developed for different customers, aligning with the release roadmap.

- Conflict prevention- Version control helps avoid code conflicts within the source code base. By maintaining separate branches for different releases, it minimizes the chance of changes overlapping and causing conflicts.

### Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

1. Managing people

Acts as a project leader

Communication with stakeholders

Manages human resources

2. Managing project

Monitors progress and performance

Risk analysis at every phase

Manages time and budget constraint

3. Job Responsibilities

Involves with the senior managers in the process of appointing team members.

Builds the project team and assigns tasks to various team members.

Responsible for effective project planning and scheduling, project monitoring and control activities in order to achieve the project objectives.

Acts as a communicator between the senior management and the development team and internal and external stakeholders.

Effectively resolves issues that arise between the team members by changing their roles and responsibilities.

Modifies the project plan (if required) to deal with the situation.

### Software Maintenance

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance is a continuous process that occurs throughout the entire life cycle of the software system. The goal of software maintenance is to keep the software system working correctly, efficiently, and securely, and to ensure that it continues to meet the needs of the users. This can include fixing bugs, adding new features, improving performance, or updating the software to work with new hardware or software systems. It is also important to consider the cost and effort required for software maintenance when planning and developing a software system.

Types

- Corrective Maintenance: This involves fixing errors and bugs in the software system.

- Patching: It is an emergency fix implemented mainly due to pressure from management. Patching is done for corrective maintenance but it gives rise to unforeseen future errors due to lack of proper impact analysis.

- Adaptive Maintenance: This involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.

- Perfective Maintenance: This involves improving functionality, performance, and reliability, and restructuring the software system to improve changeability.

- Preventive Maintenance: This involves taking measures to prevent future problems, such as optimization, updating documentation, reviewing and testing the system, and implementing preventive measures such as backups.

Maintenance is done for two main reasons:

a. To correct software errors.

b. To enhance the software’s capabilities in response to changing organizational needs, which may involve one of the following three situations:

- Users requesting additional features after becoming familiar with the computer
  system and its capabilities

- The business changes over time

- Hardware and software are changing at an accelerated pace

### Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Software engineers may encounter various ethical issues in their work, including:

1. Privacy Concerns: Handling sensitive user data and ensuring data privacy and security.
2. Bias and Discrimination: Developing algorithms or systems that exhibit bias or discrimination based on race, gender, or other factors.
3. Intellectual Property: Respecting intellectual property rights, avoiding plagiarism, and honoring copyright laws.
4. Transparency: Being transparent about software capabilities, limitations, and potential risks to users.
5. Conflicts of Interest: Avoiding conflicts of interest that may compromise objectivity or impartiality in decision-making.
6. Social Impact: Considering the societal impact of software, such as environmental sustainability, accessibility, and inclusivity.
7. Professional Conduct: Upholding professional standards, honesty, integrity, and accountability in all aspects of work.

To ensure adherence to ethical standards, software engineers can:

1. Familiarize themselves with ethical codes, standards, and guidelines provided by professional organizations such as the ACM (Association for Computing Machinery) or IEEE (Institute of Electrical and Electronics Engineers).
2. Implement robust security measures, data encryption, and privacy policies to protect user data and confidentiality.
3. Regularly review algorithms and AI systems for bias, ensure fairness in decision-making processes, and consider diverse perspectives during development.
4. Obtain proper licenses, permissions, or use open-source resources responsibly, and give credit to original creators.
5. Clearly communicate software functionalities, limitations, risks, and potential impacts to stakeholders and end-users.

### References

"Software Engineering" (2023, May 07). Geeks for Geeks.

"Version Control" (2023, June 06). Log Rocket.

Ochigo, S. E. (2024). System Analysis and Design. (January 16, 2024 - April 19, 2024).

Ouma, D. (2024). Introduction to Software Engineering. Power Learn Project. June 3,2024.
