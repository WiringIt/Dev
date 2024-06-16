Starting my first project
Using HTML,CSS-Frontend
Flask-Backend
Sqlite3-Database

#June16: Problems faced:
1. Error in VS code:
.venv\Scripts\activate : File C:\Users\samri\Dev\FirstProject\.venv\Scripts\Activate.ps1 cannot be loaded because running scripts is disabled on this system.     
For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ .venv\Scripts\activate
+ ~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

Solution: Set-ExecutionPolicy Unrestricted -Scope Process
Run this command everytime you're using virtual env
2. What is WSGI? 
WSGI (Web Server Gateway Interface) is a specification that describes the communication between web servers and Python web applications or frameworks. It explains how a web server communicates with Python web applications or frameworks and how web applications or frameworks can be chained for processing a request.
