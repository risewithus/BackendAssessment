# Backend Assessment
## This Assessment for JR .NET Developers

This assessment has been prepared for the candidates in the application process for the job and has been designed to help us in terms of evaluating the abilities and approaches by those who will attend. 
Within the assessment; we will expect you to complete the project whose content and details have been specified below within the time specified. The other important point is that you will deliver the best work which will also help us to properly evaluate. 

### Scenario

A simple phone directory application will be provided by designing a structure with web services to be used by web or mobile applications. 

### The Expected Functions:

-	Creating a contact in the address book
-	Removing a contact in the address book
-	Updating contacts in the address book
-	Deleting a contact in the address book
-	Listing the contacts in the address book
-	Adding contact information in the address book
-	Removing the contact information from a contact 
-	Bringing  the contact and detailed information about a person in the address book 
-	Requesting a report which shows the statistics according to the location of people in the address book. 

### Technical Design

**Contacts :** Theoretically adding the infinite numbers of contacts can be made in the system. The information related to every person must be able to be added as well.
The required fields of the data structure expected to be met are as follows :

-	UUID
-	Name
-	Last Name
-	Firm
-	Contact Information
    -	Information Type: Phone Number, E-mail Adress, Location
    -	The content of Information
  
**Report :** It simply includes the information below :

-	Location Information
    -	The most -> The least, in this way listing location by numbers 
-	The number of people registered in the address book at that location
-	The number of phone numbers registered in the address book at that location

**Note :** Please read the “Technical Expectations Section” carefully for the expectations regarding the evaluation.

### Technical Expectations

-	Technologies To Be Used 
    -	.NET Core
    -	Git
    -	MSSQL, Postgres, MongoDB (anyone of them will be sufficient)
    -	EF Core or Dapper
    -	Redis (plus)
-	Restrictions and Needs 
    -	Developing the project on Git with frequent commits
    -	Minimum %60 unit testing code coverage
    -	Having been created the migration structure which will form the project’s database
    -	READ.md documentation on how to be operated the project
    -	Services should be provided with REST communication over HTTP

### Completing Work

When the work is completed, it is expected that you will transfer this codebase to a git repository and share it with the repository address.

### Questions

If you have any question you can send an e-mail at info@rise-consulting.net
