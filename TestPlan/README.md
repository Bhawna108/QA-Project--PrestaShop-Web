Table of Contents

1. Overview

2. Scope 

   1.1 In-Scope/ Inclusions

   1.2 Out Scope/Exclusions

3. Test Environments

4. Test Strategy 

5. Defect Reporting Procedure

    5.1 Defect Reporting 

6.Roles and Responsibilities 

7. Test Schedule 

8. Test Deliverables 

9. Entry and Exit Criteria

10. Suspension and Resumption Criteria

    10.1 Suspension

    10.2 Resumption Criteria

11. Tools

12. Risks and Mitigations

13. Approvals







Overview

This test plan describes the scope, strategy, schedule, resources etc for testing the PrestaShop e-commerce website. The objective is to ensure the website functions as expected, is user-friendly. 

Scope

In-Scope/ Inclusions: The modules that are to be tested rigorously.

Out Scope/ Exclusions: The modules that are not to be tested rigorously.

Scope of the project is to test the following features of PrestaShop  website-



-> In-Scope/ Inclusions:

•	Create an Account 

•	Sign in 

•	Forgot your Password

•	Home Page

•	Search

•	Product Detail Page 

•	Add to Wish List

•	Add to Cart

•	Shopping Cart

•	Checkout

•	Currency

•	Product Categories 

•	Your Account 

•	Order History

•	Order Tracking   

•	My Alerts 

•	Contact Us

•	Special Sales

•	Logout



-> Out Scope/Exclusions:

•	Third-party services



Test Environments

The following configurations will be used for testing:

Operating Systems: Windows 10, macOS, iOS, Android

Browsers: Chrome, Firefox, Microsoft Edge, Safari, Opera

Devices: Desktop, Laptops, Smartphones, Tablets



Test Strategy

 This section defines how testing will be conducted and ensures that all testing efforts are aligned with the project’s goals and requirements.

When we get an Application for Testing, then-

	 First, we will perform Smoke Testing to check whether the different and whether the primary and most important  features of a new build work as expected and whether the application is stable enough for further testing, more in-depth testing of the application functionalities..

	If the smoke test fails, means we have discovered any flaws then QA team  must be handed back the build to the development team for fixing bugs/ faults or any issues.

	When we’ll get build from the development team and if the build passes smoke testing, it means the build is stable now QA teams then proceed with further testing by using the test cases that we have created.

	There are any bugs then we will report it, we will report it in tracking tool and then Send it to the development team for fixing.

	Apart from Smoke testing, we will perform Sanity testing. We perform Sanity testing on above stable build to check thhat bugs have been resolved and there are no new defects introduced  in the build due to the changes in the code, or functionality or bug fixing.

	Functionality testing, UI testing,

	Exploratory testing- As we explore the software to identify errors in it, we experiment with the application. Testers apply their domain knowledge, critical thinking, strong testing skills and user-centric thinking to interact with the system and uncover potential issues.

	End to End Testing- we do End to End testing to assess an application’s functionalities from start to finish. This comprehensive approach simulates real-world user scenarios to ensure the application works as expected.

	 Regression testing and Retesting.



We repeat Test Cycles until we get the quality product.



Defect tracking & Reporting

Following flowchart depicts Defect Tracking Process:











-> Defect Reporting : 

When we execute the test cases, so during the test execution, any unexpected behaviour of the application will be noted.



Defect Reporting procedure is as follows:

1.	Identify Defect: Verify that the issue is reproducible and affects functionality or user experience. After discovery of a defect, it will be retested to verify reproducibility of The defect. 

2.	Assign Priority and Severity: Determine the defect’s priority (how soon it needs fixing) and severity (how it impacts users).

3.	Gather Details: Document steps to reproduce, test environment, browser, device details, and any prerequisites.

4.	Capture Evidence: Attach screenshots or screen recordings showing the issue.

5.	Log Defect: Defects will be documented in an excel.

6.	Assign to Development Team: Send the defect to the developer.

7.	Monitor and update Status: Monitor and update the status of defects in Excel. Create a simple table to log defects, including columns for defect ID, description, status, assigned to, priority, and comments. Update the table regularly as the status of each defect changes. 

Use color coding to visually indicate the status, Red for open, Yellow for in progress, Green for resolved. 

8.	Re-test on Fix: Once fixed, verify the solution with regression testing followed by Regression Testing. 

9.	Close Defect: Mark as closed if it meets quality standards and is verified in the testing environment.



Roles and Responsibilities 

Name	Role	Responsibilities 	Contact info

A	QA Manager 	Manages the project, takes appropriate resources, & gives project direction.



Develop & Review Test Plan.

Approve Test Plan.



Review Daily Status Report. 

Review Test Summary Report.	

B	QA Lead	Interact with the application.



Coordinate in developing Test Plan, reviewing Test Plan. 



Create Test cases and execute the test cases,

Coordinate in the test execution process with QA Engineers.



Report defects.



Validate the defects being reported. 



Submit daily issues updates and summary defect reports.



Attend if any meeting with client.	

C	QA Engineer 	Interact with the application.



Coordinate in developing Test Plan. 



Create and Execute the Test cases based on different scenarios. 



Report defects.



Coordinate with QA Lead during test cases preparation/execution/defect Handling.	

D	Associate QA Engineer 	Interact with the application.



Execute the Test cases, Coordinate with QA Engineer. 



Report defects.



Coordinate with Senior QA Engineer. 	







Test Schedule 

Task	Time Duration

Develop Test Plan 	Start Date	End Date

Create Test Cases 	Start Date	End Date

Execute Test Cases 	Start Date 	End Date

Submit Test Summary Report 	Start Date	End Date



Test Deliverables 

Deliverables 	Target Date of Completion 

Test Plan 	Date

Functional Test Cases 	Date

Defect Report 	-

Test Summary Report 	Date



Entry and Exit Criteria

Entry and exit criteria for each phase in the Software Testing Life Cycle (STLC) are:

1. Requirement Analysis

 Entry Criteria:

•	Testing team receives the Requirements Documents of the Project. 

Exit Criteria:

•	Testing team understands the product requirements that need testing.

•	Identifying any flaws or loopholes in the product specifications.

•	Requirement traceability matrix (RTM) is created.

•	Testable requirements are analyzed,  documented and reviewed.

•		Requirements are clear, understood,  doubts are cleared. 

•	Requirement documents are finalized and signed off.

2. Test Planning

Entry Criteria:

•	Requirements analysis is complete, Requirements are clearly understood.

•	Testable Requirements derived from the given Requirements Documents.

Exit Criteria: 

•	The test plan and test strategy are completed, documented and reviewed.

•	Test Plan document (includes Test Strategy) is signed-off by the Client.

3. Test Case Designing

Entry Criteria:

•	Approved test plan and test strategy are available.

•	Everything is clearly defined and understood in Test Plan. 

Exit Criteria:

•	Test Scenarios are documented. 

•	Test cases are created, documented,  reviewed, and approved.

•	Test data is prepared and validated.

4. Test Environment Setup

Entry Criteria:

•	Test Cases, data are available. 

•	Required hardware, software, and network configurations are identified.

Exit Criteria:

•	The test environment is configured and validated to be working as expected.

•	The test environment is stable and ready for test execution.

5. Test Execution

Entry Criteria:

•	The test environment is set up and ready.

•	Approved test cases are available.

•	Application is ready for Testing

Exit Criteria:

•	All test cases are executed, and results are documented.

•	Defects are logged.





6. Defect Reporting

Entry Criteria:

•	Failed test cases identified during test execution.

Exit Criteria:

•	Defects are documented with detailed information (steps to reproduce, screenshots, etc.).

•	Defects are assigned appropriate statuses and prioritized.

7. Test Cycle Closure

Entry Criteria:

•	All planned test cases are executed.

•	All reported defects are addressed. 

•	Test Case Reports, Defect Reports are ready. 

Exit Criteria:

•	The test summary report is completed and signed off.

•	Lessons learned and test metrics are documented for future cycles.

Suspension and Resumption Criteria

-> Suspension criteria:

•	Significant change in requirements suggested by client.

•	The build contains many serious defects which seriously or limit testing progress. 

-> Resumption Criteria:

Resumption will occur when the problem(s) that caused the suspension have been resolved.



Tools

•	MS Excel

•	MS Word 





Risks and Mitigations 



Risks 	Mitigations 

Incomplete Requirement Analysis. 	Conduct thorough requirement reviews with stakeholders and clarify any uncertainties early.

Testing can be delayed due to design tasks, the test cannot be extended beyond the UAT 

scheduled start date.	The testing team can control the preparation tasks and the early communication 

with involved parties.

Scope Creep	Define clear testing boundaries in the test plan and control changes through proper change management.

Resource Constraints

	Allocate resources based on priority and ensure backup resources planning.

Insufficient Test Coverage	Use Requirement Traceability Matrix (RTM) to ensure all requirements are covered in test cases.

Less time for Testing	Prioritize test cases by risk and importance, focusing on critical functionality first.

Unclear Test Environment Setup	Document environment requirements in the test plan and verify setup with the development team.

Communication Gaps	Schedule regular meetings with stakeholders and team members to review test progress and issues.



Approvals

The Names and Titles of all Persons who must approve this Test Plan. Team will also send different types of documents (Test Plan, Test Scenarios, Test Cases,  Test Report) for Client Approval as well.

	QA Manager 	QA Lead	Client 

Name			

Signature 			

Date			



