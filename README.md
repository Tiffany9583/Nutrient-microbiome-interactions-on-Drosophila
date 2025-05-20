# Nutrient-microbiome-interactions-on-Drosophila
This repository contains the data and code used to track fly locomotion for the research titled 
**Systematic Analysis of Nutrient-Microbiome Interactions and Their Effects on Host Phenotype in _Drosophila_**.

## 📂 Data Description for Drosophila-related Experiment Dataset
- **Source:** The phenotypic observations and bacterial load data were collected by Yi-Ting Hung at the University of Florida during 2023–2024. 
- **File Format:** CSV
- **Size:**  101 KB 
- **Number of Records:** [1081 rows, 18 columns]  

## 📊 Data Structure
| Column Name | Description                      | Data Type |
|-------------|----------------------------------|-----------|
| `level` | 	Concentration level of protein and carbohydrate in the tested diet      | String    |
| `rep`     | Replicate number          | Integer   |
| `group` | Microbiome treatment group     | String    |
| `diet_no` | Diet identification number     | String    |
| `ratio`   | Yeast-to-sugar ratio in the tested diet     | String   |
| `yeast`  | Yeast amount in the diet    | String    |
| `sugar`  | Sugar amount in the diet    | String    |
| `CFU_AP`  | Bacteria load of _Acetobacter pasteurianus_ in flies     | Integer  |
| `CFU_LB`  | Bacteria load of _Lactobacillus brevis_ in flies     | Integer  |
| `Fecundity`  | Number of eggs laid by the tested flies     | Integer  |
| `Weight`  | Body weight of the tested flies     | Float  |
| `Protein`  | Protein level in the tested flies     | Float |
| `Glucose`  | Glucose levels in the tested flies     | Float  |
| `TAG`  | Triglyceride (TAG) level in the tested flies     | Float  |
| `Average_counts_L`  | Average locomotor activity counts during the light period     | Float  |
| `Average_counts_D`  | Average locomotor activity counts during the dark period     | Float  |
| `Sleep_duration_L`  | Total sleep duration during the light period     | Float  |
| `Sleep_duration_D`  | Total sleep duration during the dark period     | Float  |




## 📥 Accessing the Data
You can download the dataset by:  
1. Cloning this repository:  
   ```bash
   git clone https://github.com/Tiffany9583/Nutrient-microbiome-interactions-on-Drosophila.git
