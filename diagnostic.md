# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
To store data which you can read/manipulate
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller layer.  Is this a trick question cause its too early for that shiz.
```

Which layer in the MVC pattern communicates with the model?

```bash
The model layer.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Theyre silly and outdated.
```

What does C.R.U.D stand for?

```bash
Create Read Update Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The model
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
GET PATCH DELETE CREATE DESTROY
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
That request goes to the server which communicates with the controller.  The controller
then communicates with the model who retrieves the data from the database and returns it to the
controller.  Then the info moves back up the chain to the server and then the user.
  ```

What is the command to generate a new rails-api app?

```bash
rails new <appname>
```

What is the command to start an instance of a rails server?

```bash
rails s```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
db:drop
db:create
db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
rails generate scaffold Pet name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
It formats the JSON that the server gets back from the controller.
You can custom generate a serializer to your specifications.
```
