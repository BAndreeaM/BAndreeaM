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

- The business requirements must be finalizate: All functional and non-functional requirements for the application must be clearly documented and understood by the testing team. This includes the functionalities of each module (Categories, Products, Subscriptions, etc.) and the desired user experience. 
- The roles must have been allocated: Each tester is assigned their role in testing, this testing team should be properly trained, knowing the functionality of the application and the testing methodologies to be used.
- The test plan must be finished and sent to the stakeholders 
- The project risks must have been identified and mitigated
- Developed test cases: Detailed test cases should be created that describe the steps to verify each functionality. These test cases should cover both positive and negative scenarios to ensure thorough testing.
- Established test environment: A dedicated test environment that mirrors the production environment as closely as possible should be set up. This ensures that any issues identified during testing are relevant to real-world application deployment.
- Prepared test data: A variety of test data sets simulating real-world scenarios should be prepared for testing. This includes product data, customer accounts and orders with different variants (payment methods, shipping options, etc.).
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


#### 2.1.4 Test scope

##### Tests in scope:
(descrieti aici toate testele pe care intentionati sa le faceti. Puteti include functionalitati din aplicatie, tipuri sau tehnici de testare, dispozitive pe care veti testa etc)

##### Tests not in scope:
(descrieti aici toate testele pe care NU intentionati sau nu puteti sa le faceti. Puteti include functionalitati din aplicatie, tipuri sau tehnici de testare, dispozitive pe care veti testa etc)

#### 2.1.5 Risks detected

##### Project risks:
(enumerati aici toate riscurile de proiect pe care le-ati identificat pentru proiectul vostru)

##### Product risks:
(enumerati aici toate riscurile de produs pe care le-ati identificat pentru proiectul vostru)

#### 2.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 2.2 Test Monitoring and Control
(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)

### 2.3 Test Analysis
The testing process will be executed based on the application requirements. (The requirements analysis has been done in order to implement the early testing test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review).

The following test conditions were found:

(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)

### 2.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here (inserati linkul catre fisierul cu testele, in format pdf, word sau csv)

### 2.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

### 2.6. Test Execution
Test cases are executed on the created test Cycle summary: (inserati aici numele cycle-ului pe care l-ati creat)

Bugs have been created based on the failed tests. The complete bug reports can be found here: (inserati aici fisierul cu bug-urile pe care le-ati identificat)

The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 2.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.

(inserati aici raportul de executie generat din jira din sectiunea de dashboards)

The final report shows that a number (inserati numarul de teste) tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)
