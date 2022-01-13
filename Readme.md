________________________________________________________________________

#                   Curso Exploratorio de datos
________________________________________________________________________

Clase 2: Qué es el análisis exploratorio de datos

¿Qué es un EDA?

Significa Exploratory data analysis. Aquí comienza todo, antes de crear un modelo debemos saber para que lo vamos a hacer, debemos de tener contexto y la forma de hacerlo es exportando nuestros datos.

Un poco de historia:

En los años 90’s se comienza a sonar el termino de minería de datos donde se especifica que busca patrones, busca las tendencias más grandes y es justo la minería de datos es lo que le comienza a dar orden a cómo podemos explorar datos y a buscar estos patrones. Esto no es un termino que haya surgido actualmente, de hecho la IA, las primeras redes neuronales salen en los años 70, solo que actualmente ya tenemos el computo necesario para que tu lo puedas hacer de tu computadora, lo que antes solo se podía hacer en el mundo académico y era exclusivo de super maquinas.

Pero, todo esto, ¿de donde viene?

Justo en los años 90’s con la minería de datos se comienzan a crear metodologías, como estas:

    - KDD: Knowledge discovery in DataBases.

    - SEMMA: Sample, Explore, Modify, Model, and Assess.

    - CRISP-DM: Cross Industry Standard Process for Data Mining.

Y de estás metodologías de minería de datos sale nuestro EDA.

Todo esto surge a partir de una necesidad y nos comenzamos a hacer mucha preguntas, pero la pregunta final es: ¿Puedo contestar o no el requerimiento que me dieron con todos estos datos? Y si no tenemos los suficientes datos para resolver esta pregunta, eso es lo que hace precisamente el EDA, explicarnos si podemos contestar esta pregunta y si tenemos todo lo necesario para dar una respuesta.

¿Pero qué debemos de hacer si no podemos dar una respuesta? Tenemos que dar un paso atrás, debemos de pedir más datos.
Antes de hacer cualquier modelo de ML o DP debemos de entender:

De donde vienen los datos.
El contexto de los datos.
Por qué haremos el modelo.
Etapas del eda:

    Etapa 1: Definición del problema.
    Etapa 2: Preparación de datos.
    Etapa 3: Análisis de datos.
    Etapa 4: Desarrollo y representación de resultados.
    
    Nota:
    Si está en nuestra posibilidad usar toda la base de datos para entrenar nuestro modelo, hay que hacerlo. es mucho mejor pagar un poco para dar una propuesta de valor.

El foco principal del EDA es contar una historia prediciendo cuánto se va optimizar el problema implementando el modelo que vamos a proponer. Un científico de datos le da un valor a los datos.

_________________________________________________________________________________________________

Análisis Clásico: Parte del contexto de los datos para generar desarrollo y posterior análisis pero no se puede tener un dinamismo claro.

Análisis Bayesiano: Parte del contexto de datos a priori donde generaremos un modelo de probabilidad pero no tendremos una retroalimentacion para posterior actuar con esto.

EDA: Parte del contexto del negocio donde generamos un modelo donde se puede tomar un problema real del negocio, en el cual se puede actuar y retroalimentar para dar un mejor resultado


___________________________________________________________________________________________________

Herramientas de software para análisis exploratorio de datos

- Python-Jupyter:
    Se especializa en juntar texto con código y es el favorita de los científicos de datos.
    AWS SAGEMAKER: Está diseñada para el deploy de los modelos de Machine Learning. También tiene notebooks y este se utiliza más para probar modelos con bastante poder de computo, porque cobra a partir del tiempo que se emplea. Otra ventaja que tiene es que podemos llevar todo lo que hagamos a deploy como modelo de producción, osea, a que se haga una API.

- AWS EMR:
    EMR es casi lo mismo que Spark, ya que están diseñados para procesamiento de datos a grandes volúmenes tenido como base Hadoop. Es muy empleado para Data Engineer como preprocesamiento antes de un modelo o para modelos que requieren procesamiento en tiempo real. Si es que queremos que nuestro modelo sea en tiempo real, debemos de hablar con el Data Engineer para desde un inicio pedir este requerimiento.

- Google Jupyter Notebook Cloud:
    Es la forma de llevar nuestros notebooks a producción.
    Azure Notebooks: Azure apuesta que aquí solo se haga experimentación y que el deploy del modelo se haga en su plataforma.

- R Studio: 
    Este entorno tiene el Kernel de R y es un software especializado en estadística. Tiene muchas más bibliotecas de estadística que en el caso de Python, apenas están llegando.

- Knime: 
    Esta herramienta se enfoca para personas que no saben programar, es para personas que tiene conocimiento de negocio y no hay un experto que haga el flujo de trabajo del área de datos._________________________________________________________________________________________

            # Visualizacion de datos
    ________________________________________________________________________________________

    import altair as alt

    alt.Chart(df_zoo).mark_line().encode(
        x="animal name",
        y="legs"
        )

    alt.Chart(df_zoo).mark_line().encode(
        x="animal name",
        y="legs"
        )
    
    import plotly.express as px

_______________________________________________________________________________________

Transformar los datos

_______________________________________________________________________________________





        