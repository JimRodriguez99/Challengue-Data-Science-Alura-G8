# Challengue-Data-Science-Alura-G8
# Análisis Comparativo de Productos por Tienda

Este proyecto contiene scripts de Python para generar visualizaciones comparativas basadas en un análisis de datos de productos en cuatro tiendas diferentes. El análisis muestra información sobre los productos más/menos vendidos, mejor/peor calificados, y los más costosos/baratos por tienda.

## Descripción

El script `comparativas_tiendas.py` genera tres gráficos para visualizar y comparar el rendimiento de productos entre tiendas:

1. **Productos Más y Menos Vendidos**: Gráfico de barras verticales que compara los productos más vendidos y menos vendidos en cada tienda.
2. **Productos Mejor y Peor Calificados**: Gráfico de barras horizontales que muestra los productos mejor y peor calificados en cada tienda.
3. **Frecuencia de Productos**: Gráfico de barras que presenta qué productos aparecen con mayor frecuencia en distintas categorías (más vendido, mejor calificado, etc.).

## Requisitos

Para ejecutar este proyecto necesitas tener instalado:

- Python 3.6 o superior
- pandas
- matplotlib
- numpy
- seaborn

Puedes instalar las dependencias usando pip:

```bash
pip install pandas matplotlib numpy seaborn
```

## Uso

1. Clona este repositorio o descarga el archivo `comparativas_tiendas.py`
2. Ejecuta el script:

```bash
python comparativas_tiendas.py
```

3. Los gráficos se guardarán como archivos PNG en el directorio actual:
   - `productos_vendidos_comparativa.png`
   - `productos_calificados_comparativa.png`
   - `frecuencia_productos.png`

## Estructura de datos

El análisis se basa en los siguientes datos para cada tienda:

| Tienda | Producto Más Vendido | Producto Menos Vendido | Producto Mejor Calificado | Producto Peor Calificado | Producto Más Costoso | Producto Más Barato |
|--------|----------------------|------------------------|---------------------------|--------------------------|----------------------|---------------------|
| Tienda 1 | TV LED UHD 4K | Celular ABXY | Ajedrez de madera | Set de vasos | TV LED UHD 4K | Cubo mágico 8x8 |
| Tienda 2 | Iniciando en programación | Juego de mesa | Bicicleta | Cubertería | TV LED UHD 4K | Cubo mágico 8x8 |
| Tienda 3 | Kit de bancas | Bloques de construcción | Juego de mesa | Microondas | TV LED UHD 4K | Cubo mágico 8x8 |
| Tienda 4 | Cama box | Guitarra eléctrica | Juego de mesa | TV LED UHD 4K | TV LED UHD 4K | Cubo mágico 8x8 |

## Hallazgos principales

- El "Cubo mágico 8x8" es el producto más barato en todas las tiendas.
- El "TV LED UHD 4K" es el producto más costoso en todas las tiendas.
- El "Juego de mesa" destaca como el producto mejor calificado en dos tiendas.
- La "TV LED UHD 4K" tiene un rendimiento mixto: es el producto más vendido en la Tienda 1, pero el peor calificado en la Tienda 4.

## Personalización

Para modificar el análisis, puedes editar las variables de datos al inicio del script:

```python
tiendas = ['Tienda 1', 'Tienda 2', 'Tienda 3', 'Tienda 4']
mas_vendidos = ['TV LED UHD 4K', 'Iniciando en programación', 'Kit de bancas', 'Cama box']
menos_vendidos = ['Celular ABXY', 'Juego de mesa', 'Bloques de construcción', 'Guitarra eléctrica']
# etc...
```

## Contribuciones

Las sugerencias y mejoras son bienvenidas. Por favor, siente libre de hacer un fork del repositorio y enviar pull requests.
