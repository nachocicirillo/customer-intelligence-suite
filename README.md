# customer-intelligence-suite

# 🎯 Customer Intelligence Suite: AI & Analytics

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![AI](https://img.shields.io/badge/AI-KMeans%20Clustering-orange)
![Viz](https://img.shields.io/badge/Visualization-Plotly-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Descripción del Proyecto

Este proyecto es una solución **End-to-End de Inteligencia de Negocios e Inteligencia Artificial**. Su objetivo es transformar datos transaccionales crudos de un E-commerce en estrategias de marketing automatizadas y accionables.

Como **Ingeniero de IA y Administrador**, diseñé este sistema para resolver el problema clásico: *"Tengo muchos datos de ventas, pero no sé cómo fidelizar a mis clientes"*.

El sistema utiliza **Machine Learning No Supervisado (K-Means)** para segmentar matemáticamente la base de clientes y **Prompt Engineering Programático** para generar estrategias de comunicación personalizadas.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python 3.
* **Data Processing:** Pandas, NumPy (ETL y manipulación vectorial).
* **Machine Learning:** Scikit-Learn (K-Means Clustering, StandardScaler).
* **Visualización:** Plotly (Gráficos interactivos 3D, Radar Charts y Treemaps).
* **GenAI Integration:** Lógica de Prompt Engineering dinámico.

---

## 🔄 Pipeline del Proyecto

El flujo de trabajo consta de 5 notebooks modulares:

### 1. `1_generacion_datos.ipynb` (ETL)
Simulación de 10,000 transacciones con distribuciones estadísticas reales (Pareto y Log-Normal) para emular el comportamiento humano de compra.

### 2. `2_analisis_rfm.ipynb` (Feature Engineering)
Transformación de transacciones en una Matriz de Comportamiento RFM:
* **Recency:** Días desde la última compra.
* **Frequency:** Frecuencia de compra.
* **Monetary:** Total gastado (LTV).

### 3. `3_clustering_ia.ipynb` (Modelado)
Entrenamiento de un modelo **K-Means** para agrupar clientes similares sin etiquetas previas. Se aplicó normalización y transformación logarítmica para manejar *outliers* financieros.

### 4. `4_visualizacion.ipynb` (Business Intelligence)
Creación de dashboards interactivos para la toma de decisiones:
* **Radar Chart:** Comparativa de perfiles.
* **Treemap:** Mapa de calor financiero.
* **3D Scatter Plot:** Exploración espacial de segmentos.

### 5. `5_estrategia_ia.ipynb` (Agente de Estrategia)
Un motor lógico que traduce los clústeres numéricos en **Prompts de Marketing**, listos para ser enviados a un LLM (GPT-4/Claude) para redactar correos personalizados masivos.

---

## 📊 Hallazgos de Negocio

El algoritmo detectó automáticamente 4 arquetipos de clientes:

| Segmento | Perfil Detectado | Acción Estratégica Automática |
| :--- | :--- | :--- |
| **Champions (VIP)** | Alto Gasto, Frecuencia Alta | **Exclusividad:** Acceso anticipado, sin descuentos. |
| **En Riesgo** | Alta Recencia (>100 días) | **Win-Back:** Descuento agresivo por urgencia. |
| **Nuevos** | Baja Frecuencia, Reciente | **Nurturing:** Contenido educativo para generar hábito. |
| **Leales** | Promedio constante | **Upselling:** Recomendación de complementarios. |

---

## ⚙️ Instalación y Uso

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/customer-intelligence-suite.git](https://github.com/tu-usuario/customer-intelligence-suite.git)
    ```

2.  **Crear entorno virtual e instalar dependencias:**
    ```bash
    # En Windows
    python -m venv venv
    venv\Scripts\activate
    pip install pandas numpy scikit-learn plotly matplotlib seaborn nbformat ipykernel
    ```

3.  **Ejecutar los notebooks en orden numérico (1 al 5).**

---

## 👨‍💻 Autor

**Ignacio Cicirillo**
*Aficionado a la IA & Administrador de Empresas*

[LinkedIn]([https://www.linkedin.com/in/tu-perfil](https://www.linkedin.com/in/ignacio-cicirillo-2929678b/))
