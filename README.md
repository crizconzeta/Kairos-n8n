## Hola!

Este es el repositorio que almacena los flujos de automatización creados por la comunidad **Kairós Digital**,  de forma pública.

La intención es ser un repositorio que pueda ser utilizado por toda la comunidad asociada a __n8n__, ser una fuente de información y referencia.

Tenemos un video que explica [como cargar los flujos](https://www.youtube.com/watch?v=2Yf8n3Se30k&list=PLnjy4kyqS_R8bE_ni0TxblyXswJWqRhqa&index=13)


Puedes mantenerte actualizado con nuestros tutoriales en nuestro canal [Youtube - KairosDigital.cl](https://www.youtube.com/watch?v=eOwEpMq-BQI&list=PLnjy4kyqS_R8bE_ni0TxblyXswJWqRhqa)


## Sobre Kairós

Tenemos lista de correo con [contenido exclusivo](https://kairosdigital.cl/kits-de-herramientas/automatizacion-de-procesos/
) y servidor de [discord, para resolver dudas](https://discord.com/invite/cHAc3bJxxe)


#### Si necesitas crear una cuenta en n8n se recomienda comenzar con n8n en la nube.

- Crea tu [cuenta de n8n](https://n8n.partnerlinks.io/vihfa9ov2fyg) (Link afiliado)

## Estructura de Carpetas

- **Envio de Correos**: Contiene flujos de trabajo para el envío de correos electrónicos a través de diferentes servicios.
- **Formularios**: Almacena flujos que gestionan la recepción y procesamiento de datos de formularios.
- **Integraciones**: Incluye flujos que demuestran la integración de n8n con otras plataformas y servicios.
- **Inteligencia Artificial**: Contiene flujos que utilizan modelos de IA para realizar tareas como chatbots, clasificación de texto y asistencia virtual.
- **Webhooks**: Almacena flujos que se activan a través de webhooks para la comunicación entre aplicaciones.

## Descripción de los Flujos

A continuación se detallan los flujos de trabajo disponibles en este repositorio:

### Envio de Correos

- [**AWS_SES__demo.json**](Envio%20de%20Correos/AWS_SES__demo.json): Un flujo de demostración para enviar correos electrónicos utilizando el servicio AWS SES.

### Formularios

- [**FormSimple_AI.json**](Formularios/FormSimple_AI.json): Captura datos de un formulario simple y utiliza IA para generar y enviar un correo de bienvenida personalizado.

### Integraciones

- [**Tutorial_n8n___nocodb.json**](Integraciones/Tutorial_n8n___nocodb.json): Un tutorial que muestra cómo integrar n8n con NocoDB para gestionar datos.

### Inteligencia Artificial

- [**AI_Chatbot____Privado_.json**](Inteligencia%20Artificial/AI_Chatbot____Privado_.json): Un chatbot que lee un archivo local (PDF) y responde preguntas sobre su contenido, utilizando un almacén de vectores en Supabase.
- [**Asistente_Gmail.json**](Inteligencia%20Artificial/Asistente_Gmail.json): Un agente de IA que se conecta a Gmail, clasifica los correos y realiza acciones como etiquetar o marcar como leídos.
- [**ClasificaCorreosConAI.json**](Inteligencia%20Artificial/CasificaCorreosConAI.json): Clasifica automáticamente los correos electrónicos entrantes en Gmail utilizando un modelo de lenguaje y les asigna las etiquetas correspondientes.
- [**Demo_Chat_MCP.json**](Inteligencia%20Artificial/Demo_Chat_MCP.json): Un ejemplo de un chatbot más complejo que utiliza memoria y herramientas externas para responder a las preguntas del usuario.
- [**GMAIL_TEST___MCP.json**](Inteligencia%20Artificial/GMAIL_TEST___MCP.json): Proporciona un conjunto de herramientas para interactuar con la API de Gmail, permitiendo buscar, leer y eliminar correos.

### Webhooks

- [**WebHook_Demo.json**](Webhooks/WebHook_Demo.json): Un ejemplo de cómo crear un webhook seguro en n8n que requiere autorización para acceder a los datos.
