# Funciones en PHP

## ¿Qué es una función en PHP?
Una función en PHP es un bloque de código que se puede reutilizar. Permite agrupar una serie de instrucciones bajo un nombre específico y luego llamarlo cuando sea necesario.

## Estructura de una Función
La estructura básica de una función en PHP incluye la palabra clave `function`, seguida del nombre de la función, paréntesis y el bloque de código entre llaves `{}`.



### 3. ¿Cuándo Usar Funciones en PHP?

Se recomienda usar funciones cuando:

Se necesita reutilizar el mismo código en varias partes del programa.
Se quiere modularizar el código para hacerlo más organizado. 
Se desea mejorar la legibilidad y mantenimiento del código.
Se busca reducir errores al minimizar la repetición de código.

##### Ejemplos de codigo

```php


     function nombreFuncion() {
        // Código a ejecutar
    }
    
    function suma($a, $b) {
    return $a + $b;
    
    }
     echo suma(5, 3); // Imprime: 8
      
      function aumentarValor(&$numero) {
        $numero += 10;
      }
    
    $valor = 5;
    aumentarValor($valor);
    echo $valor; // Imprime: 15


 


 
 
 
 