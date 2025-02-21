Solución de IA para Consultas de Tarjetas de Crédito
Este proyecto implementa un modelo de inteligencia artificial para automatizar respuestas a consultas frecuentes sobre tarjetas de crédito (bloqueos, cargos no reconocidos, problemas con pagos, ampliación de límites y activación). La solución mejora la experiencia del cliente, optimiza la eficiencia operativa y reduce costos al minimizar las llamadas a la API.

Objetivos
Automatización de Respuestas: Reducir la carga sobre el equipo de atención al cliente.
Mejora en la Experiencia: Ofrecer respuestas rápidas y precisas.
Escalabilidad: Atender múltiples consultas simultáneamente.
Optimización de Costos: Reducir el número de llamadas a la API mediante estrategias como caching y batching.
Herramientas y Tecnologías
Entorno de Desarrollo: Jupyter Notebook
Lenguaje: Python
Librerías:
Requests / OpenAI SDK (para llamadas a la API)
Pandas, NumPy (para manipulación y análisis de datos)
Matplotlib / Seaborn (para visualización de métricas)
Modelos de IA:
ChatGPT (para procesamiento de lenguaje natural)
Modelos de texto-imagen: Nightcafe para generar contenido visual
Infraestructura: Servidores en la nube y API Gateway para la integración y monitoreo.
Metodología
Análisis y Diseño:

Revisión de datos históricos y definición de prompts para cada tipo de consulta.
Desarrollo y Pruebas en Jupyter:

Implementación del código (ver notebooks en el repositorio) para interactuar con la API.
Evaluación de la calidad de las respuestas y optimización de la lógica de llamadas.
Optimización de Consultas a la API:

Caching: Almacena respuestas a consultas frecuentes.
Batching: Agrupa solicitudes para reducir el número de llamadas.
Monitorización: Se implementan logs y dashboards (en Jupyter) para controlar el uso de la API.
Implementación y Escalamiento:

Despliegue piloto, recolección de feedback y ajustes continuos.
Evaluación de Costos
El análisis del código indica que:

Consulta Texto a Texto: Genera 1 llamada a la API por interacción.
Consulta Texto-Imagen: Puede generar hasta 2 llamadas (una para cada tipo de respuesta).
La implementación de técnicas de caching y batching reduce significativamente el número total de llamadas, disminuyendo los costos operativos asociados.
