https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-setup-docker

docker pull microsoft/mssql-server-linux

docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=<YourStrong!Passw0rd>' -p 1433:1433 -d microsoft/mssql-server-linux