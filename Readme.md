
### Diseño del flujo en Excalidraw

Primero diseñé el flujo en **Excalidraw** antes de construir la automatización. Representé visualmente todo el proceso, desde la recepción del código de barras hasta la respuesta final. Definí las validaciones, las diferentes decisiones, las rutas de error y los procesos de análisis nutricional.

También separé el análisis del **semáforo nutricional** y del **Nutri-Score**, para después combinar ambos resultados y obtener el veredicto final. Finalmente, incorporé la generación de la respuesta mediante IA y la devolución del resultado al usuario.

### Automatización en n8n y README

Después llevé este diseño a **n8n**, construyendo la automatización por etapas y probando cada parte del flujo. La automatización recibe el código de barras, consulta **Open Food Facts**, valida el producto y sus datos nutricionales, realiza las clasificaciones y genera el resultado final mediante IA.

Por último, documenté el proyecto en el archivo **README.md del repositorio**, explicando el objetivo, el funcionamiento de la automatización, los pasos principales del flujo, las validaciones y la forma de utilizar el proyecto. Esto permite que otra persona pueda entender rápidamente cómo está construido y cómo ejecutarlo.
