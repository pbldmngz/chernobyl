# [Pruébalo tu mismo](https://pbldmngz.github.io/chernobyl/)

-----

# No-Trashtalk
>Este es un nombre que se me ocurrió ahora, meses después, porque me di cuenta de que no le puse un **readme**.

**Project chernobyl** es un uso a la API de reconocimiento de voz de Google que hace un molesto sonido de cabra gritando cuando dices una de las palabras de la lista negra.
* Puede mejorarse haciendo que las palabras salgan de un JSON, me dio flojera
* A veces da la lata y se cicla en una palabra
* Puede no entenderte si hablas como yo
* Tienes que estan mirando la pantalla casi siempre ya que depende del navegador
* Como los navegadores no quieren publicidad invasiva, lo del sonido solo se pudo activar haciéndo que primero des un click en la página, es el único objetivo del botón

En definitiva, no me hago responsable y esto es marca ACME.

# Modo de uso
No he tenido tiempo de investigar como se jala desde un JSON así que de momento la lista negra de palabras está hardcodeada con estas palabras.

```javascript
var black_list = ["pinche", "pendejo", "verga", "madre", "madres", "puta", "p***", "palta", "sombrilla"];
```

Solo dale click al botón rojo, activa tu micrófono y di las palabras mágicas para escuchar tu castigo.
