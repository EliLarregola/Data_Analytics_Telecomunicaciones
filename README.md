# <p align=center>TELECOMUNICACIONES - Accesos a Internet</p>

![alt text](Imagenes/internett.jpg)

### Introducción

Dentro de las telecomunicaciones, se busca realizar un análisis de los accesos a servicios de Internet en Argentina según diversas variables.

El presente análisis busca reconocer el comportamiento de este sector a nivel nacional, y realizar diversas propuestas de mejoras.

### Descripción del Proyecto
El objetivo del proyecto es analizar los datos de accesos a internet en Argentina, identificar patrones y tendencias clave, y ofrecer recomendaciones basadas en los insights obtenidos.

Los datos fueron obtenidos de la página del **Ente Nacional de Comunicaciones (ENACOM)** de Argentina. La ENACOM es el organismo regulador de las telecomunicaciones en Argentina, responsable de la regulación y control de los servicios de comunicación en el país.
Se utiliza el archivo de Excel llamado "Internet" el cual contiene un total de 15 hojas.

De estas 15 hojas, se decide filtrar datos y trabajar con las hojas:

- Accesos por velocidad
- Accesos por tecnología
- Penetración - población
- Penetración - hogares
- Penetración - totales
- Ingresos

Esta decisión se toma a partir de que éstas hojas, en parte, resumen el contenido del resto. Luego de un análisis exploratorio de estas hojas, se proponen 3 KPI's para buscar mejoras.

### Tecnologías y Herramientas Utilizadas
- **Python** (pandas, matplotlib, seaborn): Utilizado para el análisis exploratorio de datos (EDA).
- **Power BI:** Utilizado para el diseño y desarrollo del dashboard interactivo.

### Metodología Aplicada

El paso a paso del EDA, análisis y KPI's se encuentran detallados en el informe del EDA.

#### Análisis Exploratorio de Datos (EDA):

Se realizó un EDA exhaustivo utilizando Python en un Jupyter Notebook, donde se limpiaron, exploraron y visualizaron los datos para identificar patrones y tendencias clave. 

1) **Importación y limpieza de datos:**
- Importación de los datos desde un archivo excel.
- Revisión y limpieza de los datos mediante un análisis preliminar.

2) **Análisis descriptivo:**
- Cálculo de estadísticas descriptivas para comprender mejor la distribución de los datos.
- Creación de visualizaciones iniciales para identificar patrones y tendencias generales.

3) **Visualización de datos:**
- Uso de bibliotecas como matplotlib y seaborn para crear gráficos que permitan visualizar las relaciones y tendencias en los datos.
- Visualización de los datos segmentados por diferentes variables como velocidad de internet, tipos de accesos y acesos cada 100 hogares.

4) **Identificación de KPIs:**

- Definición de indicadores clave de rendimiento **(KPIs)** relevantes para el análisis, como cantidad de accesos cada 100 hogares por provincias, cantidad de accesos al servicio de internet de velocidades entre "+ 20 Mbps - 30 Mbps" por provincias y fomentar el acceso a internet a través de tecnologías como fibra óptica.

#### Diseño del Dashboard:

1) **Importación de Datos:**

- Importación de los datos limpios y procesados desde archivos en formato Excel y CSV a Power BI.

2) **Desarrollo de Medidas y Transformaciones:**

- Si bien las medidas y cálculos se realizaron más precisamente en el informe de EDA, en el dashboard de busca proporcionar información detallada y precisa.
- Transformaciones de datos para agregar nuevas columnas calculadas que ayuden a segmentar y analizar los datos de manera más efectiva, así como tambien relacionar tablas.


3) **Creación de Visualizaciones:**

- Diseño de visualizaciones interactivas que permitieran a los usuarios explorar los datos de manera dinámica.
- Uso de gráficos de líneas, gráficos de barras, gráficos circulares y mapas para representar diferentes aspectos de la información.

4) **Configuración de Filtros:**

- Implementación de filtros para permitir a los usuarios ajustar la visualización de los datos según diferentes criterios.

5) **KPIs:**

- Representación de los indicadores clave de rendimiento (KPIs) utilizando medidores y tarjetas de varias filas.
- Medidores para mostrar el progreso hacia los objetivos definidos.
- Tarjetas de varias filas para presentar información detallada y resumida de los KPIs, facilitando la comprensión de los resultados.

6) **Interactividad y Navegabilidad:**

- Configuración de interacciones entre gráficos para mejorar la navegabilidad y facilitar la interpretación de los datos.
- Implementación de enlaces y botones de navegación dentro del dashboard para una experiencia de usuario más fluida.

### Conclusiones

A partir del análisis exploratorio de los dataframes elegidos se puede deducir que:

- Se observa el predominio de accesos entre dos rangos de velocidades de internet específicos: "+1 Mbps - + Mbps" y de "+ 30 Mbps". Estos accesos se concentran como es de esperarse en las provincias con mayor cantidad de habitantes como son: Buenos Aires, Córdoba y Santa Fe. 

A partir de esto se propone el siguiente KPI, para incrementar el uso de velocidades medias a altas pero tal vez más accesibles economicamente:

**Incrementar en un 2% los accesos totales al servicio de internet de velocidades entre "+ 20 Mbps - 30 Mbps" para el próximo trimestre por provincia**

Las propuestas de mejoras para lograrlo son:

- Garantizar buen funcionamiento para ese rango de velocidad de servicio en provincias como Buenos Aires, Córdoba y Santa Fe.
- Promociones de ingreso a nuevos clientes en dicho rango de velocidad.
- Priorizar el crecimiento de infraestructuras en provincias del interior y extremos del país.
- Incrementar publicidad y marketing.


En cuanto a tecnologías, se observa una clara preferencia por parte de las grandes provincias como Buenos Aires, Córdoba y Santa Fe por el "Cablemodem". Una propuesta podría ser mejorar la infraestructura para hacer llegar tecnologías alternativas tales como fibra óptica.

A partir de esto se propone el siguiente KPI:

**Incrementar en un 2% el acceso a internet por fibra óptica para el próximo trimestre por provincia.**

Las propuestas de mejora para lograrlo son:

- Inversiones de infraestructura para fibra óptica en provincias.
- Promociones de ingreso a nuevos clientes de fibra óptica.
- Priorizar el crecimiento de infraestructuras en provincias que no lo tienen. Dejando un poco de lado Buenos Aires, Córdoba y Santa Fe.
- En Buenos Aires, Córdoba y Santa Fé, incrementar publicidad y marketing.


Al comparar la penetración del servicio de internet por hogares y por población, se observa una predominancia tanto de acceso y de evolución al trabajar con hogares. Esto se puede observar en los diversos gráficos, pero a su vez se intuye que en general un hogar incluye más de una persona, por lo que se estaría accediendo a más habitantes. 

A partir de esto se propone el siguiente KPI:

**Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia**

Las propuestas de mejora para lograrlo son:

- Inversiones de infraestructura en provincias para mejorar tecnologías y velocidades.
- Promociones de ingreso a nuevos accesos.
- Marketing y publicidad.

### Datos de contacto

- [LinkedIn](www.linkedin.com/in/eliana-larregola)

- E-mail: eblarregola2012@gmail.com