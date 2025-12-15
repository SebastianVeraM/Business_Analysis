# 🛒 Priorización de hipótesis y análisis de Test A/B en tienda online

## 📖 Descripción del proyecto
Este proyecto tiene como objetivo optimizar los ingresos de una tienda online mediante dos enfoques:  

1. Priorización de hipótesis utilizando los frameworks ICE y RICE.  
2. Análisis de un test A/B para evaluar el impacto de cambios en la experiencia de usuario sobre métricas clave como ingresos, conversión y tamaño promedio de pedido.  

---

## 📂 Descripción de los datos

Parte 1: Priorización de hipótesis
Archivo: /datasets/hypotheses_us.csv  
- Hypotheses → descripción breve de la hipótesis.  
- Reach → alcance de usuarios (escala 1–10).  
- Impact → impacto esperado en usuarios (escala 1–10).  
- Confidence → nivel de confianza en la hipótesis (escala 1–10).  
- Effort → recursos necesarios para probar la hipótesis (escala 1–10).  

Parte 2: Análisis del test A/B
Archivos:  
- /datasets/orders_us.csv  
  - transactionId → identificador del pedido.  
  - visitorId → identificador del usuario.  
  - date → fecha del pedido.  
  - revenue → ingresos del pedido.  
  - group → grupo del test A/B (A o B).  

- /datasets/visits_us.csv  
  - date → fecha.  
  - group → grupo del test A/B.  
  - visits → número de visitas por grupo y fecha.  

> ⚠️ Nota: Es necesario realizar preprocesamiento de datos para corregir errores, como usuarios que aparecen en ambos grupos de prueba.  

---

## 🛠️ Etapas del proyecto

1. Priorización de hipótesis
- Aplicar el framework ICE → ordenar hipótesis por prioridad.  
- Aplicar el framework RICE → ordenar hipótesis por prioridad.  
- Comparar resultados entre ICE y RICE → explicar diferencias y cambios en la priorización.  

2. Análisis del test A/B
1. Gráfico de ingresos acumulados por grupo.  
2. Gráfico del tamaño promedio de pedido acumulado por grupo.  
3. Diferencia relativa en el tamaño promedio de pedido (B vs. A).  
4. Tasas de conversión diarias por grupo.  
5. Gráfico de dispersión del número de pedidos por usuario.  
6. Percentiles 95 y 99 de pedidos por usuario → detección de anomalías.  
7. Gráfico de dispersión de precios de pedidos.  
8. Percentiles 95 y 99 de precios de pedidos → detección de anomalías.  
9. Prueba de significancia estadística en la conversión (datos brutos).  
10. Prueba de significancia estadística en el tamaño promedio de pedido (datos brutos).  
11. Prueba de significancia estadística en la conversión (datos filtrados).  
12. Prueba de significancia estadística en el tamaño promedio de pedido (datos filtrados).  
13. Decisión final:  
   - Parar la prueba y declarar un grupo líder.  
   - Parar la prueba y concluir que no hay diferencia.  
   - Continuar la prueba.  

---

## 📊 Herramientas utilizadas
- Python → Pandas, NumPy, Matplotlib, Seaborn, SciPy.  
- Jupyter Notebook → análisis exploratorio y visualización.  
- Estadística → pruebas de hipótesis, percentiles, detección de anomalías.  

---

## ✅ Resultados esperados
- Priorización clara de hipótesis para maximizar impacto con menor esfuerzo.  
- Evaluación rigurosa del test A/B con métricas clave de negocio.  
- Conclusiones basadas en evidencia estadística para apoyar decisiones estratégicas.

---

## Contacto 
