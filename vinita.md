Four types of loops
---------------------------------------
while (condition is true) {
  code to be executed;
}
---<!DOCTYPE html>
<html>
<body>

<?php  
$x = 1;
 
while($x <= 5) {
  echo "The number is: $x <br>";
  $x++;
} 
?>  

</body>
</html>

#second
do {
  code to be executed;
} while (condition is true);
---<!DOCTYPE html>
<html>
<body>

<?php 
$x = 1;

do {
  echo "The number is: $x <br>";
  $x++;
} while ($x <= 5);
?>

</body>
</html>

#Third
<!DOCTYPE html>
<html>
<body>

<?php  
for ($x = 0; $x <= 10; $x++) {
  echo "The number is: $x <br>";
}
?>  

</body>
</html>

#fourth
foreach ($array as $value) {
  code to be executed;
}

---<!DOCTYPE html>
<html>
<body>

<?php  
$colors = array("red", "green", "blue", "yellow"); 

foreach ($colors as $value) {
  echo "$value <br>";
}
?>  

</body>
</html>
