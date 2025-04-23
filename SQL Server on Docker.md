
# SQL Docker

Run the following commmand on linux:

`sudo docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=Senha@123" -p 1433:1433 --name sqllocal --hostname sqllocal -d mcr.microsoft.com/mssql/server:2022-latest`

To connect on SQL Server Management Studio

Server Name: 127.0.0.1,1433
Auth: SQL Server Authentication
Login: sa
Password: Senha@123 