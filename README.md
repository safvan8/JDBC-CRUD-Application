# JDBC-CRUD-Application
This is a simple CRUD (Create, Read, Update, Delete) console-based application developed using Java and JDBC (Java Database Connectivity). The application allows users to interact with a MySQL database and perform CRUD operations on a single table called "students".

The application uses the Statement interface to execute SQL queries, which makes it vulnerable to SQL injection attacks. To mitigate this issue, the application was later updated to use the PreparedStatement interface instead.

The application runs in the console and prompts users to enter their desired CRUD operation. Users can either perform a SELECT operation to read data from the "students" table or perform non-SELECT operations to create, update, or delete data.

After executing the user's chosen operation, the application prompts the user if they want to perform any other operations. If the user chooses to perform another operation, the application displays the available CRUD options again. Otherwise, the application terminates.
