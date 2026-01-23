# Controles y Reglas

Define la lógica operativa de tu red (ej: "si el depósito está lleno, apaga la bomba").

![Icono Controles](../assets/icons/controls.png)

### Controles Simples (Simple Controls)
Acciones directas basadas en un solo disparador:
*   **Basados en Nivel/Presión**: Si el nudo X tiene < 10m, abrir válvula Y.
*   **Basados en Tiempo**: A las 08:00h, encender bomba Z.
*   **Basados en Reloj**: Todos los lunes a las 02:00h, cerrar tubería W.

### Reglas Complejas (Rules)
Permiten combinar múltiples condiciones mediante operadores lógicos:
*   **Operadores**: `IF`, `AND`, `OR`, `THEN`, `ELSE`, `PRIORITY`.
*   **Interfaz Interactiva**: A diferencia de EPANET clásico, en QGISRed construyes las reglas seleccionando elementos y operadores en menús desplegables, evitando errores de sintaxis en el archivo de texto.
*   **Habilitación**: Puedes desactivar reglas específicas sin borrarlas para probar diferentes escenarios operativos.
