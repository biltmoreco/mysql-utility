# mysql-utility

Commands:

Start: `lando start`

MySQL: `lando mysql`

Import Database: `lando db-import sql-import/somedumpfile.sql.gz`

Export Database: `lando db-export sql-export/somedumpfile.sql.gz`

### DB dump must reside within app directory!

Due to restrictions in how Docker handles file sharing your database dump MUST exist somewhere inside of your app directory. This means that IT IS A VERY GOOD IDEA to make sure you add SQL dumps to your .gitignore file.