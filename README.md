# Taller-semana-4.

1.  En el public int estamos declarando una propiedad y declaramos getters y setters de esa propiedad
tiene dos constructores con el mismo nombre de la clase.
la primera version no tiene argumentos y el segundo tiene un entero que es el numero de lados del poligono y no tiene
por que funcionar no tiene el metodo main.

2. El size es una propiedad, hay un metodo square para poder acceder a la clase y el NumberOfSides esta definido en la anterior
clase, esto es lo que nos permite hacer la herencia.

3. un primer polygon sin argumentos, tiene 0 lados. despues un triangle con 3 lados, un square de 4.5 y un polygon de 4.5.
square es un polygon, por que square hereda de polygon. en el heap se crea un Square en donde tiene adentro dos propiedades tipo
valor que son size y number.
Tiene un miembro en el heap que se llama base  y otro size, el primero almacena la direccion de un nomberofsides en donde 
este esta en un polygon dentro del heap; el base y el size estan dentro de una clase square.

4. no puedo acceder a los miembros del square al ser una restriccion del programa.

5. si, por que se esta haciendo un cast en la palabra polygon para que el compilador lo entienda como un square

6. no, por que la herencia funciona en un solo sentido, no todos los polygons son squares.

7. si se imprime por que se realiza un cast para que entienda que es un square.

8. Hay errores en tiempo de ejecucion, el error es que el compilador es que al hacer el cast el lo entiende como un square pero
no lo es.

10. si compila

11. el as me permite detectar errores en tiempo de ejecucion. 

12. si lo puedo hacer, por que puedo almacenar la direccion de un objeto square.

13. va a imprimir un 4 por que el Base. permite acceder a los metodos originales de la clase Square que son 4 lados.

C1: las clases private no permite acceder dentro las variables que las contiene mientras que el public si los permite.

14. si por que el square es el polygon y puede acceder a el.

15. partial: para poder definir una clase por pedazos, definir una parte en un archivo y la otra en otro archivo.

16. no necesita.






