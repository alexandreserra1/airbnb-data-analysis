# airbnb-data-analysis
# Airbnb Data Analysis

This project involves an in-depth data analysis of Airbnb listings in Rio de Janeiro, Brazil. The analysis is performed using Python and various data science libraries, with the goal of uncovering trends, insights, and potential opportunities within the Airbnb market in Rio de Janeiro.

## Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Analysis](#analysis)
- [How to Run the Project](#how-to-run-the-project)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to explore and analyze the Airbnb dataset available on Kaggle for Rio de Janeiro. We perform data cleaning, exploratory data analysis (EDA), and various visualizations to understand the dynamics of the Airbnb market in Rio.

## Data Source
The dataset used in this project is obtained from Kaggle:
- **Source**: [Airbnb Rio de Janeiro Dataset on Kaggle](https://www.kaggle.com/datasets)
- **Description**: The dataset includes various attributes such as listing details, pricing, location, and availability.

## Technologies Used
- **Python**: The core programming language used for analysis.
- **Jupyter Notebook**: For interactive data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Geopandas & Folium**: For geospatial data analysis and mapping.


## Analysis
The analysis is structured into the following key sections:
1. **Data Cleaning**: Handling missing values, outliers, and correcting data types.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of data, correlation between features, and key insights.
3. **Visualizations**: Creating various plots to visualize the distribution of prices, locations, and availability of Airbnb listings in Rio.
4. **Geospatial Analysis**: Mapping Airbnb listings to visualize their geographical distribution across the city.

## How to Run the Project
1. **Clone the repository**:
    ```bash
    git clone git@github.com:alexandreserra1/airbnb-data-analysis.git
    cd airbnb-data-analysis
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook notebooks/Airbnb_Analysis.ipynb
    ```

## Contributing
Contributions are welcome! Please fork the repository and create a pull request if you have any improvements or suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


