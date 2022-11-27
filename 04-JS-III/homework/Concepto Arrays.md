Concepto Arrays

Los Arrasys son como un repositorio de datos capaces de guardar una lista
de elementos que pueden ser consultados y modificacdos.

Esto resulta util al momento de capturar, guardar y consultar datos porque
evita que tengamos que crear un alto numero de variables o constantes.

/Los arrays son declarados mediante los Brackets []
/Las posiciones son identificadas desde el 0
Es decir que la primera posicion es 0, la segunda posicion es 1 y asi sucesivamente

Array [a, b, c, d]
       0  1  2  3

atraves de las funciones .push y .pop puedes agragar o eliminar el/los dato(s)
que se encuentren ubicados en la ultima posicion del array.

Ejemplo.
Si tienes un Array llamado Lista

Var Lista = [a, b, c, d, e, f, 1, 2, 3, 4]

Mediante la funcion push podras agregar un elemento nuevo, despues del 4 es decir el array que actualmente tiene como ultima posicion [9] en la cual
esta ingresado el 4.

Si hacemos
Lista.push() = 5

El array nuevo quedara asi

Lista;
[a, b, c, d, e, f, 1, 2, 3, 4, 5]

El array ya no tiene 10 posiciones sino 11. Ya que el 5 fue agregado a la a posicion [10] (es decir la onceaba posicion).

la funcion pop actua contraria, ya que elimina te devuelve el valor al tiempo que lo elimina del array.

Es decir, si hacemos

Lista.pop()
5 // Te devolvera el 5 y podras utilizarlo.

Al consultar el array te quedaria asi

Lista;
[a, b, c, d, e, f, 1, 2, 3, 4]
// Como puedes observar el 5 fue eliminado de la posicion [10]