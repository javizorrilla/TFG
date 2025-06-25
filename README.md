# TFG - OPTIMIZACIÓN PERSONALIZADA DE LAS DINÁMICAS LABORALES PARA LOS TRABAJADORES

👦🏻 Javier Zorrilla Serrano

#### 📍Descripción 
Desarrollo e implementación de dos modelos de redes neuronales profundas totalmente conectadas (FC-DNN), uno predictivo y otro de clasificación, mediante el uso de Python, junto con las librerías de TensorFlow y Keras, claves para el aprendizaje profundo.

#### 🎯Objetivos
- Modelo de regresión: Estimación de las variables continuas: “Satisfacción en actual trabajo”, “Productividad en actual trabajo” y “Valoración general del teletrabajo”, con el objetivo de obtener predicciones precisas sobre estos aspectos en cada una de las dinámicas laborales presentes en cada individuo, siendo este análisis necesario por la falta de valores continuos en estas variables, dado que la encuesta inicialmente carecía  de ellas y, posteriormente, se incluyeron en el estudio.  
  
- Modelo de clasificación: Se realiza en dos etapas. En primer lugar, se implementan reglas específicas para reducir la incertidumbre y asignar con certeza los casos que presentan características claras. A continuación, basado en los patrones identificados, el modelo clasifica a los individuos en una de las tres modalidades laborales más pertinentes. Esta tarea es fundamental porque permite agrupar a los trabajadores en dinámicas laborales específicas, al combinar el uso de reglas con el posterior análisis de relaciones profundas que permiten ubicar a los trabajadores en el entorno que mejor se adapta a sus necesidades.

#### 🗂️Archivos dentro del repositorio
- 💻Dos modelos diseñados de regresión y clasificación.
- 📊Archivos Excel donde se almacena la información de cada apartado correspondiente dentro de los modelos realizados. Además, el archivo con nombre "Trabajo_ Remoto vs Presencial (respuestas).xlsx" es el que contiene todas las respuestas de los encuestados y con el que se trabaja para preprocesar los datos, entrenar el modelo, etc.

#### 🖥Recursos empleados
- Sistema Operativo: Windows 11.
- RAM: 16GB, aunque con una de 8GB valdría.
- Lenguaje de programación: Python 3.9.7.
- IDE: Jupyter Notebook.
