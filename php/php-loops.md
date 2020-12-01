Loops is typically used to iterate through an array

### For loop

```php
$myArray = ['a', 'b', 'c', 'd', 'e'];

for($i = 0; $i < count($myArray); $i++) {
    echo $myArray[$i] . '<br>';
}
```

### While loop

```php
$myArray = ['a', 'b', 'c', 'd', 'e'];
$i = 0;

while($i < count($myArray)) {
    echo $myArray[$i] . '<br>';
    $i++;
}
```

### Foreach

```php
$users = [
    [ 'username' => 'john', password: '1234' ],
    [ 'username' => 'jane', password: 'qwer' ],
];

foreach($users as $key => $user) {
    echo 'User with index ' . $key . ' has password: ' . $user['password'] . '<br>';
}
```

