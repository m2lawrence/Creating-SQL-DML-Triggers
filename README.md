# Creating-SQL-DML-Triggers
To log a user to a delete.

The @CustomerID variable used to capture CustomerID was modified from the last UPDATE statement. Then the suser_sname( ) function captures the identity of the user that executed the UPDATE statement and stores it in the ModifiedBy column. 
