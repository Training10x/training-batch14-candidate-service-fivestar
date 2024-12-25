#Note

Follow the below points to avoid data mismatch or merge conflicts. 

1. Always pull the code before pushing. 
2. Create database with name 'springcandidate'. You can find the username in application.properties and create the same user in your db and grant all permissions to do CRUD operations. Find below queries helpful if you need.

CREATE USER root WITH PASSWORD 'root';
GRANT ALL PRIVILEGES ON DATABASE springcandidate TO root;

Alternatively, you can add application.properties in your .gitignore file. 
