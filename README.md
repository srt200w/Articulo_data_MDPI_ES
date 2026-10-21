# Training and Evaluation Datasets — CNN + GA

Datasets containing temperature and humidity readings were incorporated for the training and evaluation of a convolutional neural network (CNN) optimized via genetic algorithms (GA).

The datasets consist of **1,000 sequential readings** of temperature and humidity. To evaluate the model's behavior in the presence of disturbances, artificial noise was introduced at intervals of 128 readings, resulting in seven episodes of anomalies.

## Data Visualization

The following graphs illustrate the behavior of the original and modified signals, allowing for the identification of variations introduced during the experimental evaluation.

### Temperature

![Comparison of original temperature and temperature with noise](/datasets/graficas/grafica_temperature.png)

**Figure 1.** Comparison of original temperature readings and those modified by the introduction of artificial noise.

### Humidity

![Comparison of original humidity and humidity with noise](/datasets/graficas/grafica_humidity.png)

**Figure 2.** Behavior of relative humidity over the 1,000 readings, highlighting the introduced disturbance episodes.

## Dataset Characteristics

| Parameter | Value |
|---|---|
| Total readings | 1,000 |
| Disturbance interval | 128 readings |
| Noise episodes | 7 |
| Modified readings | 84 |
| Original readings | 916 |
| Variables | Temperature and humidity |

These data facilitate classification and anomaly detection tasks, as well as the evaluation of the CNN + GA model's performance using metrics such as accuracy, precision, recall, and F1-score.
