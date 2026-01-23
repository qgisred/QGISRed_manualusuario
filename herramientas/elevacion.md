# Interpolación de Elevaciones (Cotas)

QGISRed permite asignar automáticamente la elevación a todos los elementos puntuales (nudos, depósitos y embalses) utilizando modelos digitales del terreno en formato ASCII.

### Formato del archivo MDT (ASCII)
El archivo debe seguir la estructura estándar de mallas ráster ASCII:

```text
NCOLS 100
NROWS 100
XLLCENTER 450000
YLLCENTER 4400000
CELLSIZE 5
NODATA_VALUE -9999
[Valores de elevación separados por espacios]
```

*   **XLLCENTER/YLLCENTER**: Coordenadas del centro de la celda inferior izquierda.
*   **CELLSIZE**: Resolución de la malla.
*   **NODATA_VALUE**: Valor que se ignorará durante la interpolación.

### Reglas de Aplicación
1.  **Selectividad**: Solo se interpolan nudos que tengan el valor de cota por defecto (0 o el configurado en opciones).
2.  **Preservación**: Si un nudo ya tiene una cota asignada manualmente o importada, el plugin respetará ese valor y no lo sobrescribirá.
3.  **Cobertura**: Si un elemento cae fuera de la malla MDT, se emitirá un aviso de incidencia.
