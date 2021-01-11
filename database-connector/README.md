# Database Connector

Various examples of how to use the database connector
 - *DynamicDatabase.jar*
   - Examples of how to set the INSERT statement dynamically based on the input payload
     - Call: http://localhost:8081/insert to test the insert of one JSON object
     - Call: http://localhost:8081/insert-bulk to test the insertion of an array of JSON objects
     - use the JSON payload provided in the repo
     - use the training services jar and the Derby database it launches
       - you can find it in the student resoruce of the fundamantals course
