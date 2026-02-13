# Introducción a la Visualización de Datos

> **Subtítulo**: Comunicando historias a través de los datos.

El arte de transformar números en decisiones. De la exploración al *storytelling* visual.

## ¿Qué es la Visualización de Datos?

Es la representación gráfica de información y datos. Al utilizar elementos visuales como cuadros, gráficos y mapas, las herramientas de visualización de datos proporcionan una manera accesible de ver y comprender tendencias, valores atípicos y patrones.

**¿Por qué es importante?**
- Simplifica relaciones complejas.
- Facilita la retención de información.
- Permite identificar anomalías rápidamente.

---

## Propósitos Principales

Según [Harvard Business Review](https://hbr.org/2016/06/visualizations-that-really-work), existen cuatro propósitos principales:

1.  **Generación de ideas**: Sesiones de "brainstorming" visual para definir problemas. Ofrece un primer acercamiento a los datos.
2.  **Ilustración de ideas**: Comunicación de tácticas, procesos y flujos de trabajo (ej. Diagramas de Gantt, gráficos en cascada).
3.  **Descubrimiento visual**: Minería de datos visual para hallar correlaciones ocultas, patrones o tendencias que difícilmente se ven a primera vista.
4.  **Visualización cotidiana**: Gráficos simples para reportes diarios de apoyo a la hora de describir datos.

---

## Tipos de Gráficas Comunes

### Básicas
1.  **Tablas y Matrices**: Ideales para comparación de valores precisos.
2.  **Barras y Torta/Dona**: Comparación de categorías y composición de un todo.
3.  **Líneas y Áreas**: Visualización de tendencias temporales y cambios en el tiempo.

### Avanzadas
4.  **Histogramas**: Distribución de una variable numérica.
5.  **Gráficas de Dispersión (Scatter Plot)**: Relación y correlación entre dos variables.
6.  **Mapas de Calor (Heatmaps)**: Intensidad de datos.
7.  **Mapas de Árbol (Treemaps)**: Jerarquías y composición.

> **Nota**: Una **infografía** es un conjunto de visualizaciones, animaciones e imágenes que busca orientar al lector hacia un tema, con poco texto y datos crudos; las imágenes hablan por sí solas.

---

## Estadios de la Visualización

El ciclo de vida en un proyecto de analítica pasa por diferentes etapas:

1.  **Exploratoria (EDA)**:
    -   *Uso*: Interno (para los analistas).
    -   *Características*: Rápida, funcional, sin adornos.
    -   *Objetivo*: Entender la distribución, detectar errores y limpiar el dataset.
2.  **Explicativa**:
    -   *Uso*: Externo (audiencia).
    -   *Características*: Curada, limpia, enfocada.
    -   *Objetivo*: Comunicar un hallazgo o "insight" (mensaje clave), eliminando ruido.
3.  **Interactiva (Dashboards)**:
    -   *Uso*: Dinámico (usuario final).
    -   *Características*: Permite filtrar y profundizar.
    -   *Objetivo*: Permitir que el usuario explore dimensiones por su cuenta (ej. Tableau, Power BI).

---

## Mejores Prácticas

Para que una visualización sea efectiva, debe cumplir con:

1.  **Contexto**: Entender qué significan los números en el mundo real para filtrar lo relevante.
2.  **Audiencia**: ¿Es para un equipo técnico o para la mesa directiva? Adapta el mensaje.
3.  **Elección Correcta**: Elegir la gráfica más apropiada (ej. no usar torta para 20 categorías).
4.  **Simplicidad (Data-Ink Ratio)**: Elimina todo elemento que no aporte información (marcos, sombras innecesarias, colores redundantes).

---

## Herramientas Open Source

### Code-Based (Python/Control Total)
-   **Seaborn**: Biblioteca basada en Matplotlib. Visualizaciones estadísticas elegantes con pocas líneas de código.
-   **Dash (by Plotly)**: Framework para crear aplicaciones web analíticas e interactivas sin necesidad de JavaScript profundo.
-   **Streamlit**: La forma más rápida de convertir scripts de Python en apps web compartibles. Muy popular en Data Science.
-   **Metabase**: Permite extenderse y conectarse fácilmente en entornos de datos para consultas rápidas.

### Low-Code/No-Code (Interfaz Gráfica)
-   **Grafana**: Especialista en series temporales y monitoreo de infraestructura/IoT en tiempo real.
-   **Apache Superset**: Herramienta de nivel empresarial para exploración y visualización. Soporta casi cualquier BD SQL y es escalable.
-   **Google Data Studio (Looker Studio)**: Versión gratuita para conectar datos de marketing y hojas de cálculo.

---

## Recursos para la Práctica

-   **[Kaggle Data Visualization Course](https://www.kaggle.com/learn/data-visualization)**: Tutoriales prácticos con Python.
-   **Makeover Monday**: Proyecto comunitario donde cada semana se mejora un gráfico existente.
-   **TidyTuesday**: Desafío semanal (R/Python) para limpiar y visualizar datos reales.

### Referencias y Lecturas Recomendadas

| Título | Autor | Por qué leerlo | Link |
| :--- | :--- | :--- | :--- |
| **Fundamentals of data visualization** | Claus O. Wilke | Conceptos claves para visualizar. | [Link](https://github.com/vishnu-u/Data-Science-Library/blob/main/Fundamentals%20of%20Data%20Visualization.pdf) |
| **The Visual Display of Quantitative Information** | Edward Tufte | Clásico sobre integridad estadística y diseño. | [Link](https://kyl.neocities.org/books/%5BTEC%20TUF%5D%20the%20visual%20display%20of%20quantitative%20information.pdf) |
| **Envisioning Information** | Edward Tufte | Presentación de datos multidimensionales. | [Link](https://eclass.uth.gr/modules/document/file.php/PRE_P_122/Edward%20R.%20Tufte%20Envisioning%20Information%201990.pdf) |
| **The Functional Art** | Alberto Cairo | Intersección entre periodismo y datos. | [Link](https://paul.zhdk.ch/pluginfile.php/93337/mod_resource/content/1/The%20Functional%20Art%20-%20An%20Introduction%20to%20Information%20Graphics%20and%20Visualization%20by%20Alberto%20Cairo%20(z-lib.org).pdf) |
| **Storytelling with Data** | Cole Nussbaumer Knaflic | Excelente para aprender qué gráficos *no* usar. | [Blog](https://www.storytellingwithdata.com/blog) |

**Sitios de Inspiración:**
- [Information is Beautiful](https://informationisbeautiful.net/) (David McCandless)
- [The Pudding](https://pudding.cool/) (Ensayos visuales)
