
## Multiplicar Console App

Es una aplicación para generar archivos .txt de tablas de multiplicar por medio de consola; utilizando Yargs para la introducción de datos.

#### Instalar paquetes de npm
````
npm install
````

#### Instrucciones
Para utilizar la aplicación, abrir una ventana de consola e introducir:
>"x" para indicar el limite de la tabla de multiplicar

>"y" para indicar la base que usaremos para la tabla de multiplicar

````
node apps crear --limite x -b y
````
Esto creará un archivo con el nombre "tabla-y-al-x.txt" ("x" y "y" deben de ser reemplazados por los valores numericos)

Si solo deseamos mostrar el resultado en consola debemos de introducir el siguiente comando (es similar al anterior, solo que este es listar):
````
node apps listar --limite x -b y
````

### Ejemplo de uso:

#### Para Crear
>node apps crear --limite 10 -b 5

Creará un archivo .txt y mostra un mensaje en consola indicando:

Archivo creado: tabla-5-al-10.txt

#### Para Listar
node apps listar --limite 10 -b 5

Mostrará en consola el siguiente resultado:
>==================================

>tabla de 5

>==================================
>5  * 0 = 0

>5 * 1 = 5

>5 * 2 = 10

>5 * 3 = 15

>5 * 4 = 20

>5 * 5 = 25