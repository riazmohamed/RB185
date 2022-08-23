# Index

* [Interacting with a database in code](#Interacting-with-a-database-in-code)



## Interacting with a database in code

#### Getting Started

Focus on the database interaction and not the application. How to dynamically generate SQL from Ruby

#### Connecting to a pgSQL database in Ruby

pgGem - postgres adapter in Ruby

Creatating  a new connection object in Ruby using `pry` instead of `irb`	

* db = PG.connect(dynamo: "films") => `the #connect method is just a convienient method that instantiates a new pg connection object using all the arguments that we have provided to it`
* `show-method PG.connect` => the method
