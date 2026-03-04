# 🛒 Priorización de hipótesis y análisis de Test A/B en tienda online
Este proyecto tiene como objetivo optimizar los ingresos de una tienda online mediante dos enfoques:  

- Priorización de hipótesis utilizando los frameworks ICE y RICE.  
- Análisis de un test A/B para evaluar el impacto de cambios en la experiencia de usuario sobre métricas clave como ingresos, conversión y tamaño promedio de pedido.  

## 🎯 Objetivo: 
Analizar el comportamiento de usuarios, dispositivos y fuentes de marketing a lo largo del tiempo para identificar patrones de conversión, rentabilidad y retorno de inversión, con el fin de optimizar estrategias y maximizar ganancias de manera sostenible

## 💡 Enfoque:
Limpieza y análisis de datos, correlación entre ventas y reseñas, segmentación por dispositivos y fuentes de marketing, y pruebas de hipótesis para optimizar estrategias comerciales y de inversión.

## 📂 Datos
Archivos (No incluidos por temas de licencia): 
- `visits_log_us.csv`
  - `Uid`: identificador único del usuario.
  - `Device`: dispositivo del usuario.
  - `Start Ts`: fecha y hora de inicio de la sesión.
  - `End Ts`: fecha y hora de término de la sesión.
  - `Source Id`: identificador de la fuente de anuncios de la que proviene el usuario.

- `orders_log_us.csv`
  - `Uid`: identificador único del usuario que realiza un pedido.
  - `Buy Ts`: fecha y hora del pedido. Revenue: el ingreso de Showz por el pedido.

- `costs_us.csv`
  - `source_id`: identificador de la fuente de anuncios.
  - `dt`: fecha.
  - `costs`: gastos en esta fuente de anuncios en este día.

**Nota**: Todas las fechas de esta tabla están en formato AAAA-MM-DD.   

## 🛠️ Metodología
- Preparación:
  - Unificar el formarto de las columnas a letras minúsculas.
  - Conversión a tipos adecuados para fechas y datos numéricos.
  - Manipulación y tratamiento justificado de valores ausentes.

- Análisis y Calculo de Métricas: 

  - Visitas:
    - Calculo de conversión de ususarios.
    - Cálculo de sesiones por día.

  - Ventas:
    - Tiempo de conversión de usuarios.
    - Tamaño promedio de compra.

  - Marketing:
    - Gastos por fuente de publicidad.
    - Cálculo del ROMI, CAC y LTV.


## 🛠️ Tecnologías
- Lenguajes: Python
- Librerías: Pandas, NumPy, SciPy.  
- Visualización:  Matplotlib, Seaborn. 
- Entorno: Jupyter Notebook/ VS Code.


## 📈 Resultados y conclusiones
- Desktop es el dispositivo dominante en visitas, ingresos y retorno de inversión, aunque con tiempos de conversión más largos.
- Móvil presenta menor popularidad, pero evidencia un potencial no explotado gracias a conversiones más rápidas y ganancias iniciales más altas.
- El repunte de métricas inicia en agosto y se extiende por 9–10 meses, lo que sugiere una ventana estratégica para maximizar resultados.
- El análisis de ROMI por fuente de marketing indica que la mayor parte del presupuesto debe concentrarse en las tres fuentes más rentables (1, 2 y 5), mientras que las restantes requieren reevaluación o redistribución de inversión.


## 📋 Uso
- Abrir el jupyter notebook y seguir el flujo del proyecto tal y como está ordenado, yendo desde el apartado de **Descripción** hasta el apartado de **Conclusiones**.

## 📧 Contacto
Para cualquier duda, aclaración, recomendación o sugerencia por favor contactar a:

- Autor: Sebastian Vera Morales
- LinkedIn: [www.linkedin.com/in/sebastian-vera-morales]
- Correo: [sebastianvera4997@gmail.com]