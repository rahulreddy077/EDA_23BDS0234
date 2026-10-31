# Exploratory Data Analysis (EDA) Using Python

A collection of Exploratory Data Analysis (EDA) assignments originally developed using R and RStudio, converted into Python implementations using Jupyter Notebook.

This project demonstrates fundamental and advanced EDA techniques, including data manipulation, statistical analysis, data cleaning, visualization, clustering, and dimensionality reduction.

## Project Overview

The objective of this project is to implement EDA concepts using Python libraries and provide practical experience in analysing, transforming, visualizing, and interpreting datasets.

The original R-based laboratory exercises were translated into Python to provide an accessible, reproducible, and notebook-based implementation.

## Technologies Used

| Technology       | Purpose                                          |
| ---------------- | ------------------------------------------------ |
| Python           | Primary programming language                     |
| Jupyter Notebook | Interactive development environment              |
| Pandas           | Data manipulation and analysis                   |
| NumPy            | Numerical computations                           |
| Matplotlib       | Data visualization                               |
| Seaborn          | Statistical visualization                        |
| SciPy            | Statistical analysis and hierarchical clustering |
| Scikit-learn     | Data preprocessing, clustering and PCA           |

## Assignment Coverage

The project covers the following EDA concepts:

| Assessment | Topic                                 | Key Concepts                                                |
| ---------- | ------------------------------------- | ----------------------------------------------------------- |
| 1          | DataFrames and Transformations        | DataFrame creation, indexing, selection and transformations |
| 2          | Data Import and Statistics            | Dataset loading, descriptive statistics and exploration     |
| 3          | Data Cleaning and Univariate Analysis | Missing values, data cleaning and distribution analysis     |
| 4          | Bivariate Analysis                    | Relationships between two variables and visual comparisons  |
| 5          | Multivariate Analysis                 | Analysis of relationships among multiple variables          |
| 7          | 1D, 2D and nD Analysis                | Multidimensional data exploration and visualization         |
| 8          | Clustering                            | K-Means and hierarchical clustering                         |
| 9          | Principal Component Analysis          | Dimensionality reduction and feature representation         |

**Note:** Assessment 6, which requires the AirPassengers dataset, was excluded from this version to maintain the project's single-dataset scope.

## Dataset

**Dataset:** `recid.csv`

The project uses the recidivism dataset for its analysis exercises.

Dataset source:

https://raw.githubusercontent.com/salemprakash/EDA/main/Data/recid.csv

Download the dataset and place it in the project directory.

## Project Structure

```text
EDA-Python/
│
├── EDA_Theory_Assessments_Python.ipynb
│
├── recid.csv
│
├── README.md
│
└── requirements.txt
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd EDA-Python
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Alternatively, install the required libraries directly:

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

Open:

```text
EDA_Theory_Assessments_Python.ipynb
```

Execute the notebook cells sequentially using `Shift + Enter`.

Ensure that `recid.csv` is available in the expected working directory before executing the notebook.

## Requirements

* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn

## Key Learning Outcomes

Through these assignments, the project demonstrates:

* Data loading, inspection and manipulation using Pandas.
* Descriptive and exploratory statistical analysis.
* Data cleaning and preprocessing.
* Univariate, bivariate and multivariate analysis.
* Graphical representation of data distributions and relationships.
* Clustering techniques for identifying data patterns.
* Principal Component Analysis for dimensionality reduction.
* Practical implementation of EDA workflows using Python.

## Execution

The notebook is organised into assessment-based sections.

Each section contains the corresponding Python implementation and outputs.

For reproducibility:

1. Clone or download the repository.
2. Install the required dependencies.
3. Download or locate `recid.csv`.
4. Open the Jupyter Notebook.
5. Execute the cells in sequence.

## Project Objective

This project demonstrates the transition of traditional R-based EDA laboratory exercises into Python implementations, highlighting the use of Python's data science ecosystem for statistical exploration, visualization, and analytical modelling.

## Author

**Bizzam Veera Rahul Reddy**

B.Tech – Computer Science and Engineering (Data Science)

Vellore Institute of Technology (VIT)

---

*Developed as part of Exploratory Data Analysis laboratory coursework.*
