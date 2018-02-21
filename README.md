# Prueba_BackEnd_PHP

<?php
  $numero = 1;
  while ($numero <= 100) {
    if ($numero % 3 == 0 && $numero % 5 == 0) {
      echo 'FizzBuzz';
    }
    elseif ($numero % 3 == 0) {
      echo 'Fizz';
    }
    elseif ($numero % 5 == 0) {
      echo 'Buzz';
    }
    else {
      echo $numero;
    }
    $numero++;
  }
?>
