# CitaSmart

Asistente inteligente para la gestión de citas en centros de fisioterapia, desarrollado con n8n e integrado con Google Calendar, Google Sheets y herramientas de IA.

## Funcionalidades principales

- Consulta, creación, modificación y cancelación de citas.
- Verificación de disponibilidad horaria.
- Gestión de clientes con almacenamiento de datos.
- Respuesta automática a preguntas frecuentes (FAQ) mediante simulación RAG.
- Interfaz conversacional integrada con Telegram.

## Estructura del proyecto

El repositorio contiene los flujos exportados en JSON desde n8n:

- `Asistente_Principal_V2.json`: orquestador del asistente.
- `Gestion_Clientes_V2.json`: base de datos y lógica de clientes.
- `Crear_Evento`, `Modificar_Cita`, `Cancelar_Cita`, `Obtener_Citas`: flujos para la gestión de citas.
- `Verificar_Disponibilidad`, `Generar_Horarios_Disponibles`: lógica de disponibilidad.
- `Info_Centro_Retriever_V2`, `Infor_Centro_V2`: sistema de respuesta a preguntas informativas.
