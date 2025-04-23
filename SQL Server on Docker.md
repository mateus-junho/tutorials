
# SQL Docker

Run the following command on Linux:

`sudo docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=Senha@123" -p 1433:1433 --name sqllocal --hostname sqllocal -d mcr.microsoft.com/mssql/server:2022-latest`

## SQL Server Management Studio

To connect to SQL Server Management Studio

Server Name: 127.0.0.1,1433
Auth: SQL Server Authentication
Login: sa
Password: Senha@123

## Connection Strings

`"Server=127.0.0.1,1433;Database=vOperDB_BP_Helper;User Id=sa;Password=Senha@123;"`

`"ConnectionString": "Data Source=tcp:127.0.0.1,1433; User ID=sa; Password=Senha@123; Initial Catalog=vOperDB_BP_Helper; Trust Server Certificate=True;"`
