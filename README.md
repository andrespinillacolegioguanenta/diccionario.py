# DICCIONARIOS EN PYTHON
Conceptos y ejercicios de diccionarios en Python

- Los diccionarios son datos estructurados, es decir, hacen referencia a una colección de datos
- Son una coleccion desordenada de pares de datos de la forma **clave:valor**, conocidos como elementos o items.
- Son mutables, una vez definido se le pueden agregar nuevos elementos, modificar o eliminar algunos de los que ya tiene.
- Tambien son conocidos como arreglos asocíativos.
## Representación gráfica den un diccionario
![alt text](image.png)
## Sin taxis
`nombre_diccionario = {clave1:valor1, clave2:valor2,....}`

- Cada item o elemento tiene la forma **clave:valor**
- En cada item hay una clave y uno o mas valores. Si se descconoce el valor, se puede complementar con *None*
- Los elementos del diccionario se indexan por la clave.
- Las claves solo pueden ser inmutales.
- Los valores pueden ser datos mutables o inmutables
- Las claves no pueden repetirsen dentro de un diccionario.

## Ejemplo
`frutas = {'manzanas':34, 'pera':45}`

## Operaciones

### Agragar elementos
`nombre_diccionario[clave] = valor`

`frutas['cereza'] = 90`

### Consultar o modificar elementos
`print('el valor de pera es: ', frutas['pera'])`

### Eliminar elementos
`del frutas ['pera']`

### Operador de pertenencia
``` python
if 'cereza' in frutas:
    print('Si esta cereza en el diccionario')
else:
    print('No está cereza en el diccionario')
```
## Ejercicio
Cree un programa en Python que utilice un diccionario para guardar los nombres de sus amigos y su telefono.  En este caso, el diccionario representa una agenda telefónica.  El programa pedirá nombres y telefonos y los irá guardando en el diccionario (los nombres en mayúscula).  Además, el programa debe permitir consultar o eliminar un telefono.  Incluya un menú de opciones.