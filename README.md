# iris-dataset-exploration
Exploring and visualizing the Iris dataset using pandas, matplotlib, and seaborn. Includes scatter plots, histograms, box plots, pairplots, and correlation heatmaps to understand feature relationships and species distribution.

Exploring and Visualizing a Simple Dataset

## Objective
Understand how to read, summarize, and visualize a dataset using Python libraries (pandas, matplotlib, seaborn).

## Dataset
**Iris Dataset** - A classic dataset containing 150 samples of iris flowers from three species:
- Iris-setosa
- Iris-versicolor  
- Iris-virginica

**Features:**
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

**Target:** Species of the iris flower

## Approach

### 1. Data Loading & Inspection
- Loaded dataset using `pandas` and `sklearn.datasets`
- Inspected structure using `.shape`, `.columns`, `.head()`, `.dtypes`
- Checked for missing values

### 2. Data Summarization
- Generated descriptive statistics using `.describe()`
- Analyzed species distribution (50 samples each - balanced dataset)
- Computed mean values grouped by species

### 3. Visualizations
- **Scatter Plot:** Analyzed relationships between variables (Petal Length vs Width, Sepal Length vs Width)
- **Histogram:** Examined distribution of all 4 features
- **Box Plot:** Detected outliers and spread of values by species
- **Pairplot:** Comprehensive view of all feature relationships
- **Correlation Heatmap:** Identified strong correlations between features

## Key Results

| Metric | Finding |
|--------|---------|
| Dataset Size | 150 rows × 5 columns |
| Missing Values | 0 |
| Balance | Perfectly balanced (50 per species) |
| Strongest Correlation | Petal Length ↔ Petal Width (0.96) |

## Key Insights

1. **Setosa** is clearly separable from the other two species based on petal measurements.
2. **Petal Length and Petal Width** are highly correlated and are the most discriminative features.
3. **Virginica** has the largest measurements, while **Setosa** has the smallest.
4. Very few outliers detected across all features.

## Tools Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn.datasets

## File
- `Task1_Iris_Dataset_Exploration.ipynb`

---


