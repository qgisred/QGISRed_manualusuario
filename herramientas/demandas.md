# Gestión de Demandas Nodales

QGISRed ofrece herramientas potentes para distribuir los consumos de agua de forma realista sobre la red.

### Métodos de Asignación
*   **Por Sectores (Polígonos)**: Reparte una demanda total conocida en un área geográfica entre todos los nudos contenidos en dicho polígono.
*   **Por Proximidad (Puntos)**: Asigna consumos individuales (por ejemplo, de una base de datos de facturación geo-referenciada) al nudo de demanda más cercano.

### Importación y Exportación Masiva
El plugin utiliza un formato de intercambio sencillo para gestionar miles de demandas:

| Campo | Descripción |
| :--- | :--- |
| **IdJunction** | Identificador del nudo en QGISRed. |
| **Demanda Base** | Valor numérico del consumo. |
| **IdPattern** | (Opcional) Identificador de la curva de modulación asociada. |

*   **Formato**: Archivo CSV separado por punto y coma (`;`) o coma (`,`).
*   **Borrado Selectivo**: Permite eliminar demandas de nudos seleccionados y, opcionalmente, limpiar las curvas de modulación que ya no se utilicen.

---
> 💡 **CONSEJO**:
> Puedes exportar el estado actual de todas las demandas a CSV, editarlas en Excel y volver a importarlas para realizar cambios masivos de forma externa.
