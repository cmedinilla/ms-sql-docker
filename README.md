# Microsoft SQL Server Docker Template

## Build image

docker build -t ms-sql-server .

## Run image

docker run -d -p 1433:1433 --name ms-sql-server ms-sql-server

## Run a bash inside of the container

docker exec -it ms-sql-server bash