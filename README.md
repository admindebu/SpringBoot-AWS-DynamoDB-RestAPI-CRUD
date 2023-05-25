# SpringBoot-AWS-DynamoDB-RestAPI-CRUD
Working Rest API CRUD Projectusing Spring Boot and AWS Dynamodb NoSQL
👉  SUBSCRIBE, Follow me & LIKE ✅
#springboottutorial #awsdynamodb #nosql #RestAPIDevelopment 
In this video I have Explained how to create Rest API using SPringBoot and AWS DynamoDB NoSQL with working code.
I will suggest you first of all go through this DynamoDB basic tutorail for creating the table and getting accessKey, SecretKey.
# Video 1 :  DynamoDB BAsic Tutorial > DynamoDB :https://youtu.be/mmfY_CFkPrc
# Video 2 : Code Explanation with guide to run the Project > https://youtu.be/lc7XN0qiADU

Step1 : Pre-Requisit Software > 1. JDK8 (Java 8 ) and Maven 
Step2 : clone the project
Step3 : Import the project as existing maven project and build it ( maven clean install )
Step4 : Create DynamoDB Table, provide the region name, DB url , secretKey & AccessKey in the Properties file
Step5 : RUn and Test the API with below sample JSON.

URL : http://localhost:8082/v1/api/customer/add (Method name > Post)
Request Body POST API.
{
"customerId": "24",
"firstName": "gerry",
"lastName": "Yard",
"email":"gerry@emamil.com",
"address": "US-WEST"
}


