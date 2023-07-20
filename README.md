## Software and Design Engineering

### 1. Linear Sequential Model / Waterfall Model:
linear sequential model or be known as waterfall model is one of the approaches in Software Development Process Models that software engineer used to defined and design which are used during the development process of software. It clearly states that all these phases are cascaded to each other so that second phase is started as and when defined set of goals are achieved for first phase and it is signed off.

![image](https://github.com/Tanvi-Jain01/Design-Software-Eng/assets/123053700/760916d9-e414-432d-a61a-f82eaca3222c)


**Phases of Linear Sequential Model**


Requirement Analysis and Design –
This stage includes a detailed study of the business needs of the organization. Design focuses on high level design like, what programs are needed and how are they going to interact, low-level design, interface design and data design. The logical system of the product is developed in this phase. 

Implementation – In this phase the designs are translated into code. Computer programs are written using a conventional programming language or an application generator. 

Testing – In this phase the system test the program. The system is then tested as a whole. The system is tested to ensure that interfaces between modules work, the system works on the intended platform and with the expected volume of data and that the system does what the user requires.

Maintenance – It is cannot be avoided fact that a system will need maintenance. There are many reasons for the change. Change could happen because of some unexpected input values into the system.

### 2. V-Model

The V-model, or Validation and Verification model, expands on the Waterfall model with the addition of early test planning. Instead of moving down linearly through the software development stages, the V-Model moves down until the coding phase when it pivots and begins to ascend upward to form a “V” shape.
![image](https://github.com/Tanvi-Jain01/Design-Software-Eng/assets/123053700/3d0e201a-fd47-4329-a26e-33cfd67ab785)

**Advantages and Disadvantages**

•	Each development stage has a corresponding testing activity. This allows the team to detect errors in requirement specifications, code, and architecture early in the development of the project. Unfortunately, fixing errors is still difficult and expensive as there is not a clear path for resolving these problems.

•	The addition of early test planning gives the V-Model a greater chance of success than that of the Waterfall model. However, the V-Model is still linear, making it inflexible.

•	Like the Waterfall model, a team can only start the next stage when the current stage is complete. This makes adjustments difficult, expensive, and time-intensive.

•	Therefore, this model is best for short projects with fixed, clearly defined, documented requirements, but it is not ideal for long, complex, or ongoing projects.


## 3. Incremental Model:
In an Iterative Incremental model, initially, a partial implementation of a total system is constructed so that it will be in a deliverable state. Increased functionality is added. Defects, if any, from the prior delivery are fixed and the working product is delivered. The process is repeated until the entire product development is completed. The repetitions of these processes are called iterations. At the end of every iteration, a product increment is delivered.

![image](https://github.com/Tanvi-Jain01/Design-Software-Eng/assets/123053700/f35fa285-e72f-452c-9c66-e5196e0ccb13)

**Advantages:**

• you can develop prioritized requirements first.

• Initial product delivery is faster and Lowers initial delivery cost.

• Each release is a product increment, so that the customer will have a working product at hand all the time.

• Customer can provide feedback to each product increment, thus avoiding surprises at the end of development.

• Requirements changes can be easily accommodated.

**Disadvantages**

• Requires effective planning of iterations.

• Requires efficient design to ensure inclusion of the required functionality and provision for changes later.

• Requires early definition of a complete and fully functional system to allow the definition of increments.

• Total cost of the complete system is not lower.

**Examples:** M.S word, Excel


## 4. Iterative Models

While developing the software systems, it is often needed to make modifications in earlier development phases or task sets. If the development process is linear then the end product will be unrealistic. In such cases, the iterative approach needs to be adopted.

**Prototype model**

• In prototype model initially, the requirement gathering is done.Developers and customer define all over objectives and identifies areas needing more requirement gathering.

• Then a quick design is prepared. This design represents what will be visible to user in input and output format.

• From the quick design a prototype is prepared. Customer or user evaluates the prototype in order to refine the requirements.This prototype is tuned to satisfy customer requirements which is changing continuously. If the customer is not satisfied then gives the feedback and fixes to develop again.

![image](https://github.com/Tanvi-Jain01/Design-Software-Eng/assets/123053700/162800b7-68fe-4e43-8c2d-cb0932d0f454)

**Advantages:**

• Error can be detected much earlier as the model is made step by step.

• Quicker user feedback is available leading to better solution.

• This provides user a better understanding about their system.

• Users are actively involved in the system, so more accurate user requirement is obtained.


**Disadvantages:**

• It requires participation of customer which is always not possible.

• Practically, There may be too much variation in requirements which may increase complexity.

• As doing fixes is continuous this increases the cost.

It has poor documentation because of continuously changing customer requirements.


## Spiral Model
• The basic problem with the process model is they can not handle the uncertainty. So the project fails because of the neglected project risk.

• Spiral model is combination of three approaches- risk reducing, iterative incremental approach.

• The spiral model is divided into a number of framework activities. These framework activities are denoted by the task regions. usually there are six task regions.

• Spiral model is realistic approach to development of large scale systems and software. In the initial pass, product specification is built and in subsequent passes around the spiral the prototype gets developed and then more improved versions of software gets developed.

![image](https://github.com/Tanvi-Jain01/Design-Software-Eng/assets/123053700/82039d4b-c6d8-43fd-aceb-1ef8a43f41f3)

**Task regions can be described as-**

• Customer communication: - it is suggested to establish customer communication. Establishes an understanding of the system or product objectives namely- performance, functionality etc and investigate constraints namely-cost, schedule, support etc.

• Planning: - All planning activities are carried out in order to define resources timeline and other project related activities. Product’s objective, alternatives and constraints are planned and understood here.

• Risk analysis: - the task required to calculate technical and management risk are carried out.

• Engineering: - in this task required to build one or more representations of applications are carried out.

• Construct and release: - necessary task required to construct, test, install, the application are conducted and user support are also carried out.

• Customer evaluation: - Customer’s feedback is taken and based on that task are performed.

• In spiral model, the software engineering team moves around the spiral in a clockwise direction beginning at the core.

**Advantages:**

• Requirement changes can be made at every stage.

• Risk can be identified and rectified easily.

• The developer and client better understand and react to risk at each evolutionary level.

• Each phase is completed with a review by the people and documentation.

**Disadvantages:** 

• Demands considerable risk assessment expertise.

• If major risk is not uncovered or solves then problem will be occur.

• It is not much proven model like linear or prototype model.

• Customer communication must be proper else the product will not be up to the mark.



### 5. Rapid Application Development (RAD) Model
In this model, with limited functionality the basic software product is created for user’s understanding.

• The RAD Model is a type of incremental process model in which there is extremely short development cycle.

• The RAD model is a “high-speed” adaptation of the linear sequential model in which rapid development is achieved by using component based construction.
• Using the RAD model the fully functional system can be developed within 60 to 90 days.

![image](https://github.com/Tanvi-Jain01/Design-Software-Eng/assets/123053700/12883707-1203-455e-b072-c7e60646e1a6)

**Various phases in RAD are:**

• Requirements Gathering

• Analysis and Planning

• Design

• Build or Construction and

• Deployment

Multiple teams work on developing the software system using RAD model parallel.

1. Requirements Gathering :
In the Requirements Gathering phase the developers communicate with the users of the system and understand the business process and the requirements of the software system.

2. Analysis and Planning :
During analysis and planning phase, the analysis on the gathered requirements is made and a planning for various software development activities are done.

3. Design :
During the design phase various models are created. Those models are Business models, Data models and Process model.

4. Build or Constructions :
The build is an activity in which, using existing software components and automatic code generation tool the implement –tation code is created for the software system.
This code is well tested by its team.
The functionalities developed by all the teams are integrated to form a whole.

5. Deployment :
Finally the Deployment of all the software components is carried out.

**Advantages:**

• Short life span

• All the requirements are fixed

**Disadvantages:**

• Requires multiple teams or large number of people

• Requires heavily committed developer and customer

• This model requires heavy resources

• Lack of modularization results in project fail

• Difficult to adopt new technologies

• High cost



