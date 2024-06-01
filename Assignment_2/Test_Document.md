# Test Document
## Project Name: Eco-Cycle

### Table of Contents
1. [Introduction](#1-introduction)
2. [Test Plan](#2-test-plan)
   - [2.1 Objectives](#21-objectives)
   - [2.2 Scope](#22-scope)
   - [2.3 Testing Strategy](#23-testing-strategy)
3. [Test Cases](#3-test-cases)
   - [3.1 User Management](#31-user-management)
   - [3.2 Material Listings](#32-material-listings)
   - [3.3 Transaction Management](#33-transaction-management)
   - [3.4 Communication](#34-communication)
4. [Test Environment](#4-test-environment)
5. [Test Schedule](#5-test-schedule)
6. [Defect Management](#6-defect-management)
7. [Tools & Resources](#7-tools-and-resources)
8. [Continuos Improvement](#8-continuous-improvement)


### 1. Introduction
This document outlines the testing plan for the Eco-Cycle project. It includes the objectives, scope, testing strategy, detailed test cases, test environment, schedule, and defect management process.

### 2. Test Plan

#### 2.1 Objectives
- Ensure all functional and non-functional requirements are met.
- Identify and fix defects before the production release.
- Validate the performance, security, and usability of the Eco-Cycle platform.

#### 2.2 Scope
The scope of testing includes all features and functionalities outlined in the SRS and URD documents, focusing on user management, material listings, transaction management, and communication.

#### 2.3 Testing Strategy
- **Unit Testing:** Verify individual components by developers.
- **Integration Testing:** Ensure that components interact correctly.
- **System Testing:** Validate the end-to-end functionality of the platform.
- **Acceptance Testing:** Confirm the platform meets user requirements and expectations.
- **Performance Testing:** Assess the platform's responsiveness and stability under load.
- **Security Testing:** Identify and mitigate potential security vulnerabilities.
- **API Testing:** Evaluate the reliability, performance, and security of the API endpoints to ensure they handle requests and responses correctly, adhere to expected functionality, and maintain data integrity.

### 3. Test Cases

#### 3.1 User Management
- **TC01:** Verify user registration with valid and invalid data.
- **TC02:** Verify email verification process.
- **TC03:** Verify login functionality with correct and incorrect credentials.
- **TC04:** Verify profile update process.

#### 3.2 Material Listings
- **TC05:** Verify listing creation by recyclers with valid and invalid data.
- **TC06:** Verify search functionality with various criteria.
- **TC07:** Verify detailed view of listings.
- **TC08:** Verify bookmarking/saving of listings.

#### 3.3 Transaction Management
- **TC09:** Verify purchase request initiation by manufacturers.
- **TC10:** Verify recyclers' ability to accept, negotiate, or decline purchase requests.
- **TC11:** Verify transaction finalization and inventory update.
- **TC12:** Verify order tracking and history.

#### 3.4 Communication
- **TC13:** Verify messaging system functionality.
- **TC14:** Verify email notifications for various events.
- **TC15:** Verify setting communication preferences.

#### 3.5 API Testing
- **TC16:** Verify API endpoint for user registration with valid and invalid data.
- **TC17:** Verify API endpoint for login functionality with correct and incorrect credentials.
- **TC18**: Verify API endpoint for profile updates.
- **TC19:** Verify API endpoint for listing creation with valid and invalid data.
- **TC20:** Verify API endpoint for search functionality with various criteria.
- **TC21:** Verify API endpoint for purchase request initiation.
- **TC22:** Verify API endpoint for transaction finalization and inventory update.
- **TC23:** Verify API endpoint for order tracking and history.
- **TC24:** Verify API endpoint for messaging system functionality.
- **TC25:** Verify API performance under load.

### 4. Test Environment
- **Development Environment:** Local development setup with mock data.
- **Test Environment:** Staging server replicating the production environment for comprehensive testing.
- **Production Environment:** Live server where the final version will be deployed.

### 5. Test Schedule
- **Unit Testing:** Weeks 1-2
- **Integration Testing:** Weeks 3-4
- **API Testing:** Weeks 4-5
- **System Testing:** Weeks 5-6
- **Acceptance Testing:** Weeks 7-8
- **Performance and Security Testing:** Weeks 9-10

### 6. Defect Management
- **Defect Tracking Tool**
   - **Tool:** JIRA or a similar defect tracking system.
   - **Purpose:** To log, track, and manage defects efficiently and systematically.
- **Defect Lifecycle**
   - **Identification:**
      Testers identify a defect during testing activities.
      A defect is any deviation from the expected behavior or requirements.
   - **Logging:**
      Defects are logged into the defect tracking tool with detailed information.
      Information includes defect ID, description, steps to reproduce, screenshots, severity, priority, and environment details.
   - **Prioritization:**
      Defects are prioritized based on their impact on the system and urgency of fixing.
      Priority levels: Critical, High, Medium, Low.
   - **Assignment:**
      Defects are assigned to the appropriate developer or development team for resolution.
      The assignment is based on the nature of the defect and the expertise required.
   - **Resolution:**
      Developers fix the defect and update the status in the tracking tool.
      The resolution can be a code fix, configuration change, or other necessary actions.
   - **Verification:**
      Testers verify the fix by retesting the defect.
      Verification ensures that the defect has been fixed and no new issues have been introduced.
   - **Closure:**
      Once verified, the defect is closed in the tracking tool.
      Closure indicates that the defect has been resolved and verified satisfactorily.
- **Priority Levels**
   - **Critical:** 
      Defects that cause complete system failure, data loss, or significant impact on core functionalities. Requires immediate attention.
   - **High:** 
      Defects that affect major functionalities but do not cause complete system failure. Should be addressed promptly.
   - **Medium:** 
      Defects that impact non-core functionalities or have a moderate impact on user experience. Should be fixed in the normal course of development.
   - **Low:** 
      Minor defects with minimal impact on functionality or user experience. Can be fixed at a lower priority.

### 7. Tools and Resources
- **Testing Tools:** Selenium for automation, JIRA for defect tracking, Postman for API testing, LoadRunner for performance testing.
- **Resources:** Access to environments, documentation, test data, and necessary tools.
- **Training:** Ensure team members are trained on tools and processes.

### 8. Continuous Improvement
- **Feedback Loop:** Collect and use feedback to improve.
- **Process Review:** Regularly review and refine testing processes.
- **Best Practices:** Document and share best practices.
- **Retrospectives:** Evaluate and improve after major testing phases.
