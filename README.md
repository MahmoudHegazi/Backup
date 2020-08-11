# Backup

#secure, webserver and good form valdation

Bloging_system CMS , it has php CRUD, handle dynamic content, not relational database


## must used 

```php

// any query
$con = mysqli_connect($user, $pass, $db_name);
$query = "SELECT * FROM posts";
$result = mysqli_query($con, $query);

while ($row = mysqli_fetch_assoc) {
  print_r($row);
  //$row['post_id'];
  // we can use mysqli_fetch_array for the values can contains without spacifc name or not unknown data
}

```
