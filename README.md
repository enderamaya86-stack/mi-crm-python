# Cauce CRM

Landing page de **Cauce**, un CRM pensado para pymes y equipos comerciales que unifica:

- **Gestión de clientes** — pipeline, historial de interacciones, tareas y seguimiento.
- **Tienda de productos digitales** — catálogo, checkout y entrega automática.
- **Redes sociales y captación de leads** — bandeja unificada de DMs/comentarios y leads automáticos desde formularios y anuncios.
- **Automatización e IA** — flujos sin código, resúmenes de conversación y puntuación de leads.

## Estructura del proyecto

```
index.html        # Landing page (HTML/CSS/JS estático)
app.py             # Servidor Flask que sirve index.html
requirements.txt   # Dependencias Python
Procfile            # Comando de arranque para despliegue
```

## Desarrollo local

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

La app queda disponible en `http://localhost:5000`.

## Despliegue en Railway

1. Crea un nuevo proyecto en Railway y selecciona "Deploy from GitHub repo".
2. Elige este repositorio (`mi-crm-python`).
3. Railway detecta automáticamente el proyecto Python (`requirements.txt`) y usa el `Procfile` para arrancar el servidor. No requiere configuración adicional.
