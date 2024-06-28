# Lab2
# Trabajo Práctico: Clases Genéricas - Java

## Descripción
Este proyecto contiene la implementación de diversos ejercicios sobre clases genéricas en Java, correspondientes al Trabajo Práctico 1 del curso de Laboratorio II del ciclo lectivo 2023. 

## Ejercicios

### Ejercicio 1: Interfaz Genérica Operable
Implementación de una interfaz genérica `Operable` que declara las cuatro operaciones básicas: suma, resta, producto y división.

### Ejercicio 2: Pila Genérica
Implementación de una clase `PilaArray` que utiliza un array genérico y un entero que cuenta el número de objetos insertados. La clase incluye métodos para añadir, extraer y obtener el primer elemento, así como para verificar si la pila está vacía.

### Ejercicio 3: Gestión de Productos
Implementación de una clase `Producto` y una clase `Almacen` que puede almacenar productos de diferentes tipos. Se utiliza un comodín `<? extends Producto>` para imprimir una lista de productos.

### Ejercicio 4: Almacenamiento de Elementos Superclase de Producto
Implementación de una clase `AlmacenSuper` que puede almacenar elementos de cualquier tipo que sean superclases de `Producto`. Se utiliza un comodín `<? super T>` para imprimir una lista de elementos.

## Estructura del Proyecto
El proyecto está organizado en cuatro paquetes, uno para cada ejercicio:
- `ejercicio1`
- `ejercicio2`
- `ejercicio3`
- `ejercicio4`

## Requisitos
- Java Development Kit (JDK) 8 o superior
- Un entorno de desarrollo integrado (IDE) como IntelliJ IDEA, Eclipse, o NetBeans

## Instalación y Ejecución
1. Clona el repositorio en tu máquina local:
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
