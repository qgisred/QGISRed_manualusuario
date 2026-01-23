# Edición de Propiedades

Acceder y modificar los datos de tus elementos es sencillo gracias a los formularios inteligentes de QGISRed.

![Icono Propiedades](../assets/icons/properties.png)

### El Diálogo de Propiedades
Al seleccionar un elemento con esta herramienta, se abre una ventana intuitiva que te permite:
*   **Modificar atributos**: Cambia diámetros, rugosidades, demandas, etc.
*   **Navegación (Browser)**: Desplázate rápidamente a los elementos conectados o revisa los que has visitado recientemente sin cerrar la ventana.
*   **Centrar elemento**: Botón para localizar visualmente el elemento seleccionado en el mapa.

### Métodos Alternativos
1.  **Tabla de Atributos**: Abre la tabla de la capa (Pipes, Junctions, etc.) y usa la calculadora de campos para ediciones masivas.
2.  **Identificador de QGIS**: Si activas "Auto open form" en el identificador nativo de QGIS, el formulario de QGISRed se abrirá al hacer clic.

---

### Datos Específicos de QGISRed
Existen campos adicionales que no están en EPANET pero son vitales para el plugin:
*   **Material**: El material de la tubería (usa el acrónimo de la tabla de materiales).
*   **InstalDate**: Fecha de instalación con formato `yyyyMMdd` (ej. 20240115).
*   **IsActive**: En el Gemelo Digital, permite habilitar o deshabilitar elementos como acometidas.
