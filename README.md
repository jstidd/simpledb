#Simple DB

This just sets up a PHP PDO connection with MySQL. This initial version is just setup for my convenience. 

```
SimpleDB\SimpleDB($server, $database, $username, $password);
```

Methods: 

- select($sql, $data) returns array

The following four methods are the same except in name to ease reading code when using the class.

- insert($sql, $data) 
- update($sql, $data) 
- delete($sql, $data) 
- execute($sql, $data)

Or you can use just the connection

- rawConnection()
