# Mixed Martial Arts Project

This project will have you building a backend restful crud api and a front-end react application around it.
Below are some user stories to help you complete this project.

## Api
The api should be built around a fighter resource. The resource should contain the following columns
```
id
name
bio
style
image_url
strength
```
The strength column should be a number between 1 - 100.


__#1__
```
As a user when I make a GET request to /fighters
I should get back an array of all the fighters in the database
```

__#2__
```
As a user when I make a GET request to /fighters/:id
I should get back a fighter matching the id in the route parameter
```

__#3__
```
As a user when I make a POST request to /fighters and pass json data
it should insert the fighter based off the JSON data passed
```

__#4__
```
As a user when I make a PUT request to /fighters/:id and pass json data
it should update the fighter matching the id in the route parameter based off the JSON data passed
```

__#5__
```
As a user when I make a DELETE request to /fighters/:id
it should delete the fighter matching the id in the route parameter
```
