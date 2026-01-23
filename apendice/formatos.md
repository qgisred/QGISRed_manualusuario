# Formatos de Datos y Archivos DBF

Para los usuarios avanzados que prefieran editar los datos directamente desde las tablas de QGIS o archivos externos, aquí se detallan los formatos técnicos requeridos.

### Formato de Fechas
El campo `InstalDate` en la capa de tuberías debe seguir estrictamente el formato:
**`yyyyMMdd`**
*   **yyyy**: Año (4 dígitos).
*   **MM**: Mes (2 dígitos, con cero inicial si es necesario).
*   **dd**: Día (2 dígitos).
*   *Ejemplo*: `20230715` para el 15 de julio de 2023.

### Gestión de Patrones y Curvas (DBF)
Los datos de patrones y curvas se almacenan en tablas `.dbf`. Al editarlas manualmente ten en cuenta:
*   **Orden**: Existe un campo de orden que indica la posición del factor dentro de la serie.
*   **Separadores**: Si editas fuera de QGIS, asegúrate de mantener la coherencia con el separador decimal (punto).

### Gestión de Reglas (Rules)
Las reglas en las tablas de atributos pueden aparecer desordenadas. Para visualizarlas correctamente, ordena la tabla por estas columnas en este orden:
1.  **RuleOrder**: Agrupa todas las líneas de una misma regla.
2.  **LineOrder**: Define el orden lógico de las condiciones (IF, AND, OR, THEN, ELSE).

### Campo "Name"
QGISRed añade una columna `Name` a las reglas y controles. Este campo no afecta a la simulación pero permite identificar visualmente la función de cada línea en el formulario del plugin.
