# [Ejemplo Completado] Documento de Requisitos del Proyecto

> **Instrucciones de uso:** Documento rellenado (MarkIt) con criterios del proyecto técnico y especificaciones operativas.

## 1. Propósito
Este proyecto brindará luz sobre los patrones de comportamiento de los usuarios (compradores/vendedores) en MarkIt, facilitando el diseño de nuevos productos para incrementar la monetización y ventas.

## 2. Dependencias Clave
- **Infraestructura Técnica (Almacenamiento de Datos)** (Ariana Tirado) para disponibilizar tablas confiables.
- **Acceso Autorizado por Gobierno de Datos** (Cornelia Vega)
- Analista BI (Sam Winters)
- El entorno de visualización requerido para la conexión de bases de datos.

## 3. Requisitos de las Partes Interesadas
- **R (Requerido):** Datos agregados diarios, trimestrales y anuales.
- **R (Requerido):** Paneles y gráficos comprensibles para usuarios no técnicos.
- **R (Requerido):** Granularidad a nivel de categoría de producto e ID de cliente.
- **D (Deseado):** Gráfica de "tiempo en el sitio web antes de completar venta".
- **N (Agradable de tener):** Detalles profundos sobre los puntos donde el proceso de venta o listado es abandonado.

## 4. Criterios de Éxito (SMART)
- Desplegar la herramienta final a producción en **cuatro semanas** exactas tras la fase 1.
- Todas las métricas visuales se validan a contra balances de la base central con una precisión del **100%**.
- Disponer de reportes diarios, trimestrales, anuales de: anuncios creados vs vendidos vs eliminados.

## 5. Recorridos del Usuario (User Journeys)
- Los líderes de negocio (Alice Shi, Matías Sosa) requieren informes de la adopción global (ej. "quiero un reporte general del trimestre") y detalles del proceso de conversión de una búsqueda a venta real ("¿Si el comprador busca de forma amplia es menos probable que compre?").
- Idealmente abrirán su Dashboard online con su cuenta ejecutiva y verán los indicadores de conversión resumidos y con capacidades de desglose por categoría.

## 6. Suposiciones
- Existe una relación entre las sesiones de búsqueda del usuario y las compras.
- Los clientes están categorizados y sus IDs mapeados de forma inequívoca en las tablas.
- Los volúmenes agregados no generarán cuellos de botella para las visualizaciones.

## 7. Cumplimiento y Privacidad
- Solicitamos anonimización de información de pagos críticos.

## 8. Accesibilidad
- Soporte total para herramientas de dictado ("texto a voz") en la integración del dashboard y tamaño de fuentes adaptativo escalable (letra grande) asegurando lectura óptima a todos los usuarios.

## 9. Plan de Despliegue
- **Semana 1:** Exploración del Conjunto de Datos. Mapeo preliminar y validación de diseño de campos e ID's de usuario.
- **Semana 2:** Desarrollo de modelo dimensional (SQL) y limpieza/extracción (ETL/ELT).
- **Semana 3:** Entrega y finalización del modelo de datos de visualización (SQL). Boceto del Dashboard y fase de revisión entre pares para feedback comercial.
- **Semana 4:** Desarrollo interactivo, control de calidad, testeos (UAT) y despliegue final del panel (Go Live).
