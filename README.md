
## Multiplicar Console App

Es una aplicación para generar archivos .txt de tablas de multiplicar por medio de consola; utilizando Yargs para la introducción de datos.

Ejecutar este comando
````
npm install
````

Para utilizar la aplicación, abrir una ventana de consola e introducir:
Debemos de reemplazar:
    x para indicar el limite de la tabla de multiplicar
    y para indicar la base o que usaremos para la tabla de multiplicar
Esto creara un archivo con el nombre "tabla-y-al-x.txt" ("x" y "y" son reemplazados por los valores introducidos)
````
node apps crear --limite x -b y
````

Si solo deseamos mostrar el resultado en consola debemos de introducir el siguiente comando (es similar al anterior, solo que este es listar):
````
node apps listar --limite x -b y
````

### Ejemplo de uso:

#### Crear
node apps crear --limite 10 -b 5
Creara un archovo .txt y mostra un mensaje indicando:

Archivo creado: tabla-5-al-10.txt

#### Listar
node apps listar --limite 10 -b 5

Mostrará en consola el siguiente resultado:

==================================
tabla de 5
==================================
5 * 0 = 0
5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
5 * 4 = 20
5 * 5 = 25
5 * 6 = 30
5 * 7 = 35
5 * 8 = 40
5 * 9 = 45
5 * 10 = 50



