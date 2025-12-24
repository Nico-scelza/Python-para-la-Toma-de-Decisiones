# 🐍 Python para la Toma de Decisiones

Bienvenido a **Python para la Toma de Decisiones**, un repositorio que aloja herramientas interactivas diseñadas para facilitar el análisis cuantitativo y la resolución de problemas complejos de gestión y estrategia.

Este proyecto utiliza **Jupyter Notebooks** con interfaces gráficas (GUI) integradas, permitiendo a estudiantes y profesionales modelar problemas de **Investigación Operativa** sin necesidad de manipular el código fuente directamente.

---

## 📂 Módulos Disponibles

### 1. 📈 Optimización: Programación Lineal (`Programación Lineal.ipynb`)
Módulo enfocado en la asignación eficiente de recursos limitados para maximizar beneficios o minimizar costos.

* **Interfaz Intuitiva:** Ingreso dinámico de variables, restricciones y función objetivo.
* **Motor de Cálculo:** Utiliza el método *Highs* de `scipy.optimize` para garantizar precisión numérica.
* **Análisis Gráfico:** Generación automática de la región factible y visualización del punto óptimo (para problemas de 2 variables).
* **Tipos de Problemas:** Soporte para maximización y minimización con desigualdades mixtas ($\le, \ge, =, <, >$).

### 2. ⚖️ Estrategia: Teoría de los Juegos (`Teoria de los Juegos.ipynb`)
Laboratorio para analizar la toma de decisiones estratégicas en situaciones de conflicto o cooperación entre agentes.

* **Configuración Flexible:** Matrices de tamaño $N \times M$ personalizables para jugadores (Usuario vs. Contrincante).
* **Modelos Soportados:**
    * **Suma Cero:** Escenarios estrictamente competitivos.
    * **Suma No Cero (Bimatricial):** Escenarios generales con pagos independientes.
* **Herramientas de Decisión:**
    * Detección automática de **Estrategias Dominantes**.
    * Cálculo de criterios **MaxMin** (prudente) y **MinMax**.
    * Identificación de **Puntos de Silla** y **Equilibrios de Nash**.
    * Resolución de **Estrategias Mixtas** mediante programación lineal.
* **Visualización:** Mapas de calor (Heatmaps) para identificar patrones de pagos y mejores respuestas.

---

## 🛠️ Tecnologías Utilizadas

El proyecto aprovecha la potencia del ecosistema de ciencia de datos de Python:

* **Core:** `Python 3.x`
* **Interfaz:** `ipywidgets`, `ipysheet`
* **Cálculo Numérico:** `numpy`, `pandas`, `scipy` (Linear Programming)
* **Visualización de Datos:** `matplotlib`, `seaborn`

---

## 🚀 Instalación y Uso

Sigue estos pasos para ejecutar las herramientas en tu entorno local:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/python-para-toma-decisiones.git](https://github.com/TU_USUARIO/python-para-toma-decisiones.git)
    cd python-para-toma-decisiones
    ```

2.  **Instalar dependencias:**
    Se recomienda crear un entorno virtual antes de instalar:
    ```bash
    pip install notebook numpy pandas matplotlib seaborn scipy ipywidgets ipysheet
    ```

3.  **Iniciar Jupyter:**
    ```bash
    jupyter notebook
    ```

4.  **Ejecutar los módulos:**
    * Abre `Programación Lineal.ipynb` o `Teoria de los Juegos.ipynb`.
    * Ejecuta todas las celdas (Cell -> Run All) para cargar la interfaz gráfica.

---

Desarrollado con ❤️ y 🐍 Python.
