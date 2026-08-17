# telecom-analysis
Este proyecto analiza el comportamiento de los clientes de ConnectaTel para identificar segmentos y oportunidades de mejora en los planes.


🎯 Objetivos de aprendizaje del proyecto
Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
Documentar todo el proceso en un Jupyter Notebook, junto con un README reproducible para subirlo a GitHub.

Datasets del Proyecto
plans.csv: Catálogo de planes con sus precios y beneficios.
users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). 
usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud. 

Etapas del análisis realizadas
Paso	Acción	Resultado para el negocio
1. Cargar y explorar	Cargar y explorar plans, users_latam, usage.	Visión clara de la estructura y tipos de columna de cada dataset.
2. Identificación de problemas de calidad	Contar nulos, detectar sentinels, revisar fechas fuera de rango.	Lista priorizada de problemas que pueden sesgar decisiones.
3. Limpieza básica	Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.	Datos consistentes y listos para análisis estadístico.
4. Summary statistics	Revisar las medidas clave en variables categóricas y numéricas.	Medidas clave (media, mediana, percentiles) que muestran el comportamiento típico y extremo
5. Visualización & outliers	Creación de histogramas y boxplots.	Visualización de sesgos, patrones de usuarios o datos atípicos.
6. Segmentación	Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.	Segmentos accionables que permiten diseñar ofertas, campañas y migraciones de plan.
7. Insight ejecutivo	Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.	Responder a las preguntas del negocio y proponer acciones concretas.
8. Publicación	Subir tu notebook + README a GitHub.	Entrega reproducible para revisión y ejecución por stakeholder


Cómo ejecutar el notebook 













