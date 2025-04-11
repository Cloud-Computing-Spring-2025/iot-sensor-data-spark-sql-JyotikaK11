# IoT Sensor Data Analysis Using Spark SQL

This project showcases the analysis of IoT sensor data using Apache Spark and Spark SQL. The dataset reflects typical readings from IoT sensors, such as temperature, humidity, sensor location, and type. The workflow covers:

- Reading and exploring structured data
- Filtering records and performing grouped calculations
- Time-of-day based trend analysis
- Ranking sensors with window functions
- Creating pivot tables to examine patterns across dimensions

Each section generates a CSV file containing the results, saved in the `output/` folder.

---

## 🔧 Requirements

Before running this project locally, ensure the following tools and libraries are installed:

### Tools & Libraries

- Apache Spark 3.x
- Python 3.8 or later
- `pyspark` (`pip install pyspark`)
- `faker` for data simulation (`pip install faker`)

### Generating the Data

The data used in this project is synthetic and created using `data_generator.py`, which outputs a CSV file named `sensor_data.csv`.

To create the data:

```bash
python data_generator.py
