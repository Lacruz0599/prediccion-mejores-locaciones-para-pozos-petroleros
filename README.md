# Selección de Regiones para Nuevos Pozos Petroleros — OilyGiant

Este proyecto tiene como objetivo encontrar las mejores ubicaciones para abrir **200 nuevos pozos petroleros**, utilizando datos históricos de tres regiones diferentes. Se desarrolló un modelo para evaluar el rendimiento potencial de cada región en términos de ingresos brutos, riesgos financieros y consistencia, utilizando técnicas estadísticas como **bootstrapping**.

## 🎯 Objetivo

Determinar la región óptima para construir nuevos pozos petroleros, considerando la rentabilidad promedio, los intervalos de confianza y el riesgo de pérdida.

## ⚙️ Descripción del Proyecto

- Se analizan datos de producción de tres regiones con parámetros técnicos de cada pozo.
- Se entrena un modelo de regresión para estimar el volumen de petróleo extraído por pozo.
- Se aplica la técnica de **bootstrapping** para:
  - Calcular el **ingreso promedio esperado** por región.
  - Determinar el **intervalo de confianza del 95%**.
  - Estimar el **riesgo de pérdidas**.

## ✅ Resultados

- **Riesgo de pérdida del 0%** en las tres regiones, lo cual implica una baja exposición financiera.
- La **Región 0** destaca con:
  - El **mayor ingreso promedio**.
  - Un **intervalo de confianza superior**, con ingresos que podrían alcanzar **más de 132 millones de dólares** con un 95% de probabilidad.
- Se identificó que centrarse únicamente en la ganancia máxima puede ser engañoso. La consistencia en los ingresos promedio es un factor más confiable para tomar decisiones estratégicas.

## 🔍 Conclusión

Aunque cualquiera de las regiones representa una opción viable, **la Región 0 se posiciona como la más favorable** para la inversión en nuevos pozos. Esta recomendación se basa en su alto rendimiento promedio y la baja variabilidad esperada, optimizando así la probabilidad de éxito del proyecto y reduciendo los riesgos de resultados extremos.

---

📌 _Este proyecto fue desarrollado como parte de mi formación en Ciencia de Datos, empleando técnicas de modelado predictivo y análisis estadístico con Python._

## 📬 Contacto

**César Eduardo Cruz Cabrera**  
📧 cesar.eduardo.cruz.cabrera@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)

---
