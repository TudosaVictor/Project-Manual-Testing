<h1> Manual Testing Project </h1>

   The scope of the final project is to use all gained knowledge through the course and apply them in practice, using a live application OrangeHRM Demo.
      
   The application under test: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
  
   API Documentation: https://orangehrm.github.io/orangehrm-api-doc/
  
   The final project will be split into 2 sections:  X and Y
  
   Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench. 
      

<h1> Functional specifications </h1>

<p>   The below Story was created in JIRA and describes the functional specifications of the Dependants module, upon which the final project is performed upon. </p>

![add](https://github.com/TudosaVictor/Project-Manual-Testing/assets/125571503/3b0a5543-ede5-41b5-8ae6-01ff07a2480d)


<h1> 1. Testing section </h1>

   <h2> Test planing </h2>
<p>
    The Test Plan is designed to describe all details of testing for the Dependants module from the https://opensource-demo.orangehrmlive.com/ website.
    It is a detailed document that describes software testing areas and activities. It outlines the test strategy, objectives, test schedule, required resources (human resources, software, and hardware), test estimation and test deliverables. </p>


   <h2> 1.1.1 Roles assigned to the project and persons allocated </h2>
  
  Project manager - 
  
  Product owner - 
  
  Software Developer - 
  
  QA Engineer - Victor Tudosa
  
  
  
   <h2> 1.1.2 Entry criteria defined </h2>
  
  - the requirement document should be available
  
  - a complete understanding of the application flow is required
  
  - roles needed for the project are allocated
  
  - initial project risks were detected and mitigated
  
  - the Test Plan Document should be ready
  
  - exploratory regression testing must be performed on the Admin module, which includes the Dependents section
  
  
   <h2> 1.1.3 Exit criteria defined </h2>
 
  - number of unresolved bugs is insignificant or they have low priority

  - all tests have been executed

  - all resolved bugs have been re-tested and approved by the QA team

  - the deadline was reached

  - no detected major risk remained un-mitigated


<h2>  1.1.4 Test scope </h2>
      
   Test in scope: GUI testing, functional testing, usability testing,
      
   Tests out of scope: performance testing, stress testing, security, integrations of the dependents module with other modules, automation testing, compatibility testing with multiple browsers
   
   
   <h2> 1.1.5 Risks detected </h2>
   
   - Project risks: lack of tester experience, documentation not updated with the current version of the software, only one tester for the project
   
   - Product risks: validation constraints on the fields might be too restrictive to the end user 


<h2>  1.1.6 Evaluating entry criteria </h2>

   The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.
    
   
   <h1> 1.2 Test Monitoring and Control </h1>
   
   Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 29 of the test cases were executed, in 2023:
   
  ![(/assets/chart.png)](https://github.com/TudosaVictor/Project-Manual-Testing/blob/main/chart.png)
   
   <h1> 1.3 Test Analysis </h1>
   
   The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:
   
   - check if the Add button is working

   - view dependant details and check they are correct

   - enter data for all available fields except one and check that the dependant is created

   - enter data for all available fields and check that the dependant is created

   - check if the delete a system user action is working

   <h1> 1.4 Test Design </h1>

   Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are smoke testing, database and use case testing.

![test case1](https://github.com/TudosaVictor/Project-Manual-Testing/assets/125571503/ddc9f987-faff-4ec5-9326-6297e2c35b88)

The test cases with the steps can be viewed here:

[test cases.xlsx](https://github.com/TudosaVictor/Project-Manual-Testing/files/11949680/test.cases.xlsx)


   
   <h1> 1.5 Test Implementation </h1>

   The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: https://opensource-demo.orangehrmlive.com/
   
* Access to the testing environment is given: Username : Admin | Password : admin123
   
* The test cases are written for the story to be tested
   
* Postman collection with the dependents API methods was created
   
* Authorization token was created for accessing the API
   
