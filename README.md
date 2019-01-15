# zcs
assignment

application:

Scenario:
Your application name is ClientOnboard.
This application is for onboarding a user.
This application accepts only bulk requests. In Json Format.
Fields are name, age, sex, permanent address, current address, mail id, phone number, govt. id number, country, marital status
All are mandatory fields.
Duplicate request is not accepted. - Duplicate can be in request and duplicate can be there in data base as well. If a request is already present, then we will not insert that
If country is India then age should be less than 45, if USA then 50
If married, then wife/husband’s name is mandatory and if kid is also there then kid’s name is mandatory. If Divorced and kid is with that person, then kid’s name is mandatory. Else nothing is required. So, if user passes the value also system should be able to ignore.
For each request a request ID should be generated in Java

Expected:
Create a single json which covers all these scenarios. Positive as well as negative.
Application should be able to validate all the data and save the data in DB (Any DB of your choice) which is correct.
Error messages should be meaningful so that requestor can understand where the fault is.
Service should create a proper response. Where for pass scenario login id and name and request id should come and in case of fail it should give request ID, name, and reason for failure. 
HTTP response code based on the service response.

Preferred Springboot application.

=====================================================================================
UI is not required. Only back end logic is needed. 

Rules for creating and expose a rest service should be followed.
JUNIT is mandatory


