# App De Notas

Para esta app de notas necesitamos estos **casos**:
1. Ver todas las notas
2. Guardar una nota
3. Ver las notas filtradas por pendientes
4. Dar una respuesta en *caso de errores*


Tenemos una serie de preguntas para poder arrancar:
- ¿De qué tipo de dato deberían ser **una nota**?
>Necesitamos dos datos string, el titulo y el estado
- ¿Cómo podemos guardar muchas notas?
>Tenemos un tipo de dato que almacena muchos valores
- Necesitamos tomar éstos datos de algún lado. ¿Existe alguna forma?
>Recordá que por ahora solo estamos en el backend, no tenemos interface mas que la terminal
- ¿Vamos a usar modulos nativos? o ¿Podríamos usar modulos externos?
>Tenemos una variable que nos sirve para procesar lo que hay en la terminal 
- Necesitamos guardar estos datos en JSON ¿Cómo hacemos para manipularlos?
>Tenemos un modulo nativo para leer archivos y para escribirlos
- ¿Cómo contemplamos cada **caso**?
>Una estructura que evalua de la misma variable, diferentes casos por ejemplo