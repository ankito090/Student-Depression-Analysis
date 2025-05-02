# Student Depression Analysis

![Loan EDA Banner](./assets/logo.png)

## Contents

* [Project Overview](#project-overview)
* [Main Files](#main-files)
* [Software Used](#software-used)
* [Dataset](#dataset)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)

## Project Overview

In this project, I conducted a comprehensive data analysis of depression among students using a large-scale survey dataset. The analysis was performed in **R** within a **Jupyter Notebook** as part of the Google Data Analytics Capstone project.

## Main Files

- [`student_depression_analysis.ipynb`](./student_depression_analysis.ipynb) – Jupyter Notebook containing the complete analysis, visualizations, and interpretations.  
- [`LICENSE`](./LICENSE) – MIT License governing use and distribution of this project.

## Software Used

- **Programming Language:** R 4.4.3
- **Environment:** Jupyter Notebook

## Dataset

The dataset used in this project is the [Student Depression Dataset](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset), sourced from Kaggle. It contains anonymized, self-reported survey responses from students across diverse academic and demographic backgrounds.

## Requirements

Ensure the following libraries are installed:

- [autofileIO](https://github.com/ankito090/autofileIO) (A custom package I created for automatically reading and writing files)
- dplyr
- janitor
- tidyr
- skimr
- ggplot2
- stringr
- forcats    

## Installation

### 1. Clone or Download the Repository

To get started, first clone or download this repository to your local machine.

#### To clone the repository using Git, run the following command in your terminal or CLI:

```
git clone https://github.com/ankito090/Student-Depression-Analysis.git
```

**or**

#### [Download the Repository]https://codeload.github.com/ankito090/Student-Depression-Analysis/zip/refs/heads/main)

### 2. Install R and Jupyter Notebook

Ensure that R and Jupyter Notebook are installed on your machine. If not:

- Download and install R from [CRAN](https://cran.r-project.org/). 
- To use R within Jupyter Notebook, install [Anaconda](https://www.anaconda.com/products/distribution), which includes Jupyter Notebook.
- After installing Anaconda, open **Anaconda Navigator** or launch a terminal and type:

  ```
  jupyter notebook
  ```
  This will open the Jupyter interface in your browser.

### 3. Add R Kernel to Jupyter

To enable R in Jupyter, follow these steps:
- Open R or RStudio
- Run the following in the R console:

  ```
  install.packages("IRkernel")
  IRkernel::installspec(user = FALSE)
  ```
  You should now see R as a kernel option when creating a new notebook in Jupyter.

### 4. Install Required R Packages

- In R or RStudio, install the required packages (if not already installed) by running:

  ```
  install.packages(c("dplyr", "janitor", "tidyr", "skimr", "ggplot2", "stringr", "forcats"))
  ```

- Also, install the custom autofileIO package used in this project by running:

  ```
  install.packages("devtools")
  devtools::install_github("ankito090/autofileIO")
  ```

## Usage

### Open your terminal or CLI and navigate to the root directory of the cloned or downloaded project using this command:

```
cd path/to/project-directory
```
Replace `path/to/project-directory` with the actual path where the project is saved.

### Open and run the notebook using Jupyter:

```
jupyter notebook student_depression_analysis.ipynb
```
