# Creación de Elementos

Usa la barra de herramientas de QGISRed para construir tu red. Los botones están diseñados para automatizar la topología.

![Barra de Herramientas](../assets/images/image70.png)

### Mecánica de Construcción

#### 1. Tuberías (Pipes) ![Icono Pipe](../assets/icons/pipe.png)
*   **Creación**: Haz clic para establecer el punto inicial y final. Automáticamente se generarán dos nudos extremos (tipo *Junctions*).
*   **Propiedades**: Al crear una tubería, se le asignan automáticamente los valores por defecto del proyecto.

#### 2. Depósitos y Embalses (Tanks / Reservoirs) ![Icono Tank](../assets/icons/tank.png) ![Icono Reservoir](../assets/icons/reservoir.png)
*   **Requisito**: Debes pulsar sobre un nudo (Junction) ya existente. QGISRed no permite crear nudos aislados de este tipo; siempre deben estar vinculados a la red.

#### 3. Válvulas y Bombas ![Icono Valve](../assets/icons/valve.png) ![Icono Pump](../assets/icons/pump.png)
*   **Inserción en línea**: Selecciona la herramienta y haz clic sobre una tubería existente. 
*   **División inteligente**: El plugin dividirá la tubería original en dos tramos o la acortará para insertar el nuevo elemento manteniendo la conectividad.

---
> ❗ **IMPORTANTE**:
> A diferencia de otros editores de EPANET, en QGISRed **no necesitas definir manualmente los IDs de nudos iniciales y finales**. El plugin utiliza análisis espacial para conectar las líneas y nudos automáticamente.
