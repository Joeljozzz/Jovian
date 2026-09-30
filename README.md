# 📊 Supermarket Store Sales Analysis

[![View on Jovian](https://img.shields.io/badge/View_on-Jovian-007ACC?style=for-the-badge&logo=jovian&logoColor=white)](https://jovian.ai/joeljo2201/zerotopandas-course-project-starter)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

An exploratory data analysis (EDA) project evaluating retail store characteristics and sales performance across a supermarket chain. Built as part of the Jovian *Data Analysis with Python: Zero to Pandas* course, this project examines relationships between store physical area, inventory variety, daily customer footfall, and overall revenue.

---

## 🚀 Live Notebook

You can view the interactive notebook hosted directly on Jovian:
**[View Interactive Notebook on Jovian](https://jovian.ai/joeljo2201/zerotopandas-course-project-starter)**

---

## 🔍 Key Features

- **Automated Dataset Retrieval**: Programmatically downloads the [Kaggle Stores Area and Sales Data](https://www.kaggle.com/datasets/surajjha101/stores-area-and-sales-data) using `opendatasets`.
- **Data Preprocessing & Cleaning**: Inspects data integrity, handles column naming discrepancies, and analyzes summary statistics across 896 store entries.
- **Statistical Visualization**:
  - Store sales and footfall distribution plots (`distplot` / histograms).
  - Multi-variable pairplots analyzing cross-attribute variance.
  - Correlation heatmap evaluating interactions between store area, inventory count, customer visits, and total sales.
- **Store Performance Analysis**:
  - Ranks top 10 stores by gross revenue.
  - Identifies top 10 stores by monthly customer traffic.
  - Evaluates maximum and minimum sales extremes and store-specific footfall benchmarks.

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Environment**: Jupyter Notebook
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Data Source & Platform**: Kaggle (`opendatasets`), Jovian

---

## 📁 Project Structure

```
Jovian/
├── zerotopandas-course-project.ipynb   # Main Jupyter notebook containing analysis & plots
├── LICENSE                             # MIT License
└── README.md                           # Project documentation
```

---

## 🏁 Getting Started

### Prerequisites

- Python 3.8 or higher installed on your machine
- A [Kaggle account](https://www.kaggle.com) with API credentials (`kaggle.json`) if downloading the dataset directly via code

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/joeljo2201/Jovian.git
   cd Jovian
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn opendatasets jovian jupyter
   ```

---

## 💻 Usage

1. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. Open `zerotopandas-course-project.ipynb` in the browser interface.

3. **Run the cells sequentially**:
   - When prompted by `opendatasets`, enter your Kaggle username and Kaggle API key to download the dataset.
   - Alternatively, download `Stores.csv` manually from [Kaggle](https://www.kaggle.com/datasets/surajjha101/stores-area-and-sales-data) and place it in `./stores-area-and-sales-data/Stores.csv`.

---

## 📊 Key Findings

- **Average Store Traffic**: Supermarket branches see an average of approximately 800 customers daily.
- **Inventory & Area Correlation**: Store area and available items share a strong positive correlation, while sales variation is influenced by footfall and localized buying patterns.
- **Top Performers**: Pinpointed benchmark store IDs achieving peak revenue and customer retention.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
