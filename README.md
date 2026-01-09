# 📊 Clasificación de Hongos: Rigurosidad Estadística y Desafío de Supuestos

[![Reporte en HTML](https://img.shields.io/badge/VER_REPORTE_INTERACTIVO-HTML-blue?style=for-the-badge&logo=html5)](https://alej2andro.github.io/Mushroom-Classification-Bernoulli-Naive-Bayes-vs-K-Nearest-Neighbors-Algorithms/)
[![RPubs](https://img.shields.io/badge/Portafolio-RPubs-orange?style=for-the-badge&logo=r)](https://rpubs.com/Alej5ndro)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/alejandrofigueroarojas)
[![Email](https://img.shields.io/badge/Email-Contacto-D14836?style=for-the-badge&logo=gmail)](mailto:alejandro.figueroa,rojas@gmail.com)

---

## 🔍 Filosofía y Enfoque
Mi aproximación a la **Ciencia de Datos** no se limita a la ejecución de algoritmos "caja negra". Mi trabajo se basa en la **rigurosidad matemática** y el estudio profundo de la naturaleza de los datos. Creo firmemente que la eficacia de un modelo reside en el respeto a sus supuestos y en la disciplina del análisis exploratorio.

> *"Un modelo no es solo una predicción, es una hipótesis sobre la estructura del mundo."*

## 🍄 Resumen del Proyecto: Bernoulli NB vs. KNN
Este proyecto analiza la separabilidad de clases (Comestible vs. Venenoso) en un dataset de hongos, contrastando dos paradigmas algorítmicos distintos para evaluar cómo la estructura de los datos afecta el rendimiento del modelo.

### 🔬 Puntos Clave del Análisis:
* **Diagnóstico de Supuestos**: Evaluación crítica de la **independencia condicional** requerida por Naive Bayes. A través de una matriz de correlaciones avanzada, identifico violaciones severas (correlaciones de hasta 0.848) que explican las limitaciones predictivas del modelo.
* **Matriz de Separabilidad**: Implementación de visualizaciones complejas en `ggplot2` para analizar la distribución bimodal y la estructura discreta de las variables más discriminantes.
* **Contraste de Paradigmas**:
    * **Bernoulli Naive Bayes**: Evaluado bajo la óptica de la probabilidad condicional y la distribución de Bernoulli.
    * **K-Nearest Neighbors (KNN)**: Utilizado para capturar la geometría local y las interacciones que Naive Bayes ignora por diseño.
* **Optimización y Validación**: Uso de validación cruzada (10-fold CV) para asegurar la robustez de las métricas de desempeño y evitar el sobreajuste.

## 🛠️ Stack Técnico
* **Lenguaje**: R (Tidyverse, Caret, GGally, ggplot2).
* **Disciplina Matemática**: Estadística Bayesiana, Probabilidad Condicional, Geometría de Datos.
* **Documentación**: RMarkdown para la creación de reportes científicos reproducibles y dinámicos.

---

## 📈 Conclusión Técnica
El modelo Naive Bayes alcanzó un **94.09% de accuracy**. Sin embargo, el análisis profundo revela que este éxito es parcial: la violación del supuesto de independencia genera **51 falsos negativos**. Este proyecto documenta empíricamente por qué la estructura de dependencias en los atributos morfológicos requiere modelos que capturen interacciones complejas, como KNN, el cual logra corregir estas desviaciones.

---

**Alejandro Figueroa Rojas** *Comprometido con la precisión analítica y la disciplina en la ciencia de datos.*

---

### Acceso al Proyecto
1. **Explorar el código**: El archivo `Bernoullinb.Rmd` contiene el flujo de trabajo completo.
2. **Visualizar Reporte**: [Haz clic aquí para ver el análisis renderizado en HTML](https://alej2andro.github.io/Mushroom-Classification-Bernoulli-Naive-Bayes-vs-K-Nearest-Neighbors-Algorithms/).
