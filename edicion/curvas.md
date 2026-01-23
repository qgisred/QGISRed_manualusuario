# Patrones y Curvas

Gestiona el comportamiento dinámico de demandas, bombas y tanques.

![Icono Curvas](../assets/icons/curves.png)

### Curvas de Modulación (Patterns)
Define cómo varía un parámetro (normalmente la demanda) a lo largo del tiempo.
*   **Tipos**: Volumen, tiempo o factores multiplicadores.
*   **Edición**: Puedes añadir factores uno a uno o importar series completas desde archivos CSV.
*   **Asociación**: En el nudo de demanda, asegúrate de poner el ID del patrón en el campo `IdPattern`.

### Curvas de Comportamiento (Curves)
Define la relación física entre dos variables.
*   **Bombas (Pump Curves)**: Relación entre Caudal (Flow) y Altura (Head). QGISRed permite definir curvas de 1 punto o 3 puntos, calculando la ecuación aproximada automáticamente.
*   **Depósitos (Efficiency/Volume Curves)**: Relación entre nivel y volumen para depósitos con formas irregulares.
