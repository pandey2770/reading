# Rest API ( Get, Put, Post, Delete )
REST stands for Representational State Transfer. Its an architectural paradign where each resource has a unique identifier operation like create, update, delete, get can be performed over the resource.
HTTP protocols are used to create restful api ( Get, Put, Post, Delete ).

## Get
`Get` helps to brings the all or selected present data stored in the database and show it to the clint side. Basic syntax of get is
```
GET /clients
GET /clients/1
```
## Put 
`Put` helps to edit, change or update the present data stored in are database. Basic syntax of put is 
```
PUT /clients/
Request Body { ... }
```
## Post
`Post` helps to creat a new entry or we can se add a new data in are databse. Basic syntax of post is 
```
POST /clients/
Request Body { ... }
```
## Delete 
`Delete` helps to delete an entry or any selected data from our database. Basic syntax of delete is
```
DELETE /clients/1
```