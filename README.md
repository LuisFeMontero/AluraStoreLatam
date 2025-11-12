# 📊 Análisis de Datos: AluraStore Latam



[![Python Badge](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Pandas Badge](https://img.shields.io/badge/Pandas-2.0-green.svg)](https://pandas.pydata.org/)
[![Matplotlib Badge](https://img.shields.io/badge/Matplotlib-3.7-orange.svg)](https://matplotlib.org/)
[![Seaborn Badge](https://img.shields.io/badge/Seaborn-0.12-purple.svg)](https://seaborn.pydata.org/)
[![License Badge](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## Índice

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Estado del Proyecto](#estado-del-proyecto)
- [Análisis Realizados](#análisis-realizados)
- [Acceso al Proyecto](#acceso-al-proyecto)
- [Ejecución del Proyecto](#ejecución-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Personas Contribuyentes](#personas-contribuyentes)
- [Licencia](#licencia)

---

## Descripción del Proyecto

**AluraStore Latam** es un proyecto de Análisis Exploratorio de Datos (EDA) que evalúa el rendimiento de cuatro tiendas de comercio electrónico (Tienda 1, 2, 3 y 4). El objetivo principal es analizar métricas clave de rendimiento, comparar las tiendas e identificar patrones para generar un informe estratégico que ayude a la toma de decisiones (en este caso, determinar qué tienda sería la más indicada para una venta).

Este proyecto fue desarrollado como parte del desafío de Data Science del programa **Oracle Next Education (ONE) G9**, en colaboración con Alura Latam.

### Métricas Analizadas:
- Facturación total (Ingresos).
- Ventas por categoría de producto.
- Calificación promedio y satisfacción del cliente.
- Productos más y menos vendidos.
- Eficiencia operativa (Costos de envío).
- Distribución geográfica de las ventas.

## Estado del Proyecto

El proyecto está **finalizado**. El análisis de datos, la generación de visualizaciones y el informe de recomendación estratégica han sido completados.

## Análisis Realizados

- **1. Análisis de Facturación**:
  Cálculo y comparación de los ingresos totales generados por cada tienda.

- **2. Ventas por Categoría**:
  Desglose de la cantidad de ventas por cada categoría de producto para entender el mix de productos de cada tienda.

- **3. Calificación Promedio**:
  Medición de la satisfacción del cliente a través de la calificación promedio de cada tienda.

- **4. Productos Más y Menos Vendidos**:
  Identificación del Top 5 y Bottom 5 de productos para cada tienda, revelando los "productos estrella" y aquellos con baja rotación.

- **5. Costo de Envío Promedio**:
  Análisis de la eficiencia logística y costos operativos mediante el cálculo del costo de envío promedio.

- **6. Visualización Comparativa**:
  Generación de gráficos de barras (Ingresos), circulares (Categorías) y de dispersión (Costo vs. Calificación) para facilitar la comparación visual.

- **7. Análisis Geográfico**:
  Mapeo de la huella de ventas, ingresos y calificaciones usando coordenadas de latitud y longitud para identificar clusters geográficos.

- **8. Informe Estratégico**:
  Un informe final que sintetiza todos los hallazgos y provee una recomendación justificada sobre qué tienda vender para maximizar el capital.

---

## Acceso al Proyecto

Puedes clonar el repositorio desde GitHub para obtener una copia local del script de análisis.

```bash
git clone [https://github.com/](https://github.com/LuisFeMontero)[LuisFeMontero]/AluraStoreLatam.git
cd AluraStoreLatam
```
## Ejecución del Proyecto

Este proyecto es un script de Python, idealmente ejecutado en un entorno como Google Colab o un Jupyter Notebook local.

1.  **Instalar dependencias**:
    Asegúrate de tener las bibliotecas necesarias instaladas.

    ```bash
    pip install pandas matplotlib seaborn
    ```

2.  **Ejecutar el script**:
    Puedes ejecutar el archivo [`alurastorelatam.py`](AluraStoreLatam.py) directamente o, preferiblemente, cargar el contenido en un notebook (como Google Colab) para ejecutar cada celda de análisis y ver las visualizaciones generadas.

    El script carga los datos directamente desde los URLs de GitHub, por lo que no se necesita descargar archivos CSV manualmente.

## Tecnologías Utilizadas

- **Python 3.10+**:
  Lenguaje principal utilizado para todo el análisis de datos.

- **Pandas**:
  Biblioteca fundamental para la ingesta, limpieza, manipulación y análisis de los DataFrames.

- **Matplotlib**:
  Usada para la creación de visualizaciones estáticas, principalmente los gráficos circulares.

- **Seaborn**:
  Biblioteca basada en Matplotlib para crear visualizaciones estadísticas más atractivas y complejas (gráficos de barras, dispersión y geo-localización).

- **Google Colab (o Jupyter)**:
  Entorno de notebook utilizado para el desarrollo interactivo del análisis.

## Personas Contribuyentes

Este proyecto ha sido desarrollado por Luis Felipe Montero como parte del proceso de aprendizaje y práctica en Data Science dentro del programa **Oracle Next Education (ONE) G9**, con el apoyo de Alura Latam.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [`LICENSE`](LICENSE.txt) para más detalles.

¡Gracias por explorar este análisis de AluraStore! 😊