# Real_TIme_Air_Quality_Project
🌍 Real-Time Air Quality Monitoring using Python | Fetches air quality forecast data for Shimla using the Open-Meteo API, analyzes PM2.5, PM10, NO₂, and O₃ levels, exports data to CSV, and visualizes pollutant trends using Matplotlib.
# 🌍 Real-Time Air Quality Monitoring — Shimla

## 📌 Project Overview

The **Real-Time Air Quality Monitoring Project** is a Python-based data analysis and visualization project that retrieves air quality forecast data for Shimla, Himachal Pradesh, using the Open-Meteo Air Quality API.

The project collects hourly forecast data for major air pollutants, including PM2.5, PM10, Nitrogen Dioxide (NO₂), and Ozone (O₃). The collected data is organized using Pandas, exported to a CSV file, and visualized using Matplotlib to understand changes in pollutant levels over time.

This project demonstrates API integration, data collection, data handling, CSV export, and data visualization using Python.

**Note:** The project uses model-based air quality forecasts provided by the API. It does not collect readings from physical sensors or use a trained machine learning model.

## 🎯 Project Objectives

* Retrieve air quality forecast data using an API.
* Analyze hourly air quality data for Shimla.
* Work with multiple air pollutants.
* Store collected data in CSV format.
* Visualize pollutant trends using graphs.
* Practice Python programming and data analysis.

## ✨ Features

* 🌐 **API Integration:** Fetches air quality forecast data from Open-Meteo.
* 📊 **Pollutant Monitoring:** Works with PM2.5, PM10, NO₂, and O₃.
* ⏰ **Hourly Forecast:** Retrieves forecast data for up to five days.
* 📁 **CSV Export:** Saves collected data to a CSV file.
* 📈 **Data Visualization:** Creates graphs to display pollutant trends.
* 📍 **Location-Based Analysis:** Uses the coordinates of Shimla, Himachal Pradesh.
* 🔄 **Data Refresh:** Retrieves fresh forecast data whenever the API cell is executed again.

## 🛠️ Technologies Used

* **Python** — Programming language
* **Requests** — API requests and data retrieval
* **Pandas** — Data processing and CSV export
* **Matplotlib** — Data visualization
* **Jupyter Notebook / Google Colab** — Development environment
* **Open-Meteo Air Quality API** — Air quality forecast data source

## 🧪 Air Pollutants Analyzed

| Pollutant | Description                                                        |
| --------- | ------------------------------------------------------------------ |
| PM2.5     | Fine particulate matter with a diameter of 2.5 micrometers or less |
| PM10      | Particulate matter with a diameter of 10 micrometers or less       |
| NO₂       | Nitrogen dioxide                                                   |
| O₃        | Ozone                                                              |

## ⚙️ How It Works

1. Import the required Python libraries.
2. Set the latitude and longitude for Shimla.
3. Send a request to the Open-Meteo Air Quality API.
4. Retrieve hourly pollutant forecast data.
5. Convert the API response into a Pandas DataFrame.
6. Organize pollutant data into readable columns.
7. Export the processed data to a CSV file.
8. Create graphs to visualize pollutant forecast trends.

## 📂 Project Structure

```text
Real-Time-Air-Quality-Monitoring/
│
├── Real_Time_Air_Quality_Project_2.ipynb
├── shimla_real_time_air_quality_forecast.csv
└── README.md
```

**Note:** The CSV file is generated when you run the notebook. You can add the generated file to your repository if you want to share a sample output.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Real-Time-Air-Quality-Monitoring.git
```

### 2. Navigate to the Project Folder

```bash
cd Real-Time-Air-Quality-Monitoring
```

### 3. Install Required Libraries

```bash
pip install requests pandas matplotlib jupyter
```

### 4. Run the Notebook

Open the notebook using Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, upload the `.ipynb` file to Google Colab and run the cells in sequence.

### 5. Generate the Output

Execute the notebook cells to:

* Fetch air quality forecast data.
* Process the data using Pandas.
* Save the results as a CSV file.
* Generate pollutant forecast graphs.

**Google Colab users:** The notebook includes a CSV download command that uses `google.colab.files`. If you run the notebook locally, use `df.to_csv()` to save the output without the Colab-specific download command.

## 📊 Expected Output

After running the notebook, you will get:

* A DataFrame containing hourly air quality forecast data.
* A CSV file named `shimla_real_time_air_quality_forecast.csv`.
* A graph showing PM2.5 and PM10 forecast trends.
* A graph showing NO₂ and O₃ forecast trends.

The actual values and trends depend on the latest data returned by the API.

## 🌐 Data Source

This project uses the Open-Meteo Air Quality API.

API Documentation: https://open-meteo.com/en/docs/air-quality

The API provides model-based air quality information. Forecast values should not be treated as direct measurements from a physical monitoring station.

## 🔮 Future Improvements

* Add an interactive dashboard using Streamlit.
* Include additional pollutants and weather parameters.
* Compare forecasts with observed air quality measurements.
* Add historical data analysis.
* Introduce automated periodic data collection.
* Develop and evaluate a machine learning model using suitable historical observations.
* Display an air quality index when supported by an appropriate data source and calculation method.


## 📄 License

This project is intended for educational and learning purposes. Add a suitable open-source license if you want others to reuse, modify, and distribute your code.

---

⭐ If you find this project useful, consider giving the repository a star!
