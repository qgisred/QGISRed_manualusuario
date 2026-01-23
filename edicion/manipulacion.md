# Herramientas de Edición Avanzada

QGISRed ofrece herramientas precisas para manipular la geometría y el estado de tu red sin romper la topología.

### Manipulación Gráfica

#### Edición de Vértices
Permite ajustar el trazado real de tuberías y otros elementos lineales:
*   **Mover**: Arrastra cualquier vértice intermedio.
*   **Crear**: Haz clic en cualquier parte del tramo para añadir un punto de quiebre.
*   **Borrar**: Pulsa botón derecho sobre un vértice para eliminarlo.

#### Mover Nudos
Esta herramienta desplaza un nodo (Junction, Tank, Reservoir) y arrastra consigo todos los elementos conectados (tuberías, válvulas, bombas) manteniendo la red unida.

---

### Herramientas de Red (Net Tools)

| Herramienta | Acción |
| :--- | :--- |
| **Invertir** | Cambia la orientación de una línea (afecta al sentido del flujo positivo). |
| **Dividir/Unir Tubería** | Parte una tubería en dos o une dos tramos con idénticas propiedades (diámetro, material, edad). |
| **Dividir/Unir Nudo** | El proceso de unión es de dos en dos (origen -> destino). La división (botón derecho) separa las líneas conectadas en nudos individuales. |
| **Conexiones en T** | Crea o deshace uniones donde un nudo de conectividad 1 coincide sobre una tubería. |
| **Cruces de Tubería** | Fusiona o separa tuberías que se cruzan en el mapa. |
| **Desplazar Válvulas/Bombas** | Mueve un elemento de una tubería a otra manteniendo sus propiedades. |
| **Cambiar Estado** | Alterna el estado (Abierto/Cerrado) de tuberías y válvulas manuales. |

> [!NOTE]
> Si una tubería tiene una válvula manual, el cambio de estado debe realizarse sobre la válvula, no sobre la tubería.
