# Documentos Inteligencia Empresarial (BI) - Proyecto MarkIt

Este repositorio contiene las plantillas clave necesarias para la fase de planificación de proyectos de Inteligencia Empresarial (BI), ordenadas por el flujo natural de trabajo. **Cada documento ha sido traducido al español y se ofrece tanto en formato Word (`.docx`) como en texto plano Markdown (`.md`) para edición directa.**

Además, encontrarás una carpeta **`/Ejemplos`** con las plantillas ya resueltas (y pasadas a Markdown) para el caso de estudio adjunto de "MarkIt".

1. **`1_Documento_de_Requisitos_de_las_Partes_Interesadas.md`** / `.docx`
2. **`2_Documento_de_Requisitos_del_Proyecto.md`** / `.docx`
3. **`3_Documento_de_Estrategia.md`** / `.docx`

## 📌 Contexto del Proyecto: MarkIt

Usted trabaja como profesional de BI para **MarkIt**, una empresa de ventas de consumidor a consumidor. La plataforma de MarkIt facilita la venta de artículos de segunda mano entre particulares.
El objetivo del proyecto es entender cómo usan la plataforma tanto compradores como vendedores para poder diseñar nuevos productos y mejorar la experiencia de usuario.

### Notas de la Reunión

**Partes interesadas:**
- Alice Shi, Vicepresidenta de Ventas
- Matías Sosa, Gerente del programa

**Miembros del equipo:**
- Ariana Tirado, Especialista en Almacenamiento de datos
- Cornelia Vega, Responsable de Gobierno de datos
- Sam Winters, Analista de datos

**Requisitos Generales:**
- El panel de control debe ser accesible, con letra grande y alternativas de texto a voz.
- Revisar datos diarios, trimestrales y anuales de: anuncios publicados, ventas realizadas y anuncios eliminados.
- Comprender el comportamiento del usuario: ¿Qué buscan? Si buscan más cosas, ¿compran más? ¿Qué puntos de dolor hay en la experiencia?

**La pregunta / métricas a investigar:**
- Incluir ID/nombre de usuario, categoría del artículo y fecha.
- Gráfico sobre el tiempo que los listados de ventas están activos antes de su venta.
- Para compradores: Gráfico que compare búsquedas realizadas vs ventas completadas.

**Despliegue planeado (4 semanas):**
* Semana 1: Asignación del conjunto de datos y diseño inicial.
* Semana 2: Desarrollo SQL/ETL.
* Semana 3: Finalización SQL y diseño del tablero.
* Semana 4: Pruebas y despliegue del Dashboard.

---

## 🛠️ Cómo Utilizar Estos Documentos

Siga el siguiente orden para completar las plantillas de planificación:

### Paso 1: Documento de Requisitos de las Partes Interesadas
> Archivo: `1_Documento_de_Requisitos_de_las_Partes_Interesadas.md`

Utilícelo para captar las peticiones de los interesados y comprender sus necesidades. Debe responder a:
- **Problema empresarial:** ¿Cuál es la pregunta o problema principal?
- **Partes interesadas:** ¿Quiénes son y cuáles son sus cargos?
- **Uso:** ¿Cómo utilizarán la herramienta?
- **Requisitos principales:** ¿Qué necesita la herramienta para tener éxito?

### Paso 2: Documento de Requisitos del Proyecto
> Archivo: `2_Documento_de_Requisitos_del_Proyecto.md`

Contiene los detalles técnicos y de gestión del proyecto:
- **Propósito:** Por qué la empresa invierte en esto.
- **Dependencias:** Equipos, recursos o entregables principales.
- **Requisitos de las partes interesadas:** Priorizados como R (requeridos), D (deseados) o N (agradables).
- **Criterios de éxito:** Metas medibles (SMART).
- **Recorridos del usuario:** La experiencia actual vs ideal.
- **Suposiciones, Cumplimiento y Accesibilidad:** Temas legales, privacidad, accesibilidad del informe.
- **Plan de despliegue:** Alcance temporal de 4 semanas, rollback, y momentos de medición.

### Paso 3: Documento de Estrategia
> Archivo: `3_Documento_de_Estrategia.md`

Es el acuerdo colaborativo sobre los entregables y la métricas funcionales de BI.
- Aquí define la limitación de datos, los cálculos necesarios de métricas, y las suposiciones de datos finales.
- Este documento suele requerir el visto bueno final de las partes interesadas antes del trabajo de implementación técnica.

### ❓ Tarea pendiente de las Notas:
Escriba de 3 a 5 preguntas de seguimiento a las partes interesadas sobre cualquier información faltante en la reunión (por ejemplo, el origen técnico de las BDD) para poder rellenar por completo estos documentos de planificación.
