# Used Vehicle Market Analysis Web Application

---

## Project Overview

This project consists of an interactive web application developed with Streamlit for exploratory analysis of used vehicle advertisement data.

The application enables users to explore vehicle characteristics through interactive visualizations, making it easier to identify relationships between mileage, price, and other attributes.

The project demonstrates how data analysis can be transformed into an accessible web application for interactive exploration.

---

## Business Problem

Used vehicle marketplaces generate large volumes of advertisement data containing valuable insights about pricing and vehicle characteristics.

The objective of this project is to provide an interactive interface that allows users to:

- Explore vehicle price distributions
- Analyze mileage patterns
- Investigate relationships between numerical variables
- Interact with visualizations without writing code

---

## Dataset

The project uses the dataset:

- `vehicles_us.csv`

The dataset contains advertisements for used vehicles, including information such as:

- Price
- Model year
- Mileage
- Fuel type
- Transmission
- Vehicle condition
- Vehicle type

The dataset was provided by TripleTen for educational purposes.

---

## Technologies Used

- Python
- Pandas(análise e manipulação de dados)
- Plotly Express(gráficos interativos)
- Streamlit (interface web)
- Jupyter Notebook
- Git (controlo de versões)
- GitHub (armazenamento e partilha do código)
- Render (hospedagem da aplicação)

---

## Application Features

The application allows users to:

- Explore vehicle mileage distributions through interactive histograms.
- Visualize the relationship between mileage and price using scatter plots.
- Interact with charts through Streamlit checkboxes.
- Analyze data dynamically without modifying the source code.

---

## Interactive Visualizations

The application includes:

- Mileage Distribution Histogram
- Mileage vs Price Scatter Plot

---

## Live Demo

The application is available online through Render:

https://vehicles-app-epdt.onrender.com

---

## Application Screenshots

### Home Interface

*(image here)*

---

### Scatter Plot Analysis

*(image here)*

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/etienne-94/vehicles-app.git
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Launch the application:

```bash
streamlit run app.py
```

---

## Repository Structure

```text
vehicles-app/
│
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
├── vehicles_us.csv
│
├── images/
│   ├── app_home.png
│   └── scatter_plot.png
│
├── notebooks/
│   └── EDA.ipynb
│
├── .streamlit/
│   └── config.toml
│
└── .vscode/
    └── settings.json
```

---

## Dataset Availability

The dataset used in this project was provided by TripleTen for educational purposes and is not included in this repository.

---

## Conclusion

This project demonstrates how exploratory data analysis can be transformed into an interactive web application, allowing users to explore vehicle data without programming knowledge.

By combining Python, Pandas, Plotly Express, and Streamlit, the application provides an intuitive interface for visualizing patterns and relationships within the dataset while showcasing practical skills in data analysis, web application development, and deployment.

---

## Author

Etienne Viegas dos Santos

Data Analytics Student | TripleTen

GitHub: https://github.com/etienne-94
