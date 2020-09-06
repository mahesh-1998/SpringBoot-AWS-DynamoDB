# SpringBoot-AWS-DynamoDB

1. Created the POST REST end point where you can give the list of student abject (JSON) as a part of request body and those student object should be validate at the resource level
Student data contains
Student ID, 
Student Name, 
Student address, 
Student zipcode, 
Student totalMark

2. Validations:
Student Id must be numeric, 
Student Name length must be 50 char, 
Student zipcode must be numeric, 
Student totalMarks must be in numeric, 
Once you have validated student json provided in the request body process the request son and stored this data in one file.

3. Created the GET REST end point where student id is passed as path parameter and on the basis of student id fetch student data from file where you stored the student data from POS

Read the student data from file,
Save it the any collection,
Retrieve the data on the basis of student id from collection,
