# Ferramentas para a impartición do módulo de Dixitalización aplicada aos sectores produtivos

## Datos e información

### Diferencia entre datos e información

En el contexto de la digitalización y las tecnologías de la información, es fundamental distinguir entre los conceptos de "dato" e "información".

Un **dato** es una representación simbólica, numérica, alfabética o de otro tipo de una entidad, fenómeno o hecho. Por sí solo, un dato carece de significado contextual. Por ejemplo, "23", "Rojo" o "Lunes" son datos que no tienen sentido hasta que se relacionan con un contexto específico.

La **información**, por otro lado, surge cuando los datos son organizados, interpretados y contextualizados para generar un conocimiento útil. Por ejemplo, "La temperatura actual es de 23°C" o "El semáforo está en rojo" son informaciones que derivan de datos y permiten tomar decisiones o comprender situaciones.

### Ciclo de vida de los datos

El ciclo de vida de los datos describe las distintas etapas que recorren los datos desde su generación hasta su eventual destrucción. Estas etapas son clave para una gestión eficiente y segura de los mismos:

1. **Creación o adquisición**: Los datos pueden ser generados por sensores, introducidos manualmente mediante formularios, capturados por dispositivos IoT o descargados desde bases de datos externas.

2. **Almacenamiento**: Los datos se guardan en estructuras como bases de datos relacionales, sistemas NoSQL, data lakes o en la nube, según sus características y volumen.

3. **Procesamiento**: Consiste en limpiar, transformar y preparar los datos para su análisis. Esto incluye la eliminación de errores, el tratamiento de valores nulos y la normalización.

4. **Análisis**: Una vez preparados, los datos se analizan para extraer patrones, correlaciones o predicciones. Esto se hace mediante herramientas estadísticas, de minería de datos o de inteligencia artificial.

5. **Visualización y difusión**: Los resultados se presentan en formatos comprensibles como gráficos, dashboards o informes.

6. **Archivado o eliminación**: Finalmente, según normativas como el RGPD, los datos deben ser archivados de forma segura o eliminados si ya no son necesarios.

### Gestión de datos

Una gestión adecuada de los datos implica asegurar su calidad, su accesibilidad y su protección a lo largo de todo su ciclo de vida. Algunos de los aspectos clave de la gestión de datos incluyen:

* **Calidad del dato**: Se refiere a la precisión, actualidad, completitud y coherencia de los datos. Datos incorrectos o duplicados pueden llevar a errores graves en la toma de decisiones.

* **Gobernanza de datos**: Son el conjunto de normas, políticas y responsabilidades para asegurar una gestión ética y eficiente. Incluye la definición de roles, responsabilidades y flujos de trabajo.

* **Metadata y trazabilidad**: La metadata describe el contenido, origen y uso de los datos. La trazabilidad permite seguir el rastro de los datos desde su origen hasta su uso final.

* **Herramientas**: Existen plataformas como Data Catalogs, sistemas de gestión de bases de datos (PostgreSQL, MongoDB), y herramientas de calidad de datos como Talend o OpenRefine.

### Big Data

El término "Big Data" se refiere al manejo de grandes volúmenes de datos que no pueden ser gestionados eficazmente con métodos tradicionales. Se caracteriza por las **5 Vs**:

* **Volumen**: Cantidades masivas de datos.
* **Velocidad**: Ritmo al que se generan y procesan.
* **Variedad**: Diversidad de formatos (texto, audio, vídeo, sensores, etc.).
* **Veracidad**: Calidad y fiabilidad de los datos.
* **Valor**: Potencial de transformar los datos en conocimiento útil.

En el ámbito industrial, el Big Data permite desde el análisis predictivo del mantenimiento de maquinaria hasta la optimización de procesos y la mejora de la trazabilidad.

Las herramientas más comunes incluyen Apache Hadoop, Spark y Kafka, que permiten el procesamiento distribuido y en tiempo real de grandes flujos de datos.

### Relación con IA, ML y DL

La Inteligencia Artificial (IA) y sus subcampos, el Aprendizaje Automático (Machine Learning - ML) y el Aprendizaje Profundo (Deep Learning - DL), se basan en datos para entrenar modelos capaces de tomar decisiones, reconocer patrones o automatizar tareas complejas.

* **ML** se utiliza para generar modelos a partir de conjuntos de datos estructurados, por ejemplo, para predecir el consumo de energía de una planta química.

* **DL** se usa cuando los datos son complejos y no estructurados, como imágenes de microscopía o señales acústicas. Se basa en redes neuronales profundas.

* La **IA** se nutre de datos, y cuanto más completos y fiables sean, mejores serán sus resultados. Por ello, la gestión de datos es clave para el éxito de cualquier sistema inteligente.

### Análisis de datos

El análisis de datos es el proceso mediante el cual se examinan los datos para descubrir información útil. Puede clasificarse en:

* **Descriptivo**: Resume los datos para entender qué ha pasado (por ejemplo, media mensual de producción).
* **Diagnóstico**: Analiza causas de ciertos resultados (por ejemplo, por qué bajó la productividad).
* **Predictivo**: Modela el comportamiento futuro (por ejemplo, previsión de demanda).
* **Prescriptivo**: Sugiere acciones óptimas (por ejemplo, ajustar tiempos de mantenimiento).

Herramientas utilizadas incluyen Excel con PowerQuery, Tableau, Power BI, Google Data Studio y, para usuarios más avanzados, Python con bibliotecas como Pandas y Matplotlib.

### Almacenamiento en la nube

El almacenamiento en la nube permite guardar datos en servidores remotos a los que se accede a través de internet. Se clasifica en:

* **Almacenamiento de objetos** (Amazon S3, Google Cloud Storage): Ideal para datos no estructurados.
* **Almacenamiento de archivos** (Dropbox, Google Drive): Pensado para compartir y colaborar.
* **Almacenamiento en bloque** (Azure Disks): Usado en entornos de alto rendimiento.

Ventajas: escalabilidad, acceso ubicuo, seguridad redundante. Desventajas: dependencia del proveedor, posibles problemas de latencia, coste a largo plazo.

### Ingeniería de datos: etapas

La ingeniería de datos se encarga de diseñar y mantener la infraestructura necesaria para el tratamiento de datos. Sus etapas típicas son:

1. **Recogida**: Captura desde sensores, APIs, formularios.
2. **Ingesta**: Carga de datos al sistema mediante procesos ETL (Extract, Transform, Load) o ELT.
3. **Almacenamiento**: Elección entre data lake, data warehouse, etc.
4. **Transformación**: Limpieza, integración, agregación.
5. **Exposición**: Visualización, dashboards, APIs de datos.
6. **Gobierno y calidad**: Supervisión de normas, auditorías, trazabilidad.

### Escenarios de aplicación

* **Industria química**: Control de calidad, optimización de reacciones, análisis de residuos.
* **Logística**: Trazabilidad de envíos, optimización de rutas.
* **Producción industrial**: Mantenimiento predictivo, eficiencia energética.
* **Educación**: Analítica del aprendizaje (Learning Analytics).

### Herramientas

* **Educativas**: CODAP, Tableau Public, Jupyter Notebooks, Google Colab.
* **Profesionales**: Apache Spark, Talend, Alteryx, Microsoft Azure Synapse.
* **Recursos para el aula**: Datos abiertos (INE, Eurostat, Data.gov), visualizadores online, simuladores de pipelines.

### Actividades recomendadas para el aula

* Análisis de datos reales del sector utilizando hojas de cálculo o BI.
* Interpretación de datos químicos (temperaturas, pH, concentraciones) a partir de sensores simulados.
* Creación de informes interactivos en Tableau Public.
* Simulación de un pipeline de datos desde un formulario a un gráfico.
* Reflexión grupal sobre privacidad de datos y protección legal.
