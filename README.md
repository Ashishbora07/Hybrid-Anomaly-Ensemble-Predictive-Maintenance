
# Hybrid Anomaly-Ensemble Model for Predictive Maintenance Using Sensor Telemetry

## Project Overview

This project presents an AI and Machine Learning-based predictive maintenance system that identifies unusual patterns in sensor telemetry data.

The system uses a hybrid anomaly detection approach by combining multiple techniques to detect abnormal sensor readings and generate maintenance alerts.

## Objectives

- Detect abnormal patterns in sensor data.
- Apply multiple machine learning algorithms for anomaly detection.
- Combine model predictions using an ensemble approach.
- Generate alerts for potentially faulty equipment.
- Demonstrate how predictive maintenance can reduce unexpected machine failures.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Algorithms Used

1. Isolation Forest
2. Local Outlier Factor (LOF)
3. Statistical Z-Score
4. Majority Voting Ensemble

## Project Structure

```text
Hybrid-Anomaly-Ensemble-Predictive-Maintenance/
│
├── main.py
├── requirements.txt
└── README.md
```

## Installation

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

## Execution

Run the Python program using:

```bash
python main.py
```

You can also open the notebook in Google Colab and execute the cells.

## Dataset

The current implementation uses simulated sensor telemetry data with artificially introduced anomalies.

NASA C-MAPSS is identified as a potential real-world dataset for future testing and validation. It is not used in the current implementation.

## Applications

- Industrial equipment monitoring
- Manufacturing systems
- Predictive maintenance
- Sensor-based fault detection
- Machine health monitoring

## Future Scope

- Test the model using real industrial datasets.
- Integrate real-time sensor data.
- Improve anomaly detection accuracy.
- Develop a dashboard for maintenance monitoring.
- Generate automated maintenance notifications.

## Conclusion

This project demonstrates how machine learning and ensemble techniques can be used to identify abnormal sensor behaviour. It provides a basic predictive maintenance framework that can be extended for real-world industrial applications.

## Author

**Ashish Bora**

**USN:** 25BTRCM011

**Department:** Computer Science / CTMA

**Institution:** Jain University (Deemed to be University)

**Academic Year:** 2026–2027
