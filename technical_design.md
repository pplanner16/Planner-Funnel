# Technical Design
## Design principles
- platform independant
- client server
- most processing logic and data stored in database
## Flow
- client posts SQL statement
- HTTP server calls CGI program
- CGI program executes SQL statement on database
- CGI program queries the result on database
- CGI program outputs query result
- HTTP server returns output to client
## Front end
- web browser
- HTTP client
## Server
- HTTP server
- SQL database
- CGI program
## CGI program
- wrapper for database
- unit tests
### processing
#### SQL SELECT
- print html_page_top table
- execute query on DB
- if query has output, print
- else print return code
- print html_page_bottom table
### SQL INSERT, UPDATE, DELETE
- print html_page_top table
- execute statemnt on DB
- if error print
- query default_query
- execute default_query.query statement
- if error print
- print html_page_bottom table

### tables
#### test_cases
- SQL statement - client request
- SQL statement - Expected result
#### default_qeueries
- statement name (insert, update, delete)
- table name
- query statement
