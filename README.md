# Real-Estate-management-using-Arango-db
This repository contains :
1. Data we generated for use case in folder arangodb_backupv2.3
2. The queries which we formulated for justifying the requirements.

Command to import the data in ArangoDB using arango shell:

Create a database with name real_estate and run following command in arango shell-

arangorestore --server.database real_estate --input-directory "XX:/XXX/XXXX/arangodb_backupv2.3"

replace xxx with your local path.

For importing queries use the UI import button.

