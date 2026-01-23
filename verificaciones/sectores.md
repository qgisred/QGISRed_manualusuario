# Sectores Hidráulicos

Esta herramienta clasifica las subredes aisladas o conectadas en función de su capacidad de suministro y demanda. Es vital para identificar por qué una parte del modelo no recibe agua.

### Clasificación de Sectores
Para cada sector identificado, QGISRed lo clasifica en uno de estos 4 tipos:

| Tipo | Descripción | Estado de Suministro |
| :--- | :--- | :--- |
| **TIPO A** | Existe al menos una fuente (depósito/embalse) y hay nudos con demanda base. | ✅ **Funcional**: Los nudos pueden ser abastecidos. |
| **TIPO B** | Existe fuente de suministro, pero no hay ninguna demanda asignada en los nudos. | ⚠️ **Latente**: Capacidad instalada pero sin flujo. |
| **TIPO C** | **No existen fuentes de suministro**, pero hay demandas asignadas. | ❌ **Aislado Crítico**: No hay agua para satisfacer la demanda. |
| **TIPO D** | No existen fuentes de suministro y tampoco hay demandas asignadas. | ✅ **Pasivo**: Hidráulicamente compatible ya que no requiere flujo. |

### Utilidad del Análisis
Este diagnóstico preventivo permite detectar errores de conectividad antes de lanzar una simulación larga en EPANET, ahorrando tiempo en el diagnóstico de "Nudos Desconectados".
