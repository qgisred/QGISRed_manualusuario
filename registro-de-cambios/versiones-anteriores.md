# Versiones anteriores

### Versión 0.14

_Versiones de QGis_: 3.2-3.99

_Características_:

* Corregido error grave al leer los metadatos de modelos anteriores, que impedía trabajar con ellos

\-          Corregido error al instalar el plugin sin disponer previamente de las dependencias necesarias

\-          Corregido un error con el formato de la hora en las leyes de control simples

\-          Visualización del separador decimal definido por el usuario en las diferentes ventanas del plugin

\-          Nueva herramienta para editar la geometría de las acometidas

\-          La opción hidráulica _demand multiplier_ admite ahora un valor con decimales

\-          Prioridad de los elementos del GD a la hora de seleccionar los objetos para editar sus propiedades o borrarlos

### Versión 0.13

_Versiones de QGis_: 3.2-3.99

_Características_:

\-          Nuevo menú para agrupar las herramientas destinadas al manejo de los Gemelos Digitales

\-          Creación de acometidas a través de una herramienta propia, e incorporación de las mismas a la herramienta de borrado

\-          Ficha específica para editar las propiedades de las acometidas

\-          Carga de las lecturas automáticas de contador (telelectura) bajo diferentes formatos, a las acometidas o nudos del modelo

\-          Incorporación de las curvas de modulación de las demandas en las acometidas al editor de curvas de modulación

\-          Nuevo gestor de demandas para completar la importación desde fichero, con la exportación a fichero y borrado selectivo de las demandas base en los nudos y sus curvas de modulación

\-          Mejora de los tiempos de acceso a la ventana de edición de propiedades de los elementos, para redes de gran tamaño

\-          La apertura desde el entorno de EPANET del fichero INP al exportarlo es ahora optativa

\-          Nuevas opciones para definir las unidades y la fórmula de pérdida de carga al importar datos desde GIS

\-          El conversor de los coeficientes de pérdidas al cambiar de fórmula comprueba antes que existan tuberías declaradas

\-          Corregido el formato de las opciones de tiempo para permitir introducir días, además de horas, minutos y segundos

\-          La eliminación de las curvas de modulación en demandas múltiples se limita ahora exclusivamente a las demandas eliminadas

\-          Corregida la lectura de fechas en los metadatos

\-          Corregido el error que impedía importar SHPs al seleccionar el mismo campo para distintas propiedades

\-          Corregido el error por el cual se importaban algunos campos de los SHPs sin haberlos seleccionado expresamente

\-          Traducción al inglés de algunos textos que se mostraban solo en español

\-          Corregido el fallo de las herramientas de selección gráfica cuando el CRS de QGIS es diferente al de los datos de QGISRed

\-          Corregido el error de importación de SHPs cuando alguna _feature_ no tiene su geometría declarada

\-          Corregido un error de visualización en las capas de resultados

### Versión 0.12

_Versiones de QGis_: 3.14-3.99

_Características_:

\-          Edición de la tabla de materiales-rugosidad para el cálculo de la rugosidad en función de material y edad

\-          Nueva importación y exportación de patrones/curvas en formato CSV

\-          Nueva herramienta para importar las demandas base en los nudos y los Ids de las curvas de modulación (simples o múltiples) desde un fichero CSV

\-          Importación de acometidas desde SHP

\-          Nueva herramienta para obtener el árbol de mínima resistencia de la red

\-          Actualización de la librería de Epanet a la versión 2.2

\-          Mejorada la interfaz para convertir los coeficientes de rugosidad

\-          Corrección de un error al mostrar resultados de Calidad

\-          Refresco de las unidades y la fórmula de pérdidas actuales en la barra de estado, al cargar un proyecto QGis

\-          Los proyectos importados desde INP se muestran ahora en la lista de proyectos

\-          Corrección de un error cuando los nudos no tienen coordenadas

\-          Al insertar válvulas o bombas en tuberías, se evita ahora la aparición de longitudes negativas

\-          Corrección de un error de acceso a la edición de Patrones cuando el Pattern TimeStep es 0:00

\-          Las acometidas se leen ahora correctamente

### Versión 0.11

_Versiones de QGis_: 3.2-3.99

_Características_:

\-          Creación de un archivo Json para definir las diferentes proyecciones (contenido del .prj) en el caso de no disponer de Internet

\-          Implementada la lectura de los formatos de la sección PUMPS heredados de la versión 1.1 de Epanet

\-          Nuevo instalador único para ambas arquitecturas (x86 y x64)

\-          Se muestran las unidades y la fórmula de pérdida de carga en la barra de estado.

\-          La estimación del coeficiente de rugosidad en función de la edad y el material admite diferentes fórmulas de pérdida de carga y sistema de unidades

\-          Conversión de coeficientes de rugosidad entre diferentes fórmulas de pérdida de carga

\-          Herramienta para crear una copia de seguridad del proyecto (restauración manual)

\-          Corregido el error al cargar el plugin en la versión de QGis 3.14.15

\-          Corregido un error por no permitir expresar las horas en formato distinto a AM/PM en la sección Controls

\-          Corregido un error al no poder acceder a la información del usuario de Windows en determinados ordenadores

\-          Nuevo color azul en las etiquetas para los resultados de tipo línea

\-          Corregido el error al clonar el proyecto y perder los metadatos

\-          Corregido el error al guardar un escenario de resultados y quedarse congelado el mapa

\-          Nuevo orden alfabético en las listas de links y nodes en los Controles Simples

### Versión 0.10

_Versiones de QGis_: 3.0-3.14.1

_Características_:

\-          Corregido mal funcionamiento al crear/importar cuando hay otras cosas abiertas.

\-          Escritura de las cabeceras de las secciones del INP en inglés.

\-          Validación en las propiedades de los elementos para impedir mismo nudo final en líneas.

\-          Corregido error al importar depósitos.

\-          Mejora de la simplificación de vértices para eliminar los repetidos en el punto inicial.

\-          Corregido error al escribir los Times de Options.

\-          Restructuración de metadatos, ahora unificado en el archivo \*\_Metadata.txt.

\-          Corregido error al juntar tuberías de características iguales cuando empieza y acaba en el mismo nudo.

\-          Comprueba si hay versiones nuevas y avisa al usuario.

\-          Corregida visualización de iconos en la leyenda para versión 3.12 de QGis

\-          Corregido error que impedía guardar los estilos de resultados.

\-          Corregido error en lectura de símbolo decimal cuando el usuario usa el formato inglés y cambia el símbolo decimal por coma.

\-          EditProject cambia a LayerManagement para controlar visibilidad de capas y su creación.

\-          Ahora la proyección se guarda correctamente en el archivo PRJ.

\-          Nueva ventana con opciones del proyecto.

\-          Separación entre Importar (sin proyecto - INP o SHPs) y Añadir (con proyecto - solo SHPs).

\-          Tolerancia espacial al importar/añadir datos desde SHPs.

\-          Manual incluye formato del archivo ascii para interpolación de cotas y clasificación de los 4 tipos de sectores hidráulicos.

\-          Simplificadas 4 capas de medidores en 1 sola.

\-          Corregido error al escribir SHPs de incidencias en válvulas y bombas.

\-          Métodos para asignar rugosidad, chequear elementos superpuestos, vértices alineados, longitudes, material, diámetro o fecha de instalación ahora también para elementos seleccionados.

\-          Corregido error en caso muy específico al crear conexiones en T de forma individual.

\-          Nueva gestión de dependencias para evitar errores si están en uso.

\-          Diversas mejoras sobre las prestaciones ya ofrecidas en versiones anteriores

### Versión 0.9

_Versiones de QGis_: 3.0-3.99

_Características_:

\-          Un nuevo logo para el plugin QGISRed

\-          Creación ágil de tuberías, depósitos y embalses con herramientas propias, y opciones de anclaje a los elementos ya existentes

\-          Herramienta para editar el trazado de los elementos lineales, incluyendo creación (clic sobre el trazado), desplazamiento y borrado (botón derecho) de vértices

\-          Orientación por defecto de válvulas/bombas al insertarlas en una tubería, siguiendo el trazado de ésta

\-          Herramienta para invertir la orientación de los elementos lineales (tuberías, válvulas y bombas)

\-          Herramienta para partir y unir tuberías

\-          Herramientas para separar/unir nudos

\-          Herramienta para crear/deshacer conexiones en T

\-          Herramientas para crear/deshacer cruces de tuberías

\-          Herramienta para mover de posición válvulas y bombas

\-          Selección múltiple de elementos de diferentes capas (Ctrl añade y Shift elimina)

\-          Borrado de todos los elementos seleccionados dentro de una región poligonal

\-          Eliminación de la mayor parte de los botones dobles y sustitución por una opción en la ventana de diálogo.

\-          Nuevo icono para acceder a los últimos resultados sin simular de nuevo

\-          Posibilidad de expandir y comprimir el menú de resultados para permitir el acoplamiento de otras ventanas de QGis

\-          Corrección de un error al trabajar con rutas de ficheros largas

\-          Diversas mejoras sobre las prestaciones ya ofrecidas en versiones anteriores

### Versión 0.8

_Versiones de QGis_: 3.0-3.99

_Características_:

\-          Edición de propiedades de los elementos principales a través de una ventana de diálogo, pudiendo navegar desde ella a través de los diferentes elementos del mismo tipo que contiene el modelo.

\-          Inserción/Eliminación de válvulas y bombas en tuberías. En el primer caso clicando en un punto de la tubería, ésta se dividirá o se acortará (según el caso) para introducir el nuevo elemento. En el segundo caso, clicando sobre el elemento válvula o bomba, éste se eliminará juntando las tuberías colindantes si es posible.

\-          Edición del trazado de la red, pudiendo mover nudos del modelo de modo que el resto de los elementos que coincidan espacialmente con éstos, se desplacen a la misma posición.

\-          Reorganización de todos los botones del plugin agrupándolos en 5 categorías para facilitar el manejo de las diferentes opciones.

\-          Corrección de errores en la lectura de algunas leyes de control.

\-          Diálogos para la edición de las opciones de cálculo y los valores por defecto.

\-          Verificación de Ids repetidos durante la generación de los mismos.

\-          Ocultación de las tablas de datos de la leyenda (Patterns, Curves, Controls, Rules, Options y DefaultValues).

\-          Cambios en el menú de selección de resultados para mostrar una única variable por nudo o por línea. Reducción del tiempo de refresco.

\-          Opción para visualizar mediante etiquetas fijas el valor del parámetro elegido para cada elemento.

\-          Eliminación de los permisos de administrador para instalar las dependencias necesarias.

\-          Algunas mejoras sobre las prestaciones ya ofrecidas en versiones anteriores.

### Versión 0.7

_Versiones de QGis_: 3.0-3.99

_Características_:

\-          Tabla resumen con el número de elementos de cada tipo, así como las unidades de caudal, la fórmula de pérdidas de carga y si se modela algún parámetro de calidad.

\-          Gestor de Curvas de modulación: Permite editar, crear, borrar, clonar, exportar e importar nuevas curvas de modulación (o Patterns). Añade la opción de definir el tipo de curva de modulación. También se indica qué elementos están asociados a esa curva. Por último, se incluye la funcionalidad de trabajar con valores reales (en función del valor base asociado a la curva) o con un multiplicador o factor (forma tradicional).

\-          Gestor de Curvas de comportamiento: Permite editar, crear, borrar, clonar, exportar e importar nuevas curvas de comportamiento. Para las curvas asociadas a bombas, en el caso de 1 o 3 puntos se especifica la ecuación de la curva aproximada. También se especifica los elementos asociados a dichas curvas.

\-          Gestor de Controles Simples: Permite editar, añadir, borrar, clonar y ordenar leyes de control simple.  Incluye la opción de poder deshabilitar una ley de control.

\-          Gestor de Rules: Permite editar, añadir, borrar, clonar y ordenar Rules.  Incluye la opción de poder deshabilitar una Rule. Se permiten combinar diferentes condiciones a través de los operadores OR y AND, así como seleccionar la condición combinada apropiada para aplicar a la Rule.

\-          Tanto en el gestor de controles simples como en el de Rules su definición se realiza de forma interactiva y no escribiendo texto (modo tradicional).

### Versión 0.6

_Versiones de QGis_: 2.0-3.99

_Características_:

\-          Gestionar los proyectos de QGISRed. Es posible abrir, crear, importar, clonar o borrar proyectos.

\-          Crear o editar un proyecto de QGISRed. Permite crear las capas vectoriales (SHPs) de los elementos básicos con los que trabaja el software EPANET. Si el usuario elimina alguno de estos SHPs, es posible volver a crearlos.

\-          Importación de datos desde ficheros INP (EPANET) o SHPs. En el primer formato se pueden importar modelos completos desarrollados con el popular software EPANET. Mediante SHPs se puede crear o completar un modelo especificando para cada tipo de elemento principal, el SHP del que se desea importar información y qué campos contienen determinada información necesaria para el modelo.

\-          Validación del modelo, informando de si se ha producido algún tipo de error o aviso al procesar la información contenida en los SHPs.

\-          Exportación al fichero INP de EPANET, con la opción de abrir este software una vez generado el fichero.

\-          Simulación con la Toolkit de EPANET para mostrar los resultados hidráulicos y de calidad.

Dispone de un conjunto de herramientas asociadas al trazado (eliminación de elementos superpuestos, simplificación de vértices alineados, creación de conexiones tipo T, fusión de tuberías con las mismas características o análisis de la conectividad de la red), a las propiedades de los elementos (análisis de longitudes, diámetros, materiales, fechas de instalación, cambio de estado de tuberías o interpolación de cotas), para añadir componentes (acometidas, hidrantes, desagües) o para sectorizar (sectores hidráulicos y sectores de demandas).
