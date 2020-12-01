## Opening/closing PHP

```php
<?php

// Your code here

?>
```

## Data types

| Type | Description | Example |
| - | - | - |
| `String` | Represent textual content can be presented with double quote " or single quote ' | `"Hello world"` |
| `Integer` | Represent a full numeric value | `313` |
| `Float` | Represent a decimal value | 3.14 |
| `Boolean` | Represent a TRUE or FALSE state | `TRUE` or `FALSE` |
| `Array` | Represent a list of data | `['Deeppink', 'Lime', 'Firebrick']` or `['firstname' => 'John', 'lastname' => 'Doe']` |
| `Object` | Represent an object of values | `new Car('Black', 'Volvo')` |
| `Null` | Represent a variable, which has no value | `NULL` |

## Arithmetic (math) Operators

| Operator | Description | Example |
| - | - | - |
| `+` | Addition | `$sum = $x + $y;` |
| `-` | Subtraction | `$sum = $x - $y` |
| `-` | Multiplication | `$sum = $x * $y` |
| `-` | Division | `$sum = $x / $y` |
| `%` | Division (Remainder of division) | `$sum = $x % $y` |

## Comparison operators

| Operator | Description | Example |
| - | - | - |
| `==` | Equal value | `$x == $y` |
| `===` | Equal value and type | `$x === $y` |
| `!=` | Not equal value | `$x != $y` |
| `!==` | Not equal value and type | `$x !== $y` |
| `>` | Greater than | `$x > $y` |
| `<` | Less than | `$x < $y` |
| `>=` | Greater than or equal | `$x >= $y` |
| `<=` | Less than or equal | `$x <= $y` |

## Assignment operators (arithmetic)

| Assignment | Short for | Description |
| - | - | - |
| `$x = $y` | `$x = $y` | The left operator get value of the right operator |
| `$x += $y` | `$x = $x + $y` | Add Integer value $y to $x |
| `$x -= $y` | `$x = $x - $y` | Subtract value $y from $x |
| `$x *= $y` | `$x = $x * $y` | Multiply value $y to $x |
| `$x /= $y` | `$x = $x / $y` | Divide value $y from $x |
| `$x %= $y` | `$x = $x % $y` | Get the remainder (modulus) of the division value of $x / $y |
| `$x++` | `$x = $x + 1` | Add 1 to $x |
| `$x--` | `$x = $x - 1` | Remove 1 from $x |

## String operators

| Operator | Description | Example |
| - | - | - |
| `.` | The concatination operator | `echo 'Hi ' . $name;` |
| `.=` | Concatination assignment | `$greeting .= $name;` |
