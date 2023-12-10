<h1 align="center"> LGTB+ Trabajo y violencia con Ciencia de datos </h1>


## :hammer:Funcionalidades del proyecto 
- `Funcionalidad 1`: Tomar en cuenta de que forma va la sociedad - `Funcionalidad 2`: Consientizar y abordar los problemas de la violencia - `Funcionalidad 2a`: Empatizar a la empresas sobre el respeto y las mismas oportunidades para todos 
# Introducción 
La comunidad LGTB+ ha sido objeto de amplio estudio debido a las anomalías detectadas en su interacción con la sociedad. 
Una de las problemáticas más recurrentes es la violencia dirigida hacia estas personas, y mediante el análisis de datos, podemos anticipar o estimar posibles 
aumentos en este fenómeno en el futuro. A través de la recopilación de información proveniente de asociaciones tanto privadas como públicas, 
he construido un conjunto de datos basado en probabilidades y porcentajes, que se erige como una representación muestral de las experiencias de estas personas 
a través de encuestas.



# Desarrollo 
En esta investigación, emplearemos la ciencia de datos para implementar cadenas de Markov y desarrollar modelos de inteligencia artificial con el propósito de 
prever tanto la inserción laboral como la incidencia de violencia dentro de la comunidad LGTB+

## Cadenas de Markov 
Preparación de datos:

Si la "Necesidad de Trabajo" es una variable binaria (0 o 1), entonces puedemos usarla como tu estado.
Codifica las variables categóricas (como "Nivel Educativo" y "Área de Formación") en números para que puedas incluirlas en el modelo. 

Definir los estados:
Definimos los estados. tendríamos dos estados: "No necesita trabajo" (0) y "Necesita trabajo" (1). Modelar transiciones:
Para modelar las transiciones entre estados, necesitamos calcular las probabilidades de transición. observando cuántas veces ocurren las transiciones 
de un estado a otro en los datos. Por ejemplo, cuántas veces una persona cambia de "No necesita trabajo" a "Necesita trabajo" y viceversa. 
Estimar probabilidades de transición:
Calcula las probabilidades de transición entre los estados.
Utilizar la matriz de transición y el estado actual para calcular la probabilidad del siguiente estado. Evaluar el modelo:
Evalúamos la calidad del modelo de cadena de Markov utilizando medidas como la matriz de confusión, precisión, sensibilidad y especificidad.

- Predicción del estado en 3 pasos: [0.63418791 0.36581209]," representa la predicción de la distribución de probabilidades de los estados después de 3 pasos en la cadena de Markov, partiendo de un estado inicial donde la probabilidad de estar en "No necesita trabajo" es aproximadamente 0.6342 y la probabilidad de estar en "Necesita trabajo" es aproximadamente 0.3658.

- En otras palabras, después de 3 pasos en la cadena de Markov, la predicción indica que la probabilidad de estar en el estado "No necesita trabajo" es del 63.42%, mientras que la probabilidad de estar en el estado "Necesita trabajo" es del 36.58%. Estos valores representan la distribución de probabilidades de los estados en ese punto en el tiempo. La predicción se basa en las probabilidades de transición entre estados en la matriz de transición y el estado inicial.


# IA  

Para este modelo de inteligencia artificial utilizamos Tensorflow con Keras para pdoer predecir la obtención de trabajo, claro esta que se pueden usar otros modelos. 
Opte por este tipo de modelo para mi clase de IA y asi tener un 2x1, jaja. Bueno utilizamos Keras y fueron 3 pasos o 3 secciones para mejorar la presicón del modelo. 
Recomiendo utilizar el modelo de Spark que he subi igualmente ya que es mas adecuado apra estos casos. 

# En Spark 

Utilice Apache Spark para adentrarme al mundo del big data de manera práctica y así aprender como esque actuan los modelos en situaciónes así. Obteniendo una presicón del 98% en las
predicciones sobre la necesidad o obtención de trabajo, se recomienda lo siguiente: 

Conclusiones campañas sobre el modelo 
### Programas de Empleo y Capacitación:

- Diseña programas de empleo y capacitación específicamente dirigidos a personas de la comunidad LGTB. Estos programas podrían incluir talleres de habilidades laborales, asesoramiento profesional y conexiones con empleadores inclusivos.
Campañas de Concientización en Empresas:

- Recomendación para empresas en colaboración con otras empresas para promover entornos de trabajo inclusivos y sin discriminación. Realiza campañas de concientización para sensibilizar a los empleadores sobre la importancia de la diversidad y la inclusión en el lugar de trabajo.

### Plataformas de Empleo Específicas:

- Crea o promociona plataformas de empleo específicas para la comunidad LGTB. Estas plataformas podrían conectar a empleadores comprometidos con la inclusión con candidatos de la comunidad.
Campañas de Empoderamiento:

- Lanza campañas que empoderen a individuos de la comunidad LGTB, brindándoles recursos y apoyo para buscar y mantener empleo. Esto podría incluir sesiones de mentoría, eventos de networking y recursos de desarrollo profesional.

### Recursos de Salud Mental y Bienestar:

- Reconoce las presiones y desafíos adicionales que las personas de la comunidad LGTB pueden enfrentar en el lugar de trabajo. Ofrece recursos de salud mental y bienestar, como servicios de asesoramiento y programas de apoyo emocional.

### Alianzas con Empresas Inclusivas:

- Establece alianzas con empresas que han demostrado un compromiso real con la diversidad e inclusión. Colabora con estas empresas para crear oportunidades de empleo y desarrollo profesional para la comunidad LGTB.
Campañas Anti-Discriminación:

- Lanza campañas para combatir la discriminación en el lugar de trabajo. Estas campañas podrían incluir la promoción de políticas de no discriminación, la concientización sobre derechos laborales y la creación de recursos para enfrentar la discriminación.
Programas de Mentoría:

- Establece programas de mentoría que conecten a profesionales establecidos de la comunidad LGTB con aquellos que están ingresando al mundo laboral. La mentoría puede ser valiosa para el desarrollo de carreras y la construcción de redes profesionales.
