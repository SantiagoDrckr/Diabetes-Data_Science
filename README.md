# Predicción de Diabetes utilizando el Conjunto de Datos de los Indios Pima

Este proyecto tiene como objetivo desarrollar un modelo predictivo para diagnosticar la diabetes en pacientes utilizando el conjunto de datos de los Indios Pima del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales.

## Pima Indians Diabetes Database

Este conjunto de datos proviene del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales. El objetivo del conjunto de datos es predecir de forma diagnóstica si un paciente tiene diabetes o no, basándose en ciertas mediciones de diagnóstico incluidas en el conjunto de datos. Se impusieron varias restricciones a la selección de estas instancias de una base de datos más grande. En particular, todos los pacientes aquí son mujeres de al menos 21 años de edad de ascendencia india Pima.

### Pima Indians Diabetes Database

| Columna                   | Tipo    | Descripción                                             |
|---------------------------|---------|---------------------------------------------------------|
| Pregnancies               | int64   | Número de veces embarazada                              |
| Glucose                   | int64   | Concentración de glucosa en plasma a 2 horas en una prueba de tolerancia a la glucosa oral |
| BloodPressure             | int64   | Presión arterial diastólica (mm Hg)                     |
| SkinThickness             | int64   | Grosor del pliegue cutáneo del tríceps (mm)              |
| Insulin                   | int64   | Insulina en suero a las 2 horas (mu U/ml)               |
| BMI                       | float64 | Índice de masa corporal (peso en kg / (altura en m)^2) |
| DiabetesPedigreeFunction  | float64 | Función de pedigrí de la diabetes                       |
| Age                       | int64   | Edad (años)                                             |
| Outcome                   | int64   | Variable de clase (0 o 1) 268 de 768 son 1, los demás son 0 |

### Descarga del conjunto de datos

[Kaggle: Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data)


### Versiones

- Pandas version: 2.0.3
- Altair version: 5.1.2
- Matplotlib version: 3.7.2
- Seaborn version: 0.12.2
- Scikit-learn version: 1.3.2
- Scipy version: 1.11.3


## Conclusión

El modelo SVM polinómico con características de entrada reducidas ha demostrado ser efectivo para la tarea de detección de diabetes, logrando un equilibrio entre la precisión y el recall. La detección temprana de casos positivos es esencial para prevenir y gestionar eficazmente la enfermedad.

