GCP App Observability Lab
Este repositorio documenta el despliegue y monitoreo de una aplicación web en Google Cloud Platform utilizando App Engine, como parte de un laboratorio práctico de observabilidad.

🧪 Descripción general
Se implementó una aplicación desarrollada con Flask y se aplicaron prácticas de monitoreo avanzadas para medir latencia, configurar alertas y explorar registros (logs). El objetivo fue observar el rendimiento de la aplicación y activar notificaciones en caso de incidentes.

🚀 Tecnologías utilizadas
Google Cloud App Engine

Google Cloud Monitoring

Google Cloud Logging

Google Cloud Shell

Python (Flask)

Alert Policies (99th percentile)

Métricas de latencia y errores HTTP

✅ Lo que se configuró
Despliegue de app con Flask en App Engine.

Simulación de carga con curl para generar tráfico real.

Configuración de métricas: latencia (99th percentile) y errores 500.

Políticas de alerta por CLI y consola.

Visualización de logs e investigación de incidentes.

📂 Estructura del proyecto
css
Copiar
Editar
📁 app/
 ┣ 📄 main.py
 ┣ 📄 app.yaml
 ┣ 📁 templates/
 ┃ ┗ 📄 index.html
 ┗ 📄 requirements.txt
📌 Lecciones aprendidas
Interpretación de métricas distribuidas.

Configuración efectiva de alertas con condiciones avanzadas.

Importancia de la observabilidad para prevenir fallos críticos.

Diagnóstico proactivo usando logs en producción.
