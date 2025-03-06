# Manipulacion-de-datos-Data-Wrangling-

### Descripción del Proyecto
Este proyecto consiste en el análisis de datos provenientes de la plataforma de entregas de comestibles Instacart. A través de técnicas de limpieza de datos, análisis exploratorio y visualización de resultados, el objetivo es extraer información valiosa sobre los hábitos de compra de los clientes. Este análisis permite identificar patrones de consumo y entender el comportamiento de la clientela, información clave para estrategias de negocio y optimización de operaciones.

Se trabajó con un conjunto de datos modificado del original publicado por Instacart para una competición de Kaggle en 2017. La versión utilizada incluye modificaciones como la introducción de valores ausentes y duplicados para simular situaciones reales en análisis de datos.

### Objetivo
El proyecto tiene como propósito:

Realizar un preprocesamiento exhaustivo del conjunto de datos: limpieza, identificación de valores duplicados y ausentes, y ajustes en los tipos de datos.

Crear visualizaciones informativas que comuniquen claramente los resultados obtenidos.

Proporcionar insights clave sobre los hábitos de compra, como los horarios y días preferidos para hacer pedidos, los productos más populares y el comportamiento de recompra.

Diccionario de Datos
El análisis abarca cinco tablas clave:

instacart_orders.csv: Información sobre pedidos realizados.

- order_id: Identificador único de cada pedido.
- user_id: Identificador único de cada cliente.
- order_number: Número de pedido realizado por el cliente.
- order_dow: Día de la semana del pedido (0: domingo).
- order_hour_of_day: Hora en la que se realizó el pedido.
- days_since_prior_order: Días desde el último pedido.

products.csv: Información de los productos.

- product_id: Identificador único del producto.
- product_name: Nombre del producto.
- aisle_id: ID de la categoría del pasillo.
- department_id: ID del departamento.
  
order_products.csv: Relación entre pedidos y productos.
- order_id: ID del pedido.
- product_id: ID del producto.
- add_to_cart_order: Orden en que el artículo fue añadido al carrito.
- reordered: 0 si es la primera vez que se pide, 1 si es un producto repetido.

aisles.csv: Información sobre categorías de pasillos.
- aisle_id: ID del pasillo.
- aisle: Nombre del pasillo.

departments.csv: Información sobre departamentos.
- department_id: ID del departamento.
- department: Nombre del departamento.

### Metodología
Etapa 1: Exploración de los Datos
Revisar los archivos de datos para comprender su estructura y contenido.

Configurar correctamente pd.read_csv() para procesar los archivos con formato no estándar.

Etapa 2: Preprocesamiento
Corrección de tipos de datos y manejo de valores ausentes y duplicados.

Justificación de los métodos empleados para tratar inconsistencias en los datos.

Etapa 3: Análisis Exploratorio
Verificar rangos y consistencia en las columnas de tiempo (order_hour_of_day, order_dow).

Analizar patrones de pedidos según hora y día de la semana.

Identificar productos más comprados y su comportamiento de recompra.

### Conclusiones 
Personalmente este proyecto me ha parecido muy retador e interesante, una de las cosas que más puedo destacar es la en esta ocasión no se proporcionó toda la información como se hizo en los proyectos anteriores, 
lo cual me parece es una buena práctica para los estudiantes, pues en ocasiones en caso reales se debe aprender a solucionar este tipo de problemas aun cuando no se tiene clara la información. 
También puedo destacar que se me hizo difícil seleccionar las herramientas adecuadas para resolver algunos de los casos de este proyecto, 
sin embargo espero tener correcciones para saber en qué estoy fallando y encaminarme a mejorar en mis áreas de oportunidad. 

