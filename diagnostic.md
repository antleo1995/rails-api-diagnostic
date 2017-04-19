# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
A backend processes and stores data - allows for persistance and shared workload
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Controller layer
```

Which layer in the MVC pattern communicates with the model?

```md
Model layer
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Good question, not sure I know why
```

What does C.R.U.D stand for?

```md
CREATE
READ
UPDATE
DESTROY
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index
Show
Create
Update
Patch
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1) Client requests data
2) Server communicates with the controller
3) Controller communicates with model
4) Data is sent to the server
5) Server gives data to client
6) Client displays the data
```

What is the command to generate a new rails-api app?

```bash
rails new someapp
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
* rails db:drop
* rails db:create
* rails db:migrate
* rails db:seed
* not sure why we need 5 bullet points for 4 commands but ok....
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails generate scaffold Pet name:string age:int
```
