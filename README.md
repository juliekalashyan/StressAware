# StressAware — Full-Stack ML Web Application

**Real-time physiological stress detection** using wearable sensor data from the [WESAD](https://archive.ics.uci.edu/ml/datasets/WESAD+%28Wearable+Stress+and+Affect+Detection%29) dataset.

A production-ready **Flask** backend serves a **single-page vanilla JavaScript** frontend that enables:
- **Instant analysis** of pre-trained subjects (< 50 ms response)
- **File upload** with automated feature extraction and model training
- **Multi-classifier comparison** across 7 ML algorithms with visualizations
- **Manual sensor input** for ad-hoc stress predictions
- **Longitudinal history tracking** with date filtering and CSV export
- **Persistent storage** across server restarts via SQLite
- **Rate limiting** protection and 30+ automated test coverage

---

## License & Attribution

Built on the **WESAD** dataset:

> Schuller, B., Pirker, H., et al. (2018). WESAD: A Publicly Available Dataset for Wearable Stress and Affect Detection. 2018 International Conference on Affective Computing and Intelligent Interaction (ACII). IEEE.

Download the dataset: https://archive.ics.uci.edu/ml/datasets/WESAD+%28Wearable+Stress+and+Affect+Detection%29


## Acknowledgment

A small part of the initial orientation for this project was informed by the following publicly available GitHub notebook:

https://github.com/ipremodi/Stress-Detection-/blob/main/ProjectWESAD.ipynb

The final project structure and implementation were developed separately and adapted to the goals of this work.

