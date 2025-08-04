Descripción
Telecom X - Análisis de Evasión de Clientes

Has sido contratado como asistente de análisis de datos en Telecom X y formarás parte del proyecto "Cancelación de Clientes". La empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

Tu desafío será recopilar, procesar y analizar los datos, utilizando Python y sus principales bibliotecas para extraer información valiosa. A partir de tu análisis, el equipo de Data Science podrá avanzar en modelos predictivos y desarrollar estrategias para reducir la evasión.

Informe final

Informe Final - Análisis de Evasión de Clientes (Cancelación) en TelecomX

**1. Introducción**

El presente análisis tiene como objetivo identificar los factores que influyen en la evasión de clientes (Cancelación) en la empresa TelecomX. La retención de clientes es un aspecto clave en la sostenibilidad y crecimiento de cualquier compañía de servicios, ya que adquirir nuevos clientes suele ser más costoso que mantener a los actuales.

El problema de la Cancelación consiste en detectar qué características o patrones están más asociados con la cancelación del servicio por parte de los usuarios. A través del análisis de datos y visualizaciones, buscamos generar insights valiosos que permitan a la empresa tomar decisiones estratégicas para reducir la tasa de cancelación.


**2. Limpieza y Tratamiento de Datos**

Para comenzar, se llevó a cabo una serie de pasos de preprocesamiento de los datos:

  -Importación de datos desde un archivo .jon.

  -Revisión y corrección de valores nulos o inconsistentes.

  -Conversión de variables categóricas a formato adecuado.

  -Transformación de columnas como TotalCharges, que estaba en formato string, a valores numéricos.

  -Estandarización de etiquetas en variables como la Cancelación, SeniorCitizen, InternetService, entre otras.

Este proceso fue esencial para asegurar la calidad del análisis posterior.


**3. Análisis Exploratorio de Datos**

Se realizaron distintas visualizaciones para comprender mejor el comportamiento de los clientes:

Distribución de la variable objetivo (Cancelación)

  -Se observó que aproximadamente 25% de los clientes han abandonado el servicio, mientras que el 75% permanecen activos.

Relación entre Cancelación y otras variables:

  -Edad (Ciudadano_senior): Los adultos mayores tienen una mayor tasa de cancelación.

 -Gráfico de recuento por Ciudadano_senior y Cancelación

  -Tipo de contrato: Los contratos mensuales presentan una mayor tasa de Cancelación que los contratos anuales o de dos años.

  -Servicio de Internet: Clientes con servicio de fibra óptica mostraron mayor propensión a la cancelación.

  -Facturación electrónica  y método de pago también se asociaron con mayor cancelación.

  -Total de cargos mensuales: Los clientes con cargos mensuales altos tienen más probabilidad de irse.


**4. Conclusiones e Insights**

Los principales hallazgos del análisis fueron:

  -Existe una clara relación entre tipo de contrato y la Cancelación: los contratos mensuales tienen mayor evasión.

  -Adultos mayores son más propensos a abandonar el servicio, posiblemente por dificultades tecnológicas o menor uso del servicio.

  -El servicio de fibra óptica, aunque veloz, parece asociado a una experiencia menos satisfactoria o precios más elevados.

  -Clientes que usan facturación electrónica y pagan con métodos automáticos como tarjetas tienden a cancelar más.

Estos patrones permiten identificar segmentos de clientes con mayor riesgo de abandono, lo que puede guiar futuras estrategias de retención.


**5. Recomendaciones**

Con base en los resultados, se proponen las siguientes acciones:

  -Ofrecer incentivos y beneficios exclusivos para clientes con contratos mensuales, motivando el cambio a planes de largo plazo.

  -Diseñar campañas de retención orientadas a adultos mayores, con atención personalizada y asistencia técnica.

  -Revisar la experiencia del cliente con el servicio de fibra óptica, identificando posibles causas de insatisfacción.

  -Implementar alertas tempranas para clientes con cargos altos y métodos de pago automáticos, ofreciendo promociones o asesorías.

  -Segmentar la base de clientes según riesgo de evasión y realizar intervenciones proactivas.

