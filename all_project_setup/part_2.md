# setting up .env, variables and profiles 




### Criar Schemas e catalogs no (databricks) 



### Configuring sql warehouse for ".env" file 

"export DEV_DATABRICKS_HOST="https://dbc-526d744b-bf20.cloud.databricks.com/"

in databricks go for data warehouse

click on the warehouse you are going to use or another one (or create a new one)

look for "JDBC/ODBC ou Connection Details"

Você vai ver algo como /sql/1.0/warehouses/<id-do-warehouse>

Coloque esse path no .env: 