# jupyter_json_postgresql
Data ingestion from JSON to postgreSQL:
1. Import necessary python library -- pandas, json, sqlalchemy, psycopg2
2. [E]xtract json to pandas data frame
3. [T]ransform pandas data fram -- remove unnecessary string & convert object to numeric
4. Create connection to postgreSQL
5. [L]oad to postgreSQL
6. Close the connection
