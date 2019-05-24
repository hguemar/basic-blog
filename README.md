Node.js, Express & MongoDB: Simple Add, Edit, Delete, View (CRUD)
========

A simple and basic CRUD application (Create, Read, Update, Delete) using Node.js, Express, MongoDB & EJS Templating Engine.

**Blog:** [Node.js, Express & MongoDB: Simple Add, Edit, Delete, View (CRUD)]

**Start MongoDB server**

```
sudo service mongod start
```

**Check MongoDB server status**

```
sudo service mongod status
```

**Go to MongoDB shell**

```
mongod
```

**Show databases**

```
show dbs
```

**Create database named "test"**

```
use test
```

**Create collection(table) named "users"**

```
> db.users.insert({name:"Eliott Pignon", age:25, email:"eliott.pignon@laposte.net"})
> db.users.insert({name:"Quentin Balthazar", age:77, email:"test@example.com"})
> db.users.insert({name:"Alice Monteuil", age:65, email:"testtest@example.com"})
```

**Query collection**

```
> db.users.find().pretty()
{
	"_id" : ObjectId("5946517675f3fc671900a6c1"),
	"name" : "Eliott Pignon",
	"age" : 25,
	"email" : "eliott.pignon@laposte.net"
}
{
	"_id" : ObjectId("5946517f75f3fc671900a6c2"),
	"name" : "Quentin Balthazar",
	"age" : 77,
	"email" : "test@example.com"
}
{
	"_id" : ObjectId("5946518375f3fc671900a6c3"),
	"name" : "Alice Monteuil",
	"age" : 65,
	"email" : "testtest@example.com"
}
```
