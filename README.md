# Proyecto Regresión

## Índice
1. [Notebook](./Regresion.ipynb)
2. [Reporte HTML](./Regresion.html)
3. [README](./README.md)

---

## Descripción
Este proyecto desarrolla un análisis de regresión con el objetivo de **predecir el resultado final de un partido de fútbol (FTResult)** utilizando exclusivamente estadísticas relacionadas con faltas, tarjetas y corners. Estas variables son:

- HomeFouls  
- AwayFouls  
- HomeCorners  
- AwayCorners  
- HomeYellow  
- AwayYellow  
- HomeRed  
- AwayRed  

El objetivo central es evaluar si esta información, sin utilizar goles, probabilidades de apuestas o métricas directamente relacionadas con el marcador, permite anticipar si el resultado será:

- **H** → Gana el equipo local  
- **D** → Empate  
- **A** → Gana el equipo visitante  

El análisis incluye:

- Exploración del dataset.  
- Manejo de problemas típicos en calidad de datos.  
- Selección de características.  
- Entrenamiento de un modelo lineal (Logistic Regression) y uno no lineal (Random Forest).  
- Evaluación del desempeño mediante métricas de clasificación y validación cruzada.  
- Análisis de inferencia con márgenes de error.

*Nota: No se incluye el .csv del dataset utilizado ya que el tamaño es muy pesado para GitHub.*
