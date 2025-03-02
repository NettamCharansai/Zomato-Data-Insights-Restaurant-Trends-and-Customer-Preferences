# Zomato Data Insights: Restaurant Trends & Customer Preferences

## Overview
This project analyzes Zomato restaurant data to uncover insights on restaurant types, ratings, pricing, and customer preferences. It includes data preprocessing, visualization, and an interactive dashboard for deeper exploration.

## Features
- **Data Cleaning & Preprocessing**
  - Reads and processes `Zomato_data.csv`
  - Converts ratings to numeric format
  - Handles missing values

- **Data Analysis & Visualizations**
  - Restaurant type distribution
  - Vote analysis and most popular restaurant identification
  - Online order availability trends
  - Rating and pricing distribution
  - Relationship analysis using heatmaps and box plots

- **Interactive Dashboard (Gradio)**
  - Select restaurant type and view rating distributions
  - User-friendly web interface with dynamic plots

## Installation
### Prerequisites
Ensure you have Python and the following libraries installed:
```sh
pip install pandas numpy matplotlib seaborn gradio
```

### Running the Project
1. Clone this repository:
```sh
git clone https://github.com/your-username/zomato-data-insights.git
cd zomato-data-insights
```
2. Run the Jupyter Notebook:
```sh
jupyter notebook Data_Analysis_Project.ipynb
```
3. To launch the interactive dashboard:
```sh
python dashboard.py
```

## Usage
- Run the notebook to generate insights and visualizations.
- Launch the Gradio dashboard to explore ratings interactively.
- Modify the dataset to analyze different restaurant trends.

## Results & Insights
- The most popular restaurant based on votes.
- How restaurant type impacts customer engagement.
- The effect of online ordering on ratings.
- Cost vs. rating distribution patterns.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a PR.

## Author
Maintained by **Nettam Charan Sai**

