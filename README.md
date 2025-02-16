# Traffic Situation Prediction 🚦

## Overview
This project predicts the **traffic situation** based on vehicle counts and time-related data using **Machine Learning** techniques. The model analyzes traffic data and classifies it into different levels such as **low, normal, high, and heavy traffic**.

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical features, and normalizes numerical data.
- **Exploratory Data Analysis (EDA)**: Uses visualizations like histograms, heatmaps, and count plots.
- **Feature Selection**: Identifies key features affecting traffic situations.
- **Machine Learning Models**:
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest Classifier**
- **Evaluation Metrics**: Uses accuracy, precision, recall, and confusion matrix to assess model performance.

## Dataset
- The dataset is stored in `Traffic.csv` and contains the following columns:
  - `Time`: The time of the observation.
  - `Day of the week`: The day of the observation.
  - `CarCount`, `BikeCount`, `BusCount`, `TruckCount`: The number of different types of vehicles recorded.
  - `Total`: The total number of vehicles.
  - `Traffic Situation`: The traffic condition categorized as `low`, `normal`, `high`, or `heavy`.

## Usage
- The script reads `Traffic.csv`, processes the data, and trains machine learning models.
- It outputs:
  - Data insights through visualization.
  - Model performance metrics.
  - Predicted traffic situation for test data.

## Results
| Classifier         | Precision | Recall | Accuracy |
|--------------------|-----------|--------|----------|
| **KNN**           | 0.85      | 0.83   | 84%      |
| **Random Forest** | 0.92      | 0.90   | 91%      |

## Visualizations 📊
- **Traffic distribution by time and day**
- **Correlation heatmap of features**
- **Confusion matrices for model evaluation**

## Future Improvements 🚀
- Add deep learning models (e.g., LSTMs for time series prediction).
- Deploy the model as a web app.
- Collect real-time traffic data for better predictions.

## Contributing
Feel free to fork this project and submit pull requests to improve its functionality!

## License
This project is licensed under the MIT License.

