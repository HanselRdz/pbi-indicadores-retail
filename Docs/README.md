
# 📊 Indicadores del Dashboard de Retail

Este documento describe los indicadores clave utilizados en el tablero de indicadores estratégicos para retail, explicando su propósito, utilidad y cómo contribuyen a la toma de decisiones comerciales.

---

## 🛒 Seguimiento de Ventas
**Definición:** Compara las ventas actuales con las del año anterior, analiza la evolución mensual y permite segmentar por categoría, subcategoría y tienda.
**Utilidad:** Identifica tendencias, estacionalidades y oportunidades de crecimiento.
**Decisiones que habilita:** Ajustes en estrategias de venta, promociones y surtido por tienda.

---

## 🔁 Sell Through
**Definición:** Mide la rotación de productos en función del inventario disponible.
**Utilidad:** Evalúa la eficiencia del surtido y detecta productos con baja salida.
**Decisiones que habilita:** Optimización del portafolio, ajustes en compras y reposición.

---

## ❌ Venta Perdida
**Definición:** Estima las ventas no realizadas por falta de inventario.
**Utilidad:** Ayuda a reducir quiebres de stock y mejorar la disponibilidad de productos.
**Decisiones que habilita:** Mejora en la planificación de inventarios y abastecimiento.

---

## ⚖️ Polarización de Productos
**Definición:** Identifica productos con alto y bajo desplazamiento dentro de cada subcategoría.
**Utilidad:** Permite evaluar la participación, disponibilidad y rotación de productos.
**Decisiones que habilita:** Revisión de surtido, eliminación de productos poco rentables, fortalecimiento de líderes de categoría.

---

# 🧩 Estructura del Modelo de Datos

El modelo de datos está basado en una arquitectura estrella, compuesta por:
- **Tabla de hechos:** Fact_Venta, Fact_Compra y Fact_Inventario.
- **Dimensiones:**
  - Tienda
  - Producto (SKU, categoría, subcategoría)
  - Fecha
  - Proveedor

Cada registro representa una combinación de tienda-producto-fecha con métricas asociadas como ventas, inventario, rotación y disponibilidad.

---

# 📈 Recomendaciones de Uso del Dashboard

- Utilizar filtros por tienda, categoría y periodo para análisis detallado.
- Comparar KPIs actuales vs históricos para identificar brechas.
- Revisar productos con baja rotación o alta venta perdida.
- Evaluar polarización para ajustar el portafolio.

---

© Hansel Rodríguez, 2025
