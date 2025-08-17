# Identificación de Operadores Ineficaces en Telecomunicaciones

Este análisis se enfoca en detectar operadores ineficaces dentro del servicio de telefonía virtual CallMeMaybe, utilizando datos de llamadas entrantes, salientes e internas. 

## 🎯 Objetivo  
Identificar operadores ineficaces en telecomunicaciones mediante análisis de datos de llamadas.

## 🧠 Hipótesis  
1. Operadores con mayor tasa de abandono ofrecen menor calidad de servicio.  
2. Clientes con baja frecuencia de pagos muestran menor satisfacción.  
3. Baja interacción con servicios adicionales se asocia a menor eficiencia operativa.

## 🧪 Metodología  
**1. Datasets:**  
Clientes corporativos que gestionan llamadas entrantes, salientes e internas a través de la red CallMeMaybe.

**2. Preprocesamiento:**  
- Eliminación de duplicados  
- Conversión de tipos de datos  
- Limpieza de valores ausentes

**3. Análisis exploratorio:**  
- Duración de llamadas  
- Comparación entre llamadas internas vs externas  
- Tasa de llamadas perdidas por operador

**4. Pruebas estadísticas:**  
- T-test  
- Chi-cuadrado  
- ANOVA

## 📌 Hallazgos Clave  

**🔹 Distribución de duración de llamadas:**  
La mayoría de las llamadas duran menos de 20,000 segundos. A medida que la duración aumenta, la frecuencia disminuye drásticamente.

**🔹 Llamadas internas vs externas:**  
- Internas: 12.8%  
- Externas: 87.2%  
La mayoría de las interacciones se realizan fuera de la red interna.

**🔹 Operadores con más llamadas perdidas:**  
El operador con ID `891410` lidera en llamadas fallidas (~120), seguido por `885876` y `891414`, lo que indica diferencias claras en eficiencia.

## 📊 Dashboard Interactivo
Explora el dashboard completo aquí 👉 ([https://public.tableau.com/views/tu_dashboard_id](https://public.tableau.com/app/profile/priscila.campos.gonz.lez/viz/Book1_17457832031900/Dashboard2))

## 💯 Pruebas Estadísticas  
**Chi-cuadrado:**  
- Estadístico: 346.98  
- p-valor: 1.93  
Existe relación significativa entre tipo de llamada y tasa de abandono.

**ANOVA:**  
- Estadístico: 74.93  
- p-valor: 3.25  
Diferencias significativas en tiempos de espera según tasa de abandono.

## ✅ Conclusiones  
- Los operadores con más llamadas perdidas tienen mayores tiempos de espera.  
- Hay relación entre tipo de llamada y abandono.  
- Clientes con mayor frecuencia de pagos registran más llamadas perdidas.

## 💡 Recomendaciones  

**1. Optimización de tiempos de espera:**  
Asignar recursos a operadores con sobrecarga y alto abandono.

**2. Mejora en calidad del servicio:**  
Incentivar uso de servicios adicionales y ajustar estrategias de retención.

**3. Fortalecimiento de infraestructura interna:**  
Rediseñar flujos de atención y mejorar gestión de llamadas internas.

## 🌟 Aclaraciones  
Este proyecto incluye comentarios de revisión realizados por tutores y revisores durante mi formación como analista de datos. Fueron fundamentales para refinar tanto el enfoque analítico como la interpretación de resultados.
