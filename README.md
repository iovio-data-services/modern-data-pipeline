# modern-data-pipeline
A collection of architecture templates for ephemeral and on-demand computation of data pipelines 


## Installation of MS-SQL Server Database
```
docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=yourStrong(!)Password' -e 'MSSQL_PID=Express' -p 1433:1433 -d --name sql1 mcr.microsoft.com/mssql/server:2017-latest-ubuntu
```

## Load Bike Shop Information
