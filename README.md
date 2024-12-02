Introducción:
El proyecto busca mejorar la experiencia del cliente mediante un acceso unificado y automatizado que permita una atención rápida, personalizada y disponible las 24 horas. La implementación de un chatbot optimizará recursos, mejorará tiempos de respuesta, y aumentará la eficiencia en la resolución de consultas y problemas comunes de nuestros clientes.

Nombre del proyecto: ChatBot Atención al cliente Acceso Unificado

Presentación del problema a abordar: 
El objetivo principal de este proyecto es la clasificación de la necesidad del cliente para poder realizar las derivaciones a los departamentos de la empresa correspondientes.

Desarrollo de la propuesta de solución:
Prompts para Identificación y Clasificación de la Necesidad del Cliente:
Los prompts que se usarán en el chatbot están diseñados para analizar los mensajes del cliente y determinar su necesidad principal. Estos prompts estarán estructurados para detectar palabras clave y frases comunes en las siguientes categorías: Atención al Cliente, Mesa De Ayuda, Ventas, y Capacitación. 

Prompt de Identificación de Necesidad Inicial:
El chatbot analizará la respuesta del cliente a la pregunta “¿En qué te puedo ayudar?”en busca de palabras clave o frases que revelen su necesidad, como "problema técnico", "código", "asistencia", "contratar", "cambio de datos", entre otros.

Prompt de Clasificación de Necesidad:
Con base en la respuesta del cliente, el chatbot empleará modelos de clasificación para derivar automáticamente al área correspondiente.

Justificación de la viabilidad del proyecto:
Este proyecto se basa en herramientas de IA text to text. Por el momento el proyecto no deberá procesar voz ni imágenes. Está orientado al mejoramiento de la generación de prompts.

Objetivos: Indica los objetivos del proyecto.
El objetivo principal del proyecto es la clasificación de las necesidades de los clientes para luego poder brindar una respuesta acorde a éstas.
En primera instancia, se realizará la clasificación de la necesidad, y luego a medida que avance el chatbot, se brindarán respuestas específicas, de acuerdo a la derivación.

Metodología:
Por medio de prompts clasificadores y palabras claves, se logra determinar el departamento con el que debe comunicarse el cliente. A futuro, se necesitará que se interprete la necesidad para dar respuestas concretas y en caso de no ser posible, derivar a un operador.

Herramientas y tecnologías:
Mediante la API de OpenAI se realizan las clasificaciones necesarias.
En este proyecto no es necesaria la creación de imágenes ya que es una atención por escrito para clasificar las necesidades de los clientes.

Implementación:
En el proyecto se encuentra el libro de Juypter Notebook para ver el código generado.
