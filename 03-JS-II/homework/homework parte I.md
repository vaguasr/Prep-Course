1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `for`
* `&&`, `||`, `!`

// FOR
 Es un Bucle, es decir elemento que se repite de manera ciclica. Si declaramos las condiciones correctas 
 el bucle tendra un inicio y un fin, de lo contrario podria ejecutarse de manera infinita.
 FOR nos sirve para ejecutar tareas que son repetitivas sin necesidad de redactar varias veces la mismas expresiones,
 se recomienda el uso de FOR cuando conocemos bien las condiciones que determinaran la salida del Bucle.
 Si solo se conoce las condiciones que debe cumplir para el inicio, se recomienda While.

 // AND o '&&'
 And (Y), nos sirve para hacer cumplir dos o mas condiciones cuando estamos manejando booleanos.
 Es decir que nos ayudan para no tener que escribir varias veces una condicional (if)

 Ejemplo . Detectar cuando un numero es mayor que 20 pero menor que 50
 En vez de hacer dos condicionales:
if (n > 20){
    if (n < 50){
        return true
    }
} return false
 Podemos hacer un solo condicional que pida que se cumplan las dos condiciones al tiempo
 if (n > 20 && n < 50) return true
 return false

 // OR o '||'
 OR (o), tiene el mismo uso que AND. A diferencia de AND en donde todas las condiciones tienen que cumplirse al tiempo, cuando
 usamos OR '||' basta con que una de las condiciones se cumpla para que el resultado sea 'true'

 NOT o '!'
 Not es utilizado para negacion, al utilizarse como prefijo de algo, se esta indicando que es contrario

 Por ejemplo 
 Igual '==' ; No es igual '!==' 
 Verdadero 'True' ; Negacion verdadero '!True' === 'False'
 

