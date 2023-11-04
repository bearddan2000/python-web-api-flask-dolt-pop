# python-web-api-flask-dolt-pop

## Description
Creates an api of `pop` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.

## Tech stack
- python
- flask
- dolt

## Docker stack
- python:latest
- dolthub/dolt-sql-server

## To run
`sudo ./install.sh -u`
- Get all dogs: http://localhost/pop
  - Schema id, name, and color
- Query with params: http://localhost/pop <id>

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
- https://stackoverflow.com/questions/27766794/switching-from-sqlite-to-mysql-with-flask-sqlalchemy
