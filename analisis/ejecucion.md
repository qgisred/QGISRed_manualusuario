# Ejecución y Opciones Hidráulicas

Configura todos los parámetros del motor de EPANET directamente desde QGIS.

### Opciones de Análisis
Desde el menú **Analysis > Analysis Options**, puedes configurar:
*   **Hidráulica**: Unidades de caudal, fórmulas de pérdida de carga (D-W, H-W, C-M) y gravedad.
*   **Calidad**: Análisis de cloro, edad del agua o traza de fuente.
*   **Tiempos**: Duración de la simulación, paso de tiempo hidráulico y de calidad.
*   **Energía**: Precios de electricidad y eficiencia de las bombas.

> 💡 **NOTA**:
> En la pestaña **General**, también puedes habilitar el modelo **PDA (Pressure Dependent Analysis)** para simulaciones donde la demanda varía con la presión local.

### El Reporte de EPANET
Al finalizar una simulación exitosa, QGISRed muestra automáticamente el reporte de texto generado por la *Toolkit* de EPANET. Este archivo contiene el balance de masa, advertencias de nudos con presión negativa y el resumen de la convergencia.
