# [Ejemplo Completado] Documento de Requisitos de las Partes Interesadas

> **Instrucciones de uso:** Este documento contiene un ejemplo real rellenado para el proyecto **MarkIt**, documentando las necesidades y requerimientos de los directivos.

## 1. Problema empresarial
> *¿Cuál es la pregunta principal que hay que responder o el problema que hay que resolver?*

El objetivo principal es entender cómo los compradores y vendedores utilizan la plataforma C2C y utilizar esa información para mejorar la experiencia del usuario y diseñar nuevos productos. Queremos analizar datos de listados, ventas, eliminación de publicaciones y patrones de búsqueda para identificar cuellos de botella y mejorar las métricas de conversión.

## 2. Partes interesadas
> *¿Quiénes son los principales interesados en este proyecto y cuáles son sus cargos?*

- **Alice Shi** | Vicepresidenta de Ventas
- **Matías Sosa** | Gerente del programa
- **Equipo BI:** Ariana Tirado (Especialista BD), Cornelia Vega (Gobierno de Datos), Sam Winters (Analista de Datos)

## 3. Detalles de uso de las partes interesadas
> *¿Cómo utilizarán las partes interesadas la herramienta de BI?*

El equipo directivo y los product managers utilizarán los paneles de control de forma frecuente (mensual y trimestralmente) para evaluar el progreso y la salud general de las ventas en la plataforma.

## 4. Requisitos principales
> *¿Qué requisitos debe cumplir esta herramienta de BI para que este proyecto tenga éxito?*

- Las métricas deben mostrarse a nivel diario, trimestral y anual.
- Debe incluir estadísticas de listados creados, artículos vendidos y anuncios eliminados.
- Relación clara sobre cómo se correlacionan las búsquedas con las compras concretadas.
- **Accesibilidad:** Los reportes requieren uso de fuentes grandes y deben ser compatibles con utilidades de "Texto a Voz".

---

### Notas Adicionales / Preguntas de Seguimiento Planeadas:
1. ¿A nivel técnico, la base de datos registra el momento exacto (timestamp) de todas las búsquedas de usuarios?
2. ¿Existen políticas de depuración (eliminación) de datos antiguos que debamos considerar antes de traer información histórica?
3. ¿Cuál es la herramienta actual que utiliza el equipo para consumir datos?
