# **05 \- Product Backlog & Task Management**

**Project Name:** \[Project Name\]

**Managed By:** @product-manager

**Reference:** docs/02-product-context/02-User-Stories.md, docs/00-system-context/03-API-Specs.md

## **1\. Sprint / Milestone Goal**

\<\!-- AI INSTRUCTION: Define the primary objective of this current backlog (e.g., "MVP Release Phase 1: Core Authentication and Dashboard"). \--\>

\[Sprint Goal\]

## **2\. Task Status Legend**

\<\!-- AI INSTRUCTION: This legend dictates how development agents (@frontend-dev, @backend-dev) should update the task statuses. DO NOT change this legend. \--\>

* \[ \] **To Do** (Not Started)  
* \[-\] **In Progress** (Currently being worked on by an agent)  
* \[x\] **Done** (Completed, tested, and verified)  
* \[\~\] **Blocked** (Cannot proceed due to dependencies or missing info)

## **3\. Backlog Tasks (By Epic)**

\<\!-- AI INSTRUCTION: Break down EVERY User Story from '02-User-Stories.md' into granular, actionable technical tasks.

CRITICAL RULES:

1. Every task MUST be assigned to a specific execution agent (e.g., @frontend-dev, @backend-dev, or @devops).  
2. Tasks must be small enough to be completed in a single context window.  
3. Separate Frontend UI building from API Integration when possible. \--\>

### **Epic 1: \[Epic Name, e.g., Authentication\]**

**US-1.1: \[Story Name, e.g., User Login\]**

* **Backend Tasks:**  
  * \[ \] TASK-1.1.1: Set up Auth controller and login route POST /api/v1/login (@backend-dev)  
  * \[ \] TASK-1.1.2: Implement password hashing comparison and JWT generation (@backend-dev)  
* **Frontend Tasks:**  
  * \[ \] TASK-1.1.3: Build Login UI screen based on PRD (@frontend-dev)  
  * \[ \] TASK-1.1.4: Integrate UI with POST /api/v1/login and handle loading/error states (@frontend-dev)

**US-1.2: \[Story Name, e.g., User Registration\]**

* **Backend Tasks:**  
  * \[ \] TASK-1.2.1: \[Task description\] (@backend-dev)  
* **Frontend Tasks:**  
  * \[ \] TASK-1.2.2: \[Task description\] (@frontend-dev)

\<\!-- AI INSTRUCTION: Continue generating tasks for ALL Epics and User Stories defined in the Product Context. Ensure the logic aligns with the System Architecture (e.g., if there is no backend, do not assign @backend-dev). \--\>

### **Epic 2: \[Epic Name\]**

**US-2.1: \[Story Name\]**

* **Backend Tasks:**  
  * \[ \] TASK-2.1.1: \[Task description\] (@backend-dev)  
* **Frontend Tasks:**  
  * \[ \] TASK-2.1.2: \[Task description\] (@frontend-dev)

## **4\. Bug Tracking & Refinements**

\<\!-- AI INSTRUCTION: This section is initially empty. Use this section to log any bugs found during testing, or minor tweaks requested by the user during the review phase. Format them as actionable tasks just like above. \--\>

*   
  * \[ \] BUG-01: \[Bug description and reproduction steps\] (@agent-name)  
*   
  * \[ \] TWEAK-01: \[Minor UI/Logic change requested by user\] (@agent-name)