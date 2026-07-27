# SmartStudy AI

Plataforma web con inteligencia artificial que genera resúmenes, cuestionarios y planes de estudio personalizados a partir de un tema ingresado por el estudiante.

Proyecto desarrollado para el diplomado — Grupo #2.

## Equipo

- Sebastian David Chaparro Sánchez
- Nohelia Rodríguez Pastran
- Gabriela Rojas Rojas
- Ginna Esmeralda Páez Lancheros

## El problema

Los estudiantes pierden mucho tiempo buscando material de estudio y no saben cómo organizar su repaso antes de los exámenes.

## La solución

Una plataforma web donde el estudiante escribe un tema y recibe automáticamente:
- Un resumen corto
- Cinco preguntas tipo cuestionario
- Un pequeño plan de estudio

## Alcance del MVP

**Incluye:**
- Página web con una caja de texto para ingresar el tema
- Generación de resumen, preguntas y plan de estudio mediante IA

**No incluye (por ahora):**
- Inicio de sesión
- Historial de estudio
- Aplicación móvil
- Conexión con plataformas educativas

## Arquitectura y stack

| Capa | Tecnología |
|---|---|
| Backend | Python + Flask |
| Frontend | HTML, CSS y JavaScript |
| Inteligencia artificial | Gemini API (capa gratuita) |
| Control de versiones | Git + GitHub |

## Estructura del proyecto

```
smartstudy-ai/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   ├── config.py
│   ├── routes/
│   │   └── study_routes.py
│   ├── services/
│   │   └── ai_service.py
│   └── .env
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── main.js
├── docs/
│   ├── sprint-planning.md
│   └── arquitectura.md
├── .gitignore
└── README.md
```

## Instalación y ejecución

```bash
# Clonar el repositorio
git clone <url-del-repositorio>
cd smartstudy-ai

# Backend
cd backend
pip install -r requirements.txt
# Crear un archivo .env con la API key de Gemini:
# GEMINI_API_KEY=tu_api_key_aqui
python app.py

# Frontend
# Abrir frontend/index.html en el navegador
```

## Estado del proyecto

En desarrollo — Sprint 1 en curso.

## Documentación adicional

La planificación completa del proyecto (Sprint Planning, backlog, riesgos y evidencia gráfica) se encuentra en la carpeta `docs/` y en el espacio de Notion del equipo.
