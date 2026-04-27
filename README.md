EstadisticaComputacional

Descripción del Proyecto

Este repositorio contiene un cuaderno de Jupyter (Copia_de_Untitled4.ipynb) que explora conceptos fundamentales de la Estadística Computacional utilizando la librería pandas en Python. El proyecto se enfoca en el análisis de datos, la manipulación de DataFrames y Series, y la comprensión de cómo el tipo de dato y la indexación influyen en la eficiencia computacional. Se utiliza el entorno virtual de Google Colab para su ejecución.

Contenido del Cuaderno (Copia_de_Untitled4.ipynb)

El cuaderno aborda los siguientes temas y ejercicios:

Pregunta Uno: Análisis de Datos de Clientes

1.
Construcción de un DataFrame: Creación de un DataFrame de pandas a partir de listas de nombres, edades y montos de compra en CLP, asegurando tipos de datos correctos (dtype) e indexación personalizada (ID de cliente).

2.
Explicación:

•
Diferencia entre DataFrame y Series: Se discute la distinción entre estas dos estructuras de datos fundamentales de pandas.

•
Influencia del Tipo de Dato en la Eficiencia Computacional: Se analiza cómo los tipos de datos (int8, int32, int64, float, object) y la conversión a category pueden afectar la memoria y la velocidad de las operaciones.

•
Velocidad de Operaciones: Se examina el impacto de las operaciones numéricas, comparaciones, filtrado y manejo de valores nulos en el rendimiento.

•
Compatibilidad y Errores: Se abordan los problemas de operaciones inválidas y la importancia de la consistencia de tipos de datos.



Pregunta Dos: Manipulación de Datos de Ventas

1.
Creación de un DataFrame de Ventas: Generación de un DataFrame con al menos 20 registros, incluyendo columnas como Cliente, Producto, Monto y Fecha.

2.
Operaciones con el DataFrame:

•
Selección de registros donde el Monto sea mayor a 50000 y el Producto sea "Laptop".

•
Modificación del Monto en un 10% de aumento para los registros seleccionados.

•
Explicación de por qué loc es preferible frente a la indexación tradicional para evitar errores de copia, mejorar la claridad y mantener la consistencia.



Pregunta Tres: Análisis de Datos del World Happiness Report

1.
Extracción y Carga de Datos: Utilización del dataset "World Happiness Report" de Kaggle, que contiene información sobre los niveles de felicidad en más de 150 países.

2.
Análisis de Datos:

•
Diferencias conceptuales entre loc e iloc.

•
Riesgos de errores silenciosos en la indexación posicional.

•
Ejemplos de cómo extraer subconjuntos de datos y analizar dimensiones del dataset.



Cómo Ejecutar el Cuaderno

Para ejecutar este cuaderno, puedes utilizar Google Colab, que proporciona un entorno de ejecución de Python basado en la nube.

1.
Abre el siguiente enlace en tu navegador:
https://github.com/Garklc/EstadisticaComputacional/blob/main/Copia_de_Untitled4.ipynb

2.
Una vez en la página de GitHub, haz clic en el botón "Open in Colab" (si está disponible) o descarga el archivo .ipynb y súbelo manualmente a Google Colab.

3.
Ejecuta las celdas del cuaderno secuencialmente para replicar el análisis y los ejercicios.

Requisitos

•
Acceso a internet para Google Colab.

•
No se requiere instalación local de Python o librerías, ya que Google Colab proporciona el entorno necesario.

