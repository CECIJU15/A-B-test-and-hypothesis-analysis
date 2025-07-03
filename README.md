# 📊 Proyecto: A/B Test y Análisis de Hipótesis

## 📌 Descripción

Este proyecto se enmarca en una tienda online que busca optimizar sus ingresos mediante la evaluación y priorización de hipótesis generadas por el equipo de marketing. Además, se realiza un análisis de un experimento A/B para validar estadísticamente el impacto de posibles cambios en la experiencia del usuario o estrategias comerciales.

## 🎯 Objetivos

- Evaluar y priorizar hipótesis utilizando frameworks como ICE y RICE.
- Analizar los resultados de un test A/B para identificar diferencias significativas entre los grupos.
- Apoyar la toma de decisiones estratégicas con base en datos reales.

## 📂 Dataset Utilizado

1. `hypotheses_us.csv`: Contiene descripciones de hipótesis y sus puntuaciones según criterios como alcance, impacto, confianza y esfuerzo.
2. `orders_us.csv`: Información de pedidos, ingresos, usuarios y grupo de test A/B.
3. `visits_us.csv`: Registra las visitas diarias al sitio web por grupo de prueba.

## 🛠 Tecnologías y Librerías

- Python
- Pandas
- Matplotlib 
- NumPy
- SciPy

## 📈 Análisis realizados

- Aplicación de los frameworks ICE (Impact, Confidence, Effort) y RICE (Reach, Impact, Confidence, Effort) para ordenar hipótesis según su potencial y factibilidad.
- Aplicación de pruebas estadísticas para determinar: Si las diferencias entre los grupos A y B en ingresos, tasa de conversión y valor promedio del pedido son estadísticamente significativas.
- Prueba de hipótesis (U de Mann-Whitney)

## 📊 Visualizaciones

- Gráficos de líneas : Para mostrar ingresos acumulados , tamaño de pedido promedio acumulado y tasas de conversión diarias.
- Gráfico de dispersión del número de pedidos por usuario y precios de los pedidos.

## ✅ Conclusiones

-Prioriza las hipótesis con alto RICE, ya que este framework toma en cuenta el alcance del cambio, lo cual es crucial en estrategias escalables.
-Parar la prueba y concluir que no hay diferencia entre los grupos.

## 📁 Estructura del proyecto

```plaintext
📦 ab-test-hypothesis-analysis  
├── data/                # Archivos CSV originales  
├── ab_test.ipynb        # Análisis completo en Jupyter Notebook  
├── README.md            # Este archivo  
```

## 👤 Autor

**Cecilia Juliana Ruiz Carhuamaca**  
Estudiante de análisis de datos en TripleTen  


