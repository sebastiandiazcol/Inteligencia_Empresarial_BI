# [Ejemplo Completado] Documento de Estrategia

> **Instrucciones de uso:** Este documento concreta los entregables analíticos y KPIs definitivos acordados entre las partes técnicas (BI) y el equipo de producto (Alice Shi, Matías Sosa) para MarkIt C2C.

## 1. Funcionalidad del Cuadro de Mando
El panel principal de **MarkIt** tendrá los siguientes alcances:
- Monitoreo de Publicaciones (Creación y Eliminación).
- Patrones de comportamiento pre-compra en el motor de búsqueda interno.
- Puntos de abandono a lo largo del "Embudo de compra/venta".

El panel deberá integrarse con opciones accesibles de lectura de *Texto a Voz* nativas y permitir redimensionar elementos en interfaces de letras grandes de inmediato.

## 2. Métricas y Gráficos Asociados
*(Estos puntos han sido validados previamente en borrador)*

| Concepto a Visualizar | Sugerencia Técnica o Gráfico | Campos Estrictos Requeridos |
| :--- | :--- | :--- |
| **Volumen Total Operativo** | Tarjetas (KPIs), comparativas entre "Anuncios Creados", "Realizados/Vendidos" y "Borrados por el Vendedor". | **ID de Usuario** y Fecha Anual/Trims/Diario. |
| **Tiempo de Vida de Anuncio** | Gráfico combinatorio que indique cuánto tiempo duran las publicaciones antes de concretarse como "Ventas Existosas". | **Fecha de Modificación de Venta**, **Fecha Creación**. |
| **Conversión Búsqueda/Compra** | Gráfico de dispersión o de mapa. Cruce entre el Tipo de Búsqueda del usuario (Términos amplios vs Términos ajustados) y la *Tasa de Finalización de Compra*. | **ID del Cliente**, **Categoría del Artículo**. |

## 3. Limitaciones de los Datos y Suposiciones Técnicas
- Asumimos que los *logs* analíticos del motor de búsqueda web (tiempo en el sitio web de búsquedas, qué subpáginas navegan los usuarios de MarkIt) se relacionan correctamente al **UserID** final o perfil del cliente que convierte la venta de la base de datos transaccional normalizada.
- Aún se desconoce si dispondremos de datos de fallas orgánicas directas de la plataforma.

## 4. Firma de Acuerdo
Este documento autoriza al equipo de BI a desarrollar la versión Productiva con soporte técnico ETL (Ariana Tirado):

**Aprobación del Borrador por las Partes Interesadas:**
- Alice Shi, _Vicepresidenta de Ventas_
- Matías Sosa, _Gerente del Proyecto_
- Sam Winters, _Analista Principal_

*(Las siguientes semanas involucrarán el desarrollo, maquetación, control de calidad y validación con los usuarios finales)*
