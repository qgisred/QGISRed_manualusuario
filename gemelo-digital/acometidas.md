# Acometidas y Gestión de Demanda Individual

El Gemelo Digital de QGISRed permite modelar la red hasta el nivel de cliente individual mediante las acometidas.

### Modelado de Acometidas
*   **Dibujo Geométrico**: Puedes trazar acometidas manualmente desde la tubería principal hasta el límite de parcela.
*   **Autocompletado**: Herramienta para generar automáticamente el tramo perpendicular a la tubería más próxima desde un punto de suministro.
*   **Campo IsActive**: Permite simular rápidamente la baja o corte de suministro de usuarios específicos.

### Conversión de Acometidas
Las acometidas en QGISRed pueden tratarse de dos formas en el modelo hidráulico final:
1.  **Nudo Puntual**: La demanda se asigna directamente al nudo de conexión.
2.  **Tramo Lineal**: La acometida se convierte en una tubería de pequeño diámetro, permitiendo simular las pérdidas de carga en la conexión del cliente.

### Telelectura (Smart Metering)
QGISRed soporta la integración de datos de contadores inteligentes. Los formatos permitidos para importar series temporales son:
*   **Formato Tabla**: `Time; Id1; Id2; ...` (Columnas por contador).
*   **Formato Serie**: `Id; Time; Demand` (Un registro por fila).

---
> [!TIP]
> Puedes exportar todos los datos de telelectura acumulados a un único fichero CSV para su análisis externo.
