# Arrays en PHP

Los **arrays** en PHP son estructuras de datos que permiten almacenar múltiples valores bajo un mismo nombre. Los valores son accesibles mediante índices.

## Tipos de Arrays

### 1. **Unidimensionales**
Son listas simples de elementos.


**Ejemplo en PHP:**

    $numeros = [1, 2, 3, 4, 5];


### 2. Bidimensionales
Matrices que contienen filas y columnas.


**Ejemplo en PHP:**
    
    $matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
    ];

### 3. Multidimensionales
Arrays con más de dos dimensiones.

**Ejemplo en PHP:**

    $cubo = [
    [
    [1, 2],
    [3, 4]
    ],
    [
    [5, 6],
    [7, 8]
    ]
    ];

## Cómo Acceder a los Elementos de un Array
1. Unidimensionales
   Se accede mediante el índice.

**Ejemplo en PHP:**

    $primer_numero = $numeros[0];  // Accede al primer elemento

### 2. Bidimensionales
   Se accede especificando fila y columna.

**Ejemplo en PHP:**
    
    $elemento = $matriz[1][2];  // Accede al elemento en la segunda fila, tercera columna

### 3. Multidimensionales
   Se accede especificando cada dimensión.


**Ejemplo en PHP:**

    $valor = $cubo[0][1][1];  // Accede al valor en la primera capa, segunda fila, segunda columna

## Cómo Modificar un Array

### 1. Agregar Elementos
   Se puede usar el método **array_push()** para agregar elementos a un array unidimensional.

**Ejemplo en PHP:**

    array_push($numeros, 6);  // Agrega el número 6 al final del array

## 2. Eliminar Elementos
   Se puede usar el método unset() para eliminar un elemento específico.

**Ejemplo en PHP:**

    unset($numeros[2]);  // Elimina el tercer elemento del array (índice 2)

## Cómo Recorrer Arrays

### 1. Usando un ciclo for
   Itera sobre los elementos del array.

**Ejemplo en PHP:**

    foreach ($numeros as $numero) {
    echo $numero;
    }

### 2. Arrays Asociativos
   Son arrays donde los índices son cadenas de texto.

**Ejemplo en PHP:**

    $persona = [
    "nombre" => "Juan",
    "edad" => 30
    ];
    foreach ($persona as $clave => $valor) {
    echo "$clave: $valor";
    }

### Cómo Buscar Elementos en un Array
## 1. En Arrays Unidimensionales
En PHP, se puede usar el operador in_array() para verificar si un elemento existe en el array.


**Ejemplo en PHP:**



 

