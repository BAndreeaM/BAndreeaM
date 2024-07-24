# Testing Project for OpenCart
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test:** OpenCart

**Tools used:** Jira, Zephyr Squad.

## 1. Functional specifications:
The stories attached [here](https://github.com/BAndreeaM/BAndreeaM/blob/main/Jira_Stories.doc) were created in Jira and describe the functional specifications of the "Catalog" module, for which the final project is performed upon.

You can find a example of one of the stories that were created in the picture below:

![image](https://github.com/user-attachments/assets/6507cb4f-0b17-4728-a4e5-e2bd68602283)

### Release

Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/67d96bc9-2061-4803-864f-b8cabfe173d1)


## 2. Testing process
The test process was performed based on the standard test process as described below.

### 2.1 Test planning
The test plan is designed to describe all the testing details for the Catalog module in the OpenCart Demo e-commerce application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the projects risks associated with the plan.

The test plan that was created for this project can be found [here](https://github.com/BAndreeaM/BAndreeaM/blob/main/Test_Plan%20-%20OpenCart%20-%20final.docx)


#### 2.1.1. Roles asigned to the project and persons allocated

- Project manager: Popescu Ion
- Product owner: Pop Mihaela
- Software developer: Gavril Vlad
- QA Engineer: Burlacu Andreea 

#### 2.1.2 Entry criteria defined

_Entry Criteria for OpenCart E-commerce Shop App Testing_

- The business requirements must be finalizate: All functional and non-functional requirements for the application must be clearly documented and understood by the testing team. This includes the functionalities of each module (Categories, Products, Subscriptions, etc.) and the desired user experience 
- The roles must have been allocated: Each tester is assigned their role in testing, this testing team should be properly trained, knowing the functionality of the application and the testing methodologies to be used
- The test plan must be finished and sent to the stakeholders 
- The project risks must have been identified and mitigated
- Developed test cases: Detailed test cases should be created that describe the steps to verify each functionality. These test cases should cover both positive and negative scenarios to ensure thorough testing
- Define the objectives of testing and the accepted level of quality 

#### 2.1.3 Exit criteria defined

-	90%  or more of the tests are passed 
-	No critical issues have status open 
-	All detected errors have been reported 
-	The budget was reached 
-	The deadline was reached 
-	The objectives were fulfilled 
-	The product usage documentation has been finalized with the scenarios evaluated during the testing phase 
-	Test completion report has been created and sent to the stakeholders 
-	Product risks have been identified and mitigated
-	Not finding bugs of major severity in a specific period of time
- The existing bugs that were reported must have been fixed and followed by retesting and regression testing 


#### 2.1.4 Test scope

##### Tests in scope:
In order to meet our testing goals, we will only focus on the Catalog Module that has been scoped for testing and targeted for improvement over the next two months.

In terms of testing techniques, we will mostly use black box testing with the following test design techniques:
- equivalent partitioning
- boundary analysis
- decision table

In terms of type of testing, we will use non-functional testing where we will only cover usability testing and compatibility testing. Positive and negative testing should also be performed, and (as needed) retesting and regression testing will be done when defects are fixed or changes of any kind are made to the code.

##### Tests not in scope:
We are not going to cover during the testing process any techniques related to whitebox testing.

Also, performance and security testing will not be performed during this session of testing.

From the perspective of the modules covered, any other functionality that is located outside of the login or register module are not to be tested.


#### 2.1.5 Risks detected

##### Project risks:
- The team does not have the proper knowledge or experience in order to guarantee the desired level of quality for the application

- Not enough time has been allocated in order to properly test and cover all the functionalities in scope 

- All that the data that is going to be used will have to be created explicitly in the scope of testing, which will cut off from the time allocated for testing, generating a risk of not reaching the deadline 


##### Product risks:
- All the data that is going to be used will be test data, which will not give us an experience of the application close enough to the ones that the user will experience

- Taking into account that only two modules are in the scope of testing, the rest of the modules will still be at risk of not fulfilling the user needs 


#### 2.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 2.2 Test Monitoring and Control
In the monitoring and control stage, the test team manually executed the test cases and tracked their progress. This involves recording the results (pass/fail) and any observations in a test management tool or spreadsheet.
The test team used the Jira application to manage the tests, where they managed the test cases, followed their execution status (processed, failed, blocked). This allows for centralized control and visibility into the testing process.

The following is the test status report:

![image](https://github.com/user-attachments/assets/9affccd4-f4a9-4e57-b7b3-61ee203d1b3c)



### 2.3 Test Analysis
The testing process will be executed based on the application requirements. 

You can find below an example of ten test conditions  that were created in the scope of this project:

![image](https://github.com/user-attachments/assets/c8c805d5-a73a-4e19-b9ea-6e173f428469)



### 2.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/BAndreeaM/BAndreeaM/blob/main/Jira_Tests.doc)


### 2.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

- We make sure that all the test data is available and reviewed (test data = email examples, password examples, different type of currency, different types of credit cards)
- We make sure that the setup environment is up and running 
- We make sure that we have all the needed access and permissions to all the systems involved in the validation process 
- We prioritize the tests based on risks (if known) and business priority 


### 2.6. Test Execution
Test cases are executed on the created test Cycle summary. The test cases will be executed based on the Cycle Summary created:

![image](https://github.com/user-attachments/assets/71715b52-0d4b-4b5f-ad3a-74c3d7f0901b)


Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/BAndreeaM/BAndreeaM/blob/main/Jira_Bugs.doc)


The following is a summary of the bugs that have been found:

![image](https://github.com/user-attachments/assets/da2a3dee-429e-421d-ac0d-2431f1a5ec27)

- ST3AB-32 -> Priority High, Severity Medium
- ST3AB-10 -> Priority Medium, Severity Low

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.


### 2.7 Test Completion As the Exit criteria were met and satisfied, this feature is suggested by the Testing team

The traceability matrix was generated and can be found [here](https://github.com/BAndreeaM/BAndreeaM/blob/main/Traceability%20Matrix.xlsx) 


Test execution chart was generated and can be found below.

![image](https://github.com/user-attachments/assets/9037937f-3676-473c-8a51-1c699448e62e)


The final report shows that a number 3 tests have failed of a total of 10.

A number of 2 total bugs were found, from which the priority is: ST3AB-32 are high and ST3AB-10 are medium.

This testing process was aimed at ensuring the functionality and usability of the OpenCart eCommerce store application. A variety of test cases were executed to verify the basic functionalities of the various modules.

_Test results_ <br>
Number of test cases created: 10 <br>
Number of test cases executed: 10 <br>
Requirements coverage: About 95% <br>
Untested features: subscription plans, filters, downloads. <br>

Bug Impact
Critical Bugs: 2 critical bugs have been identified that would have a significant impact on product release and functionality in production. These bugs should be fixed before release.

