



| Metric                           | Value     |
| -------------------------------- | --------- |
| **Min Ambient Temperature (AT)** | 1.81 °C   |
| **Max Ambient Temperature (AT)** | 37.11 °C  |
| **Avg Ambient Temperature (AT)** | 19.65 °C  |
| **Min Power Output (PE)**        | 420.26 MW |
| **Max Power Output (PE)**        | 495.76 MW |
| **Avg Power Output (PE)**        | 454.37 MW |

### 🌡️ Key Dataset Insights:
- **Ambient Temperature (AT):** Ranges from **1.81°C** to **37.11°C** (average: **19.65°C**).
- **Power Output (PE):** Ranges from **420.26 MW** to **495.76 MW** (average: **454.37 MW**).
- These results show that temperature varies widely across the dataset, and power output stays within operational limits but still shows significant variation.
- Higher ambient temperature reduces cooling efficiency and overall thermal efficiency in the plant, reducing its energy output.
- This suggests that ambient temperature plays an important role in predicting the power plant’s energy output.

### 📈 Visual Analysis: Power Output vs Ambient Temperature

![Average Power Output vs Rounded Ambient Temperature](figures/average_power_vs_temperature.png)

The plot below shows the **average power output** at each rounded ambient temperature:

- Power output decreases as ambient temperature increases.
- This negative correlation is expected due to reduced thermal efficiency at higher temperatures.
- The smooth downward trend suggests that ambient temperature is a strong predictor of power output.

This visual insight highlights the importance of including temperature in the machine learning model for power output prediction.
