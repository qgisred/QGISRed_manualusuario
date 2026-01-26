# Análisis de Atributos del Modelo

QGISRed permite auditar de forma masiva los datos introducidos en los elementos para detectar inconsistencias lógicas.

### Auditoría de Datos
*   **Análisis de Longitudes**: Compara la longitud asignada en la tabla de atributos (L) con la longitud geométrica calculada (Euclídea). Si la diferencia supera el porcentaje definido por el usuario, el plugin emite un aviso. Permite la actualización masiva del valor L con el dato geométrico.
*   **Análisis de Diámetros**: Identifica tuberías cuyos diámetros se salgan de los umbrales (mínimo/máximo) preestablecidos, ayudando a detectar errores de transcripción.
*   **Análisis de Materiales**: Busca materiales que no estén definidos en la tabla oficial de materiales del proyecto o que aparezcan como "UNKNOWN".
*   **Análisis de Fechas**: Detecta fechas de instalación incorrectas, mal formateadas o que apunten al futuro.

---
> 💡 **NOTA**:
> Estas verificaciones son esenciales antes de proceder con el cálculo de rugosidades basado en la edad, ya que dependen directamente de la precisión del material y la fecha de instalación.
