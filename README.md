# REST API Test Automation Framework

## Description

This Test Automation Framework is created using Java + TestNG + RestAssured + ExtentReports, which can be used across different api based applications.

![image](https://user-images.githubusercontent.com/88130729/231573331-998e8526-5320-42d1-92d2-60de39b933ba.png)

## Tools used:

1. JAVA
2. TestNG
3. RestAssured
4. ExtentReporter
5. Mavan
6. Eclipse IDE
7. Apachi POI (for DataDriven Testing)
8. JSON

## Reports
The framework supports Extent Report for Reporting purpose. On execution, new directory is created under project directory where all artifacts related to the execution resides. The report gives the details information on the Request & Response for each API executed. 

![image](https://user-images.githubusercontent.com/88130729/231572613-8dfe0243-9c39-47bd-a69f-c7b5ef561a03.png)

![image](https://user-images.githubusercontent.com/88130729/231572750-d47bd1f9-74c4-4e45-9578-b474b70b7bbe.png)

## TestData
Testdata maintained under the project directory resourse/Data folder, that contains
1. Exce File
2. JSON file

![image](https://user-images.githubusercontent.com/88130729/231574601-8d7af3aa-6c7d-4054-9928-824b1fae6aca.png)

## pom.xml
The POM contains information about the project and various configuration detail used by Maven to build the project.

## Folder Structure 
### TestBase 
1. Request Initiation 
2. Report Initiation  
### Requests 
This folder mainly the Method and classes for process the testcases
#### Testcases
All the Testcases are maintained here
### Util
Read Excel class and LoadProperties class 
### Resourses 
TestData and config file listed here




