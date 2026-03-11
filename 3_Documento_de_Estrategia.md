# Documento de Estrategia

> **Instrucciones de uso:** Este documento sirve como punto de colaboración para que el Analista de BI y las Partes Interesadas acuerden los entregables. Se basa en explorar qué métricas se necesitan, cómo se calculan y cualquier limitación de los datos.

## 1. Funcionalidad del Cuadro de Mando
> *Determine cómo debe funcionar la herramienta para los usuarios y los procesos a evaluar.*

**[Escriba las funcionalidades clave. Ejemplo: El panel permitirá ver y filtrar listas de artículos, evaluar si un comprador termina su venta al buscar términos amplios vs términos específicos, y el tiempo de vida de los anuncios hasta ser concretados.]**

## 2. Métricas y Gráficos Asociados
> *Especifique las métricas a implementar y su visualización propuesta.*

| Métrica | Descripción (Fórmula o Lógica) | Gráfico sugerido |
| :--- | :--- | :--- |
| **Tiempo de venta** | Días desde la publicación hasta la venta completada. | *[Ej. Gráfico de barras promedio o distribución]* |
| **Volumen de ventas** | Recuento total de anuncios exitosos. | *[Ej. Tarjetas (KPI) comparativas trimestrales/anuales]* |
| **Anuncios Eliminados** | Número de listados borrados antes de la compra. | *[Ej. Gráfico de área temporal]* |
| **Búsquedas vs Ventas** | Correlación entre el número de búsquedas únicas del usuario y su tasa de compra final. | *[Ej. Gráfico de dispersión (Scatter plot) o línea comparativa]* |

### **Parámetros Obligatorios a incluir:**
- **ID/nombre de usuario del cliente**
- **Categoría del artículo** (Ropa, Artículos para el hogar, etc.)
- **Fecha**

## 3. Limitaciones de los Datos y Suposiciones Técnicas
> *Anote qué podría salir mal con los datos, o qué restricciones de negocio aplican.*

- [Ej. Limitación 1: Sólo existe registro a partir del año anterior, no se evalúa histórico pre-2022.]
- [Ej. Suposición 1: Todos los usuarios tienen un UserID unívoco y no navegan "como invitados" cuando buscan la primera vez.]

## 4. Firma de Acuerdo
> *Al momento de revisión del primer borrador, el Analista le presenta un boceto a las Partes Interesadas para obtener retroalimentación.*

**Aprobación del Borrador por las Partes Interesadas:**
- [Nombre/Firma]
- [Fecha]
