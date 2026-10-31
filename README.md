Análisis exploratorio de las PQRDS del Ministerio de Agricultura y Desarrollo Rural
Patrones territoriales y operativos asociados a los tiempos de respuesta

Proyecto académico de la Especialización en Analítica de Datos, orientado a estudiar las Peticiones, Quejas, Reclamos, Denuncias y Sugerencias (PQRDS) registradas por el Ministerio de Agricultura y Desarrollo Rural (MADR) de Colombia durante la vigencia 2025.
Equipo investigador
- Stefany Albarracín Borda
- Diego Fernando Munar Forigua
- Jhonnatan Javier Rodríguez Sichaca
Descripción del proyecto
La gestión de PQRDS es un mecanismo fundamental de interacción entre la ciudadanía y las entidades públicas. Este proyecto propone aplicar técnicas de análisis exploratorio de datos (EDA) para caracterizar la distribución territorial de las solicitudes, examinar la carga operativa de las dependencias responsables e identificar patrones asociados con los tiempos de respuesta y el cumplimiento de los términos legales.

El estudio se enmarca en el derecho de petición regulado por la Ley 1755 de 2015 y busca aportar evidencia para mejorar la oportunidad y el seguimiento de la atención ciudadana.
Pregunta de investigación
¿De qué manera la distribución territorial y por dependencia de las PQRDS del Ministerio de Agricultura y Desarrollo Rural incide en los tiempos de respuesta y el cumplimiento de los términos legales establecidos en la Ley 1755 de 2015?

Objetivo general
Analizar la distribución de las PQRDS del Ministerio de Agricultura y Desarrollo Rural según la dependencia responsable y la ubicación geográfica de origen, mediante técnicas de análisis exploratorio de datos, con el fin de identificar patrones en los tiempos de respuesta y la calidad de la gestión del servicio que permitan generar recomendaciones estratégicas basadas en evidencia para el mejoramiento de la atención ciudadana en el territorio nacional.
Objetivos específicos
1. Describir la distribución territorial, las tipologías más frecuentes y las variaciones temporales de las PQRDS.
2. Examinar la carga operativa, los tipos de requerimientos y los tiempos de gestión por dependencia.
3. Analizar el cruce entre territorio de origen y dependencia responsable para detectar patrones y posibles brechas de atención.
4. Evaluar el cumplimiento de los términos legales de respuesta y reconocer los segmentos con mayores rezagos.
5. Proponer recomendaciones basadas en evidencia e indicadores clave de desempeño para fortalecer la gestión institucional.
Alcance y metodología
- Período de estudio: 1 de enero al 31 de diciembre de 2025.
- Enfoque: cuantitativo.
- Alcance: descriptivo y exploratorio.
- Diseño: no experimental, transversal.
- Unidad de análisis: registro administrativo de PQRDS.
- Cobertura: censo de las PQRDS de 2025 disponibles para el estudio, sin selección muestral.
- Técnicas previstas: limpieza y normalización, estadística descriptiva, análisis cruzado de variables, visualizaciones, mapas temáticos e indicadores de desempeño.
El proyecto no contempla modelos predictivos ni inferencias causales avanzadas. Las asociaciones encontradas mediante EDA no se interpretarán automáticamente como relaciones de causa y efecto.
Etapas de trabajo
1. Obtención y verificación de integridad de los datos.
2. Preparación, depuración y estandarización de variables.
3. Análisis descriptivo de solicitudes, territorios, tipologías y dependencias.
4. Análisis cruzado de tiempos de respuesta y cumplimiento legal.
5. Visualización mediante gráficos, mapas e indicadores.
6. Formulación de recomendaciones e informe final.
Cifras de referencia del anteproyecto
El documento académico reporta para 2025:
Indicador	Valor reportado
Comunicaciones externas	33.842
PQRDS identificadas	7.456
Otras comunicaciones	26.386
PQRDS atendidas oportunamente	3.096 (41,5 %)
PQRDS respondidas fuera de término	2.754 (36,9 %)
PQRDS vencidas sin atención	1.285 (17,2 %)


Nota de validación: las tres categorías de oportunidad suman 7.135 registros, es decir, 321 menos que las 7.456 PQRDS reportadas. Antes de publicar indicadores definitivos se verificará la clasificación o el estado de esos registros. Estas cifras provienen del anteproyecto y no representan resultados reproducidos todavía por los cuadernos de análisis del repositorio.
Herramientas previstas
- Microsoft Excel: revisión preliminar y validación inicial.
- Python: limpieza, transformación y análisis exploratorio de datos.
- Power BI: construcción de tableros, indicadores y visualizaciones.
Las dependencias de Python del proyecto se documentarán en [`requirements.txt`](requirements.txt).
Estructura del repositorio
.
├── data/
│   ├── raw/                 # Datos originales (según permisos de acceso)
│   └── processed/           # Datos depurados para análisis
├── models/
│   └── model_card.md        # Documentación de modelos, si aplica
├── notebooks/               # Cuadernos de exploración y análisis
├── results/
│   ├── figures/             # Gráficos y mapas generados
│   ├── tables/              # Tablas e indicadores exportados
│   └── experiments.csv      # Registro de experimentos o ejecuciones
├── LICENSE
├── README.md
└── requirements.txt
Las carpetas y archivos indicados reflejan la estructura inicial del repositorio; su existencia no implica que ya contengan análisis, datos o resultados finales. Aunque existe una carpeta models/, el alcance declarado del anteproyecto es exploratorio y no exige entrenar modelos predictivos.
Ejecución del proyecto
Cuando se incorporen los cuadernos de análisis y se completen las dependencias:
# Clonar el repositorio usando su URL de GitHub
# git clone <URL_DEL_REPOSITORIO>
# cd <NOMBRE_DEL_REPOSITORIO>

python -m venv .venv
# En Windows:
# .venv\Scripts\activate
# En macOS o Linux:
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
Importante: estos son pasos orientativos. Antes de ejecutarlos debe verificarse que requirements.txt incluya las dependencias necesarias y que los cuadernos hayan sido añadidos a notebooks/.

Privacidad y uso de datos
El análisis debe respetar la Ley 1581 de 2012 sobre protección de datos personales. No se publicarán datos que permitan identificar a los peticionarios. El acceso y la difusión de bases institucionales dependerán de las autorizaciones correspondientes; en su lugar podrán compartirse resultados agregados y materiales reproducibles que no expongan información sensible.
Productos esperados
- Informe analítico con hallazgos del EDA.
- Visualizaciones territoriales y por dependencia.
- Indicadores de oportunidad y cumplimiento de términos legales.
- Recomendaciones para fortalecer el monitoreo y la gestión de PQRDS.
Referentes normativos principales
- Constitución Política de Colombia, artículo 23.
- Ley 1755 de 2015: regulación del derecho fundamental de petición.
- Ley 1581 de 2012: protección de datos personales.
- Ley 1712 de 2014: transparencia y acceso a la información pública.
Estado del proyecto
En preparación. El anteproyecto establece el diseño metodológico y presenta cifras institucionales de referencia. La incorporación de datos autorizados, los cuadernos de análisis y la validación de resultados se documentarán conforme avance la investigación.
