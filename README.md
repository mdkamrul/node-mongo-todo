# node-mongo-todo
simple todo app using nodejs, mongo

We use postman for testing
1. To select all todo use GET request
	http://localhost:3000/tasks

2. To add new todo use POST request
	http://localhost:3000/tasks <br>
	{
		"__v": 0,
		"name" : "test",
		"_id" : "53cb6b9b4f4ddef1ad47f943",
		"status" : [
			"pending"
		],
		"Create_date" : "2018-0101T10:02:02.584Z"
	}