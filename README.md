# gitflow-diagnostic-matiasmasjuan

### Aspectos implementados:
* Se inició un archivo jupyter notebook ```main.ipynb``` que tendrá las 4 funciones solicitadas en el enunciado, además de la función ```main``` que es la que pide los inputs y llama a las funciones.
* La entrega fue desarrollada en un jupyter notebook, por lo que basta con correr todas las celdas de forma secuencial, y en la última se llamará a la función ```main``` que abrirá el menú, pedirá los inputs y entregará los resultados según la opción elegida.

### Gitflow:
Para esta entrega se realizó una rama ```development``` a partir de ```main```. Luego, desde ```development``` salieron ```function-one```, ```function-two```, ```function-three```, ```function-four```, ```function-main```. Cada una de estas *branches* resolvió una función a implementar. Apenas una función estaba terminada, se realizaron *commits* y *Pull Requests* para realizar el *merge* con la rama ```development```. Si bien era un poco redundante realizar *PR* cuando yo era el único contribuidor, era parte del objetivo de esta entrega. Finalmente, una vez todas las *branches* estaban terminadas, se hizo una *PR* final a ```development```, y una vez que se haya testeado el correcto funcionamiento en ```development```, se realizó la última *PR* para *mergear* a ```main```. 
### Consideraciones:
* Se añadió el archivos json al ```.gitignore``` para no ser subida al repositorio. Es importante que al momento de ejecutar el notebook, el archivo se encuentre en el mismo directorio que ```main.ipynb```