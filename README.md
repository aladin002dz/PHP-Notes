# PHP Notes:

## Variables and operators:
  ```php
  <?php
  $x = 10;  
  $y = 6;

  echo $x + $y;
  ?> 
  ```
## Conditions:
  ```php
  <?php
  if ($a > $b)
    echo "a is bigger than b";
  ?>
  ```
  
  ```php
  easy way to execute conditional html / javascript / css / other language code with php if else:

  <?php if (condition): ?>

  html code to run if condition is true

  <?php else: ?>

  html code to run if condition is false

  <?php endif ?>
  ```
## Loops:
### For: 
  ```php
  <?php 
  for ($x = 0; $x <= 10; $x++) {
      echo "The number is: $x <br>";
  } 
  ?>
  ```  
 
### Foreach:
  ```php
  <?php
  $colors = array("Red", "Green", "Blue");

  // Loop through colors array
  foreach($colors as $value){
      echo $value . "<br>";
  }
  ?>
  ```
  
### While:
  ```php
  <?php
  $i = 1;
  while($i <= 3){
      $i++;
      echo "The number is " . $i . "<br>";
  }
  ?>
  ```
### Comments: 
  ```php
  # this is a comment line
  // this is a comment line
  /* this is a comment line */
  ```
  
  
