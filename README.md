# Challenge-2-TelecomX

## Introducción
Se realizó una evaluación como asistente de análisis de datos en la empresa Telecom X dentro del proyecto "Churn de Clientes". Mediante el presente proyecto se busca determinar las causas del alto índice de abandono de los clientes al realizar un Análisis Exploratorio de Datos, para lo cual fue proporcionada una base de datos de la empresa, la cual pasó por un procedimiento de ETL para poder ser analizada.  
________________________________________________________________________________

## Tratamiento de datos
La información proporcionada fue mediante un documento JSON, el método de extracción fue realizado utilizando la librería Pandas para la generación del Data Frame (DF). El DF resultante requirió un tratamiento para el acomodo de los diccionarios dentro de las distintas columnas, así como el manejo de información faltante en la columna 'Churn', se optó por eliminar esta información indeterminada constataba menos del 5% general y resultaba irrelevante para el análisis.

Finalmente, se le realizó un tratamiento a los distintos tipos del DF con la finalidad de mantener una mayor legibilidad al transformar objetos a valores enteros y flotantes, de esta manera en futuros análisis el procesamiento de la información resultará más directo y al tener un mismo térmio para valores de sí = 1 y no = 0, se facilita el entendimiento del DF.
________________________________________________________________________________

## Información obtenida

Mediante el análisis de resultados realizado previamente, se determinó que los clientes con mayor tasa de abandono cuentan con las siguientes características Senior, proporcionalmente hablando, con un contrato de mes a mes, solteros, método de pago de tipo cheque electrónico, con baja inversión total y con gastos mensuales o diarios más elevados.

La estrategia que se propone para evitar la desersión de mayor clientela radica en hacer planes más atractivos para los senior y no senior, pues aunque proporcionalmente los senior cuentan con mayor tasa de abandono, la magnitud de no senior que abandonan de igual manera es bastante significativa ya que representa más mercado que los clientes senior. 

Por otro lado, se recomienda facilitar el cambio del método de pago, principalmente de los clientes de cheque electrónico, así como buscar el motivo por el cuál no les agrada tanto este método para tomar acciones correctivas. 

Finalmente, se deberá buscar reducir los gastos diarios y mensuales de los clientes mediante promociones o incentivos como campañas de lealtad, de igual manera, se deberá buscar una forma para que su inversión total sea mayor mediante contratos más extensos, pues se demostró que los clientes con planes de mayor duración cuentan con un índice de abandono muy bajo.

Se recomienda a los ejecutivos de la empresa TelecomX considerar seriamente las propuestas proporcionadas y tomar acción inmediata, ya que los datos demostraron actualmente al menos el 26.53% de la clientela ya abandonó la empresa, sin considerar a aquellos clientes con información faltante.

Si deseas saber más sobre el tratamiento realizado sobre el Data Frame, así como el análisis de las gráficas obtenidas, te invito a acceder al documento TelecomX_LATAM.ipynb. ¡Saludos!
