# Reto: Movilidad Urbana
El presente proyecto busca estimar los Viajes Origen-Destino del 30% de la población de la Región Metropolitana de Chile  mediante el uso de información de movilidad, almacenada por Movistar Chile, posibles de procesar para convertirlos en información de movilidad de personas. Todo lo anterior bajo los estándares de completo anonimato y sin entrega de datos personales de los usuarios de los terminales celulares, y de aquella forma, en consistencia con la normativa vigente sobre uso de datos personales y protección de la vida privada de las personas.

# ¿Que se encuentra dentro del repositorio?
Dentro de la carpeta de documentación se encuentran archivos generales sobre el proyecto y la división del proyecto en carpetas por las distintas etapas de CRISP-DM. Por otra parte, en la carpeta de código fuente se encuentra todo el código realizado durante las distintas etapas del proyecto.

# ¿Cuál fue el proceso que se siguió?
Como se puede observar en el siguiente diagrama, hasta el momento se han realizado 4 etapas de preparación de datos. Cada una de estas etapas aporta mejoras al dataset de entrenamiento, lo cual nos permite obtener modelos cada vez mejores. 
Para conocer a detalle sobre los cambios que implica cada etapa de data preparation, favor de revisar la documentación de preparación de datos.

![modelos](https://user-images.githubusercontent.com/46075159/203157828-f19e6e1c-5730-421e-91ab-c054c87de291.png)


# Cúal es el contenido de cada carpeta

## Documentación

### Business understanding
Definición de los objetivos del proyecto e identificación los requerimientos desde una perspectiva de negocio, converción de este conocimiento en un problema de minería de datos y el diseño de un plan para lograr los objetivos

### Data undestanding
Visualización de los datos y descubrimiento de hallazgos

### Data preparation
Los pasos que se siguieron para la construcción de los dataset para el entrenamiento de los modelos, asi como su codificación.

### Modeling
En este se encuentra la codifición de cada uno de los modelos, la justificación de la selección de cada uno de ellos al igual que sus evaluaciones

### Evaluation
La validación del modelado con mejores resultados en la parte de modelado, en base a los requisitos de negocio.

## Código Fuente

### Data Preparation
Aquí se encontrarán distintas subcarpetas que engloban el código fuente requerido para cada una de las preparaciones de datos que se realizaron. 

### Modelado
Aquí se encuentra el código fuente de cada uno de los distintos modelos realizados.
