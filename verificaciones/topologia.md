# Verificación de Topología y Conectividad

Estas herramientas aseguran que la estructura física de tu red sea correcta y que no existan errores que impidan la simulación.

### Herramientas de Topología
*   **Consolidar Datos**: Proceso fundamental para asegurar que todos los cambios manuales en las tablas de atributos se sincronicen correctamente con el modelo interno del plugin.
*   **Elementos Superpuestos**: Detecta y elimina tuberías, nudos, válvulas o bombas que compartan exactamente la misma ubicación geográfica, evitando redundancias.
*   **Simplificar Vértices**: Elimina vértices intermedios en tramos rectos de tuberías. Esto optimiza el rendimiento gráfico y simplifica el modelo sin alterar su longitud.
*   **Unión de Tuberías**: Fusiona automáticamente tramos de tubería que tengan idéntico diámetro, material y año de instalación, reduciendo la fragmentación del modelo.
*   **Conexiones Tipo T**: Resuelve situaciones donde un nudo de extremo coincide sobre el trazado de una tubería, dividiéndola en dos y estableciendo la conexión real.

### Análisis de Conectividad
Esta utilidad identifica qué partes de la red están aisladas de las fuentes de suministro.
*   **Detección de Subzonas**: El plugin agrupa los elementos en subredes conectadas.
*   **Limpieza Automática**: Ofrece la opción de eliminar automáticamente aquellas subzonas que tengan un número de tuberías inferior al umbral definido por el usuario (útil para limpiar "basura" topológica tras una importación desde GIS).
