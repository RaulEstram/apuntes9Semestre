# Prolog

## Variables o Variables logicas

Las variables en Prolog no son variables en el sentido habitual, por eso las llamamos variables lógicas. Se escriben como una secuencia de caracteres alfabéticos comenzando siempre por mayúscula o subrayado. Ejemplos de variables:

  Variable 
  _Hola  


El hecho de que los nombres de variables comienzen por mayúscula (o subrayado) evita la necesidad de declarar previamente y de manera explícita variables, tal y como ocurre en otros lenguajes.  

## Variable anonima

Existen variables sin nombre, y todas ellas se representan mediante el símbolo de subrayado _. Pero cuidado, aunque todas las variables anónimas se escriben igual, son todas distintas. Es decir, mientras que dos apariciones de la secuencia de caracteres Hola se refieren a la misma variable, dos apariciones de la secuencia _ se refieren a variables distintas.

## COndicional 

```prolog
elCondicional :-
    write('¿Cuál es la palabra mágica?'), nl,
    read(Palabra),
    Palabra == 'hola' -> 
        write('¡Hola! Has acertado.')
        ; 
        write('No has acertado.').
```