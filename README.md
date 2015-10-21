# _php

##Comienzo con PHP

*El codigo PHP se escribe dentro de <?php y ?>*

##Imprimiendo con PHP con la funcccion echo

<?php echo "Imprimiendo con PHP"; ?>

*PHP puede ser escrito dentro de las etiquetas HTML*

<p><?php echo "PHP dentro de etiquetas HTML"; ?></p>

##String

*Un string o cadena es una palabra o una frase dentro de comillas ""*

<?php echo "Hello, world!"; ?>

##concatenacion

*Se realiza concatenacion con el punto .*

<?php  echo "Hello," . " " . "world" . "!"; ?>

##Aritmetica

<?php echo 7 * 5; ?>

#Variables

*Una Variable almacena algun tipo de dato*

$variable = "Julian";

$myVariable = 22;

<?php echo "soy " . $variable ."y tengo " . $myVariable ;

#Punto y coma

*En cada declaracion se termina con un ";"*

<?php echo "Use your semicolons!"; ?>

#Comentarios

*Los comentarios empienza con //*

<?php echo "un comentrario abajo"; 

 // Esto es un comentario en PHP 
 
 ?>
 
 #Comparaciones 
 
 *Lista de comparaciones*
 
*> Mayor que

*< Menor que

*<= Menor que o igual a

*>= Mayor que o igual a

*== Igual a

*!= Diferente a 

# Declaracion if 

<?php
   $numero = 7
   if($numero < 7){
      echo "numero es menor";
   }
 ?>
 
#Else

<?php
  $name = "Edgar";

  if ($name == "Simon") {
    print "I know you!";
  }
  else {
    print "Who are you?";
  }
?>


#Flujos de Control con if /elseif / else

if (condition) {

} elseif (condition) {

} else {

}

#Setencia Switch

*Busca el valor de switch y sale con break del switch*

switch (2) {
        case 0:
            echo 'The value is 0';
            break;
        case 1:
            echo 'The value is 1';
            break;
        case 2:
            echo 'The value is 2';
            break;
        default:
            echo "The value isn't 0, 1 or 2";
    }
    ?>
    
    
*Ejemplo*

$myNum = 2;

switch ($myNum) {
    case 1:
        echo "1";
        break;
    case 2:
        echo "2";
        break;
    case 3:
        echo "3";
        break;
    default:
        echo "None of the above";
}



#Multiple Cases. 

*Se puede seleccionar varios switch sin agregar el break*

 <?php
    $i = 5;
    
    switch ($i) {
        case 0:
            echo '$i is 0.';
            break;
        case 1:
        case 2:
        case 3:
        case 4:
        case 5:
            echo '$i is somewhere between 1 and 5.';
            break;
        case 6:
        case 7:
            echo '$i is either 6 or 7.';
            break;
        default:
            echo "I don't know how much \$i is.";
    }
 ?>
    
 #




 
 
 
