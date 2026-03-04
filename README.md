# 🛒 Priorización de hipótesis y análisis de Test A/B en tienda online
Este proyecto tiene como objetivo optimizar los ingresos de una tienda online mediante dos enfoques:  

1. Priorización de hipótesis utilizando los frameworks ICE y RICE.  
2. Análisis de un test A/B para evaluar el impacto de cambios en la experiencia de usuario sobre métricas clave como ingresos, conversión y tamaño promedio de pedido.  

## 🎯 Objetivo: 
Analizar el comportamiento de usuarios, dispositivos y fuentes de marketing a lo largo del tiempo para identificar patrones de conversión, rentabilidad y retorno de inversión, con el fin de optimizar estrategias y maximizar ganancias de manera sostenible

## 💡 Enfoque:
Limpieza y análisis de datos, correlación entre ventas y reseñas, segmentación por dispositivos y fuentes de marketing, y pruebas de hipótesis para optimizar estrategias comerciales y de inversión.

## 📂 Datos

Archivos: 
- hypotheses_us.csv  
  - `Hypotheses` → descripción breve de la hipótesis.  
  - `Reach` → alcance de usuarios (escala 1–10).  
  - `Impact` → impacto esperado en usuarios (escala 1–10).  
  - `Confidence` → nivel de confianza en la hipótesis (escala 1–10).  
  - `Effort` → recursos necesarios para probar la hipótesis (escala 1–10).  

- orders_us.csv  
  - `transactionId` → identificador del pedido.  
  - `visitorId` → identificador del usuario.  
  - `date` → fecha del pedido.  
  - `revenue` → ingresos del pedido.  
  - `group` → grupo del test A/B (A o B).  

- visits_us.csv  
  - `date` → fecha.  
  - `group` → grupo del test A/B.  
  - `visits` → número de visitas por grupo y fecha.   

---

## 🛠️ Metodología

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

## 🛠️ Tecnologías
- Lenguajes: Python
- Librerías: Pandas, NumPy, SciPy.  
- Visualización:  Matplotlib, Seaborn. 
- Entorno: Jupyter Notebook/ VS Code.


## 📈 Resultados y conclusiones
- Priorización clara de hipótesis para maximizar impacto con menor esfuerzo.  
- Evaluación rigurosa del test A/B con métricas clave de negocio.  
- Conclusiones basadas en evidencia estadística para apoyar decisiones estratégicas.

## 📋 Uso
- Abrir el jupyter notebook y seguir el flujo del proyecto tal y como está ordenado, yendo desde el apartado de **Descripción** hasta el apartado de **Conclusiones**.

## 📧 Contacto
Para cualquier duda, aclaración, recomendación o sugerencia por favor contactar a:

- Autor: Sebastian Vera Morales
- LinkedIn: [www.linkedin.com/in/sebastian-vera-morales]
- Correo: [sebastianvera4997@gmail.com]