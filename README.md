# Task-05-Prodigy-InfoTech

# US Traffic Accident Analysis & Visualization

**Short Description:**
A data analysis project that explores US traffic accident data (2016–2023) to identify trends, accident hotspots, and contributing factors using data cleaning, exploratory data analysis (EDA), and visualization techniques in Python.

---

## Project Overview

This project analyzes a **large-scale US traffic accident dataset (2016–2023)** to understand when, where, and under what conditions traffic accidents occur. The notebook follows a structured data analysis workflow, including data cleaning, feature exploration, and visual analytics.

The goal is to uncover meaningful patterns related to **time, geography, weather, and road conditions**, supporting data-driven decisions for **traffic safety, urban planning, and infrastructure improvement**.

---

## Objectives

* Clean and preprocess traffic accident data
* Perform exploratory data analysis (EDA)
* Identify accident trends across time and locations
* Analyze environmental and road-related contributing factors
* Visualize insights clearly and effectively

---

## Features

* Data Cleaning and Preprocessing

  * Handling missing values
  * Removing irrelevant or redundant columns
  * Converting date and time features

* Exploratory Data Analysis (EDA)

  * Accident frequency analysis
  * Time-based trend analysis (hour, day, month)
  * Location-based insights

* Visualization

  * Bar charts, histograms, and count plots
  * Trend analysis across multiple dimensions

* Insight Generation

  * Identification of accident hotspots
  * Understanding peak accident periods
  * Analysis of contributing factors

---

## Technologies Used

* Python
* Pandas – Data manipulation and analysis
* NumPy – Numerical operations
* Matplotlib – Data visualization
* Seaborn – Statistical visualizations
* Jupyter Notebook

---

## Dataset

**Source:** US Traffic Accidents Dataset (2016–2023)

**Description:**
The dataset contains **46 features** capturing detailed information about traffic accidents across the United States, including time, location, severity, environmental conditions, and road/infrastructure attributes.

### Complete List of Columns

1. ID
2. Source
3. Severity
4. Start_Time
5. End_Time
6. Start_Lat
7. Start_Lng
8. End_Lat
9. End_Lng
10. Distance(mi)
11. Description
12. Street
13. City
14. County
15. State
16. Zipcode
17. Country
18. Timezone
19. Airport_Code
20. Weather_Timestamp
21. Temperature(F)
22. Wind_Chill(F)
23. Humidity(%)
24. Pressure(in)
25. Visibility(mi)
26. Wind_Direction
27. Wind_Speed(mph)
28. Precipitation(in)
29. Weather_Condition
30. Amenity
31. Bump
32. Crossing
33. Give_Way
34. Junction
35. No_Exit
36. Railway
37. Roundabout
38. Station
39. Stop
40. Traffic_Calming
41. Traffic_Signal
42. Turning_Loop
43. Sunrise_Sunset
44. Civil_Twilight
45. Nautical_Twilight
46. Astronomical_Twilight

**Note:** These columns capture temporal, geographic, environmental, and road-related features, providing a comprehensive view for analysis.

---

## Project Workflow

### 1. Data Loading

* Loaded the dataset into a Pandas DataFrame
* Inspected dataset shape, types, and completeness

### 2. Data Cleaning

* Handled missing values and duplicates
* Dropped unnecessary columns
* Converted date and time features for analysis

### 3. Exploratory Data Analysis

* Analyzed accident frequency by severity
* Examined trends across hours, days, and months
* Studied accident distribution across states and cities

### 4. Visualization

* Visualized peak accident hours
* Compared accident counts across weather conditions
* Highlighted accident-prone regions

---

## Code Structure

```
Task_05.ipynb
├── Import Libraries
├── Load Dataset
├── Data Inspection
├── Data Cleaning
├── Exploratory Data Analysis (EDA)
│   ├── Time-based Analysis
│   ├── Location-based Analysis
│   └── Weather-based Analysis
├── Data Visualization
└── Insights & Conclusion
```

---

## Key Insights

* Accidents occur more frequently during peak commuting hours
* Certain states and cities show consistently higher accident counts
* Weather, visibility, and environmental conditions influence accident frequency
* Time-of-day and road infrastructure factors play a significant role in accident occurrence

---

## Conclusion

This project demonstrates a full **data analysis pipeline** applied to large-scale traffic accident data. By analyzing time, location, weather, and road conditions, the notebook identifies accident patterns and hotspots, providing actionable insights for **road safety, urban planning, and policy decisions**.

The project showcases skills in **data cleaning, exploratory analysis, visualization, and insight communication**, which are directly applicable to **Data Analyst, Product Analyst, and Business Analyst roles**.

---

## Contributing

Contributions are welcome. Please fork the repository and submit pull requests.

---

## Contact

Aditya Gaur
Email: [work.adityagaur@gmail.com](mailto:work.adityagaur@gmail.com)
LinkedIn: [https://linkedin.com/in/adityamnnit03](https://linkedin.com/in/adityamnnit03)

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

* Dataset: US Traffic Accidents (2016–2023)
* Created for hands-on data analysis and portfolio development
* Inspired by real-world transportation analytics use cases
 
