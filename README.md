# ml-heart-disease-prediction
Trabajo final del curso de Data Science (UTN FRBA). Como estudiante de Bioingeniería, desarrollé un modelo de machine learning para predecir enfermedades cardíacas usando parámetros médicos. Incluye análisis exploratorio, entrenamiento del modelo y evaluación de resultados, con enfoque en aplicaciones prácticas en salud.

## **Heart Disease Prediction Project**
### **Descripción**:
Este proyecto es el trabajo final del curso de Data Science dictado por la UTN FRBA. Como estudiante avanzado de Bioingeniería, desarrollé un modelo de machine learning que predice la presencia de enfermedades cardíacas a partir de parámetros médicos relevantes. Este repositorio incluye el análisis exploratorio de datos, el entrenamiento y evaluación del modelo, y las conclusiones obtenidas con un enfoque en aplicaciones prácticas para la salud.

### Tabla de Contenidos
- Descripción del problema
- Objetivo
- Datos
- Metodología
- Resultados
- Conclusiones
- Propuestas de implementación
- Requisitos
- Uso

### Descripción del problema
Las enfermedades cardíacas son una de las principales causas de mortalidad en el mundo. Este proyecto busca explorar cómo el uso de herramientas de ciencia de datos puede contribuir a su detección temprana y mejorar las decisiones médicas basadas en datos.

### Objetivo
Desarrollar un modelo de clasificación que prediga la probabilidad de enfermedad cardíaca basándose en parámetros médicos clave, utilizando técnicas de aprendizaje supervisado.

### Datos
Se utilizó un conjunto de datos que incluye variables clínicas de pacientes:

- Variables predictoras: Edad, sexo, tipo de dolor de pecho, presión arterial en reposo, colesterol, frecuencia cardíaca máxima, entre otras.
- Variable objetivo: Indicador binario que refleja la presencia o ausencia de enfermedad cardíaca.
El dataset fue preprocesado para identificar y tratar valores atípicos y preparar las características para el modelo.

### Metodología
- *Exploración de datos*: Análisis inicial, generación de gráficos y análisis estadístico.
- Preprocesamiento*: Manejo de valores atípicos y selección de características relevantes.
- *Entrenamiento del modelo*: Utilización de Random Forest como algoritmo principal.
- *Evaluación del modelo*: Medición del desempeño con una matriz de confusión, precisión, recall, f1-score y accuracy.

### Resultados
El modelo alcanzó una precisión del 81%. Destacó su capacidad para identificar correctamente casos sin enfermedad cardíaca, aunque mostró un menor desempeño en la clasificación de casos positivos de enfermedad. Este balance sugiere que el modelo podría ser útil como herramienta de apoyo, pero no como único criterio de diagnóstico.

### Conclusiones
Los resultados demuestran el potencial de machine learning para identificar patrones asociados a enfermedades cardíacas, aunque es necesario mejorar la sensibilidad del modelo para detectar casos positivos. Esto podría lograrse ampliando el dataset, ajustando hiperparámetros o explorando nuevos algoritmos.

### Propuestas de implementación
- Incorporar el modelo como parte de un sistema de apoyo a decisiones médicas en instituciones de salud.
- Integrar el modelo en dispositivos de monitoreo de pacientes para alertas tempranas.
- Usar los hallazgos del proyecto como base para investigaciones futuras que incluyan más datos clínicos.

### Requisitos
Python 3.7+
Bibliotecas:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Uso
Clona este repositorio:
- Copiar código: git clone https://github.com/MatiasGaggiamo/ml-heart-disease-prediction.git  

### Créditos
Este proyecto fue desarrollado por Matias Andres Gaggiamo como parte del trabajo final del curso de Data Science dictado por la UTN FRBA.
