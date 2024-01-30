# taller-semana16
## Generar una miniespecificación
### Usar dos funciones y un procedimiento
1) Resolver:

Dados los sueldos de 3 conductores ; generar una solución que permita encontrar la suma de los sueldos por cada conjunto de valores de los conductores.

La problemática sugiere el uso de estructuras de datos.

Los sueldos están en un arreglo bidimensional llamado sueldos; sueldos tiene 3 filas y 4 columnas. 
```
sueldos <-- { {100.2, 300.2, 400.2, 100.3} , {200.2, 300.4, 400.2, 222.2} , {300.2, 400.1, 300.9, 400.4} }
```
Los nombres de los conductores están en un arreglo unidimensional que tiene 3 elementos. El arreglo se llama conductores.
```
conductores <-- {"Juan Peréz", "Gabriela Lima", "Homero Salas"}
```

**Atención**; los valores del arreglo sueldos de la fila del índice 0 pertenecen al conductor del índice 0 del arreglo conductores; y así con cada fila de sueldos e índice de conductores

Cada suma de sueldos de un conductor deberá ser almacenado en una posición de un arreglo unidimensional llamado sumaSueldo; resaltar que el arreglo sumaSueldo tendrá 3 elementos.

Al final se debe presentar el siguiente reporte:
```
Conductor: Juan Peréz con total de sueldos ?
Conductor: Gabriela Lima con total de sueldos ?
Conductor: Homero Salas con total de sueldos ?
```
