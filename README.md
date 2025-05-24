# 🛢️ Selección de Regiones para Nuevos Pozos Petroleros — OilyGiant

Este proyecto tiene como objetivo identificar las **mejores ubicaciones para perforar 200 nuevos pozos petroleros**, utilizando datos históricos de producción de tres regiones distintas. Se aplicaron técnicas estadísticas y de modelado predictivo para evaluar el rendimiento económico esperado y minimizar los riesgos asociados a la inversión.

---

## 🎯 Objetivo

Determinar la región óptima para invertir en nuevos pozos petroleros considerando:

- **Rentabilidad promedio esperada**
- **Intervalos de confianza del 95%**
- **Riesgo de pérdidas**

---

## ⚙️ Descripción del Proyecto

El análisis se llevó a cabo mediante los siguientes pasos:

- **Exploración de datos:** Análisis de los parámetros técnicos y de producción de pozos en tres regiones.
- **Modelado predictivo:** Entrenamiento de un modelo de **regresión lineal** para estimar el volumen de petróleo extraído por pozo.
- **Análisis estadístico con Bootstrapping:**
  - Simulación de 1,000 iteraciones para cada región.
  - Estimación del **ingreso promedio esperado** al invertir en 200 pozos.
  - Cálculo del **intervalo de confianza al 95%** para cada estimación.
  - Evaluación del **riesgo financiero**, definido como la probabilidad de obtener ganancias por debajo del punto de equilibrio.

---

## ✅ Resultados

- **Riesgo de pérdida:** 0% en las tres regiones, lo que indica una **baja exposición financiera**.
- **Región recomendada:** **Región 0**, destacada por:
  - El **mayor ingreso promedio esperado**.
  - Un **intervalo de confianza más alto**, con ingresos proyectados que podrían superar los **$132 millones USD** con un 95% de probabilidad.
- El análisis reveló que **la estabilidad del ingreso promedio es más relevante que los valores máximos posibles**, lo cual respalda decisiones más estratégicas y sostenibles.

---

## 📌 Conclusión

A pesar de que todas las regiones presentan un riesgo bajo, los análisis realizados concluyen que **la Región 0 ofrece la mejor combinación de rentabilidad y consistencia**. Esta recomendación proporciona una base sólida para una inversión eficiente en la expansión operativa de OilyGiant, maximizando el retorno esperado y minimizando la volatilidad de los resultados.

---

## 🧠 Tecnologías y Herramientas

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Bootstrapping (técnica de remuestreo)

---

## 👤 Autor

**César Eduardo Cruz Cabrera**  
📧 cesareduardocruzcabrera@gmail.com  
💼 [LinkedIn - César Eduardo Cruz Cabrera](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)
