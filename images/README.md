# 📸 Capturas del Dashboard en Power BI

Esta carpeta contiene imágenes del dashboard en acción, mostrando cómo funcionan los filtros y visualizaciones interactivas.

## 🖼️ Capturas Incluidas
- `dashboard_general.png` → Vista general del dashboard.
- `ventas_por_vendedor.png` → Gráfico de ventas por vendedor.
- `mas_vendido.png` → Producto más vendido con el vendedor seleccionado.
- `filtros_dashboard.png` → Uso de filtros para análisis por fecha y vendedor.
- `modelado_datos.png` → **Modelo de datos en Power BI.**

## 🔎 📊 **Modelo de Datos en Power BI**
El modelado de datos es una parte clave del proyecto, ya que permite integrar información de distintas tablas para generar análisis más precisos.

![Modelo de Datos](modelado_datos.png)

### 📌 **Estructura del Modelo**
- **`Ventas`** → Tabla principal con los registros de ventas por producto, fecha y representante.
- **`Vendedores`** → Contiene información adicional de cada representante: ciudad y fotografía.
- **`Productos`** → Información de los productos vendidos: descripción, precio, costo y almacén.

### 🔗 **Relaciones entre las Tablas**
- `Ventas[Representante]` se relaciona con `Vendedores[Representante]` (**relación muchos a uno**).
- `Ventas[CódigoProducto]` se relaciona con `Productos[CódigoProducto]` (**relación muchos a uno**).

## 🔎 **Interacción con el Dashboard**
1. **Filtrar ventas por período** para analizar tendencias a lo largo del tiempo.
2. **Seleccionar un vendedor específico** para evaluar su rendimiento individual.
3. **Visualizar productos más vendidos** para detectar oportunidades de negocio.

🚀 **Este dashboard permite tomar decisiones estratégicas basadas en datos de manera efectiva.**

