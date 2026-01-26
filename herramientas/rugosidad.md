# Gestión y Conversión de Rugosidad

Una de las potencias de QGISRed es la gestión dinámica de la rugosidad basada en el material y la antigüedad de la infraestructura.

### Cálculo por Edad y Material
El plugin estima el coeficiente de rugosidad cruzando la **Fecha de Instalación** y el **Material** de la tubería con la **Tabla de Materiales** del proyecto.

1.  Busca el material en la tabla para obtener la rugosidad inicial ($\epsilon_0$).
2.  Calcula la edad actual (años desde la instalación).
3.  Aplica el incremento anual de rugosidad configurado.

### Conversión entre Fórmulas
QGISRed permite convertir coeficientes de rugosidad automáticamente cuando cambias la fórmula de pérdida de carga del proyecto:

*   **Darcy-Weisbach (D-W)** $\leftrightarrow$ **Hazen-Williams (H-W)**
*   **Darcy-Weisbach (D-W)** $\leftrightarrow$ **Chezy-Manning (C-M)**

> ❗ **IMPORTANTE**:
> Al cambiar la fórmula en las **Opciones Hidráulicas**, el plugin te preguntará si deseas realizar la conversión masiva de todas las rugosidades existentes para mantener la coherencia física del modelo.

### Tabla de Materiales
Puedes configurar los coeficientes base en `Project > Materials Table`. Es fundamental usar los acrónimos correctos (ej: `PVC-O`, `PEAD`) para que la vinculación sea efectiva.
