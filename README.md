# Datasets de entrenamiento y evaluación — CNN + AG

Se incorporaron conjuntos de datos de temperatura y humedad para el entrenamiento y evaluación de una red neuronal convolucional (CNN) optimizada mediante algoritmos genéticos (AG).

Los conjuntos contienen **1,000 lecturas secuenciales** de temperatura y humedad. Para evaluar el comportamiento del modelo ante perturbaciones, se introdujo ruido artificial en intervalos de 128 lecturas, generando siete episodios de anomalías.

## Visualización de los datos

Las siguientes gráficas muestran el comportamiento de las señales originales y modificadas, permitiendo identificar las variaciones introducidas durante la evaluación experimental.

### Temperatura

![Comparación de temperatura original y temperatura con ruido](/datasets/graficas/grafica_temperatura.png)

**Figura 1.** Comparación de las lecturas de temperatura originales y modificadas mediante la introducción de ruido artificial.

### Humedad

![Comparación de humedad original y humedad con ruido](/datasets/graficas/grafica_humedad.png)

**Figura 2.** Comportamiento de la humedad relativa durante las 1,000 lecturas, destacando los episodios de perturbación introducidos.

## Características del conjunto de datos

| Parámetro | Valor |
|---|---|
| Lecturas totales | 1,000 |
| Intervalo de perturbación | 128 lecturas |
| Episodios de ruido | 7 |
| Lecturas modificadas | 84 |
| Lecturas originales | 916 |
| Variables | Temperatura y humedad |

Estos datos permiten realizar pruebas de clasificación y detección de anomalías, así como evaluar el rendimiento del modelo CNN + AG mediante métricas de exactitud, precisión, recall y F1-score.
