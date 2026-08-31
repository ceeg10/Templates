# 🧪 Plantilla Profesional de Casos de Prueba Funcionales (QA / Testing)

[![QA - Status](https://img.shields.io/badge/QA-Functional_Testing-blue.svg)](#)
[![Excel Template](https://img.shields.io/badge/Template-Excel-green.svg)](#)
[![Jira - Integration](https://img.shields.io/badge/Traceability-Jira-0052CC.svg)](#)

¡Bienvenido/a a este repositorio! 👋  

Como **QA Analyst / Test Engineer**, he diseñado y optimizado esta **plantilla estándar en Excel** para la gestión, ejecución y seguimiento de **casos de prueba funcionales**. El objetivo principal de este recurso es brindar una estructura clara, organizada y escalable para garantizar la calidad del software en ciclos de pruebas iterativos (Agile/Scrum o Tradicional).

---

## 📌 Características Principales

- **Trazabilidad con Gestión de Requisitos:** Sección superior dedicada para vincular la *User Story (HU)* en Jira, descripción funcional y enlaces directos a carpetas de evidencias.
- **Estructura Detallada de Casos de Prueba:** Campos claros para ID, Escenario, Precondiciones, Datos de Prueba (*Test Data*), Pasos y Resultados (Esperado vs. Obtenido).
- **Atributos de QA Esenciales:** Clasificación por *Criticidad* (Alta, Media, Baja), *Tipo de Caso de Prueba* (Funcional, Regresión, Smoke, etc.) y *Estado* (Aprobado, Fallido, Bloqueado, Pendiente).
- **Matriz de Pruebas Multi-Browser / Multi-Dispositivo:** Secciones organizadas por ciclos/fechas para registrar ejecuciones en múltiples navegadores (*Chrome, Firefox, Edge, Safari*) y entornos.
- **Control de Ejecución e Histórico:** Registro de responsable (*Tester*), fecha de ejecución y referencias a evidencias individuales por caso de prueba.

---

## 📄 Estructura del Archivo (`.xlsx`)

La plantilla cuenta con una cabecera de contexto del requerimiento y una tabla principal dividida de la siguiente manera:

### 1. Encabezado de la Historias de Usuario (HU)
| Campo | Descripción |
| :--- | :--- |
| **Descripción HU** | Resumen funcional de la Historia de Usuario o Requisito. |
| **Link HU en Jira** | Enlace directo a la tarea o ticket en la herramienta de gestión. |
| **Carpeta de Evidencias** | Link general a Google Drive / OneDrive con capturas o videos. |

### 2. Definición del Caso de Prueba
| Columna | Descripción |
| :--- | :--- |
| **ID** | Identificador único del caso (ej. `TC_01`). |
| **Escenario** | Título o propósito de la prueba. |
| **Precondiciones** | Estado previo requerido del sistema antes de ejecutar. |
| **Data** | Datos de entrada necesarios (*Test Data*). |
| **Pasos** | Secuencia detallada de acciones a realizar. |
| **Resultado Esperado** | Comportamiento que se aguarda según la especificación. |
| **Resultado Obtenido** | Comportamiento real observado durante la prueba. |
| **Estado** | Resultado final (`Aprobado`, `Fallido`, `Bloqueado`, etc.). |
| **Tipo CP** | Categoría de la prueba (ej. `Funcional`). |
| **Criticidad** | Nivel de impacto (`Alta`, `Media`, `Baja`). |

### 3. Matriz de Ejecución y Cobertura (Browsers / Ambientes)
Permite validar el comportamiento en paralelo a lo largo de diferentes ejecuciones/fechas:
- 🌐 **Navegadores:** Chrome, Firefox, Edge, Safari.
- 👤 **Tester:** Responsable de la ejecución.
- 📅 **Fecha:** Día de la validación.
- 🖼️ **Evidencia:** Link específico a la captura o log del resultado.

---

## 🚀 Cómo Usar esta Plantilla

1. **Descarga la plantilla:** Puedes descargar directamente el archivo `.xlsx`:
