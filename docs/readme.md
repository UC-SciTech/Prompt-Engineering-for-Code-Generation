# Documentation

## Table of Contents

- [Documentation](#documentation)
  - [Table of Contents](#table-of-contents)
  - [Project Information](#project-information)
  - [Exploratory Data Analysis](#project-eda)
  - [Usage](#usage)

## Project Information

We built a framework that explores different prompt engineering techniques and how to craft them effectively to generate desired code generation outputs from the LLMs. By conducting the experiments using this framework, we can improve how LLMs generate code, making it more accurate and relevant to the task.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was performed by summarising key statistics, visualising trends, and identifying potential outliers or patterns from the compiled results of all conducted experiments for this project.

### Research Problems
1. Which model performs best (highest accuracy, F1 score, etc.) across different datasets (HumanEval, BIG Bench, MBPP)?
2. How does the performance of each model vary depending on the technique used (CoT, Zero Shot, Few Shot)?
3. How does the performance of each model vary depending on the dataset used (MBPP, HumanEval, BIG Bench)?
4. How does the performance of each model vary depending on the technique used (CoT, Zero Shot, Few Shot) and Application (Function, Snippet)?
5. How does the performance of each model vary depending on the Application (Function, Snippet)?
6. How does the performance of each technique used (CoT, Zero Shot, Few Shot) vary depending on the Application (Function, Snippet)?
7. which technique had the highest Exact Match Score?
8. Do some models consistently perform better on specific applications (Function vs. Snippet) or tasks (identified by Task_ID)?
9. Is there a significant difference in execution time between models for the same task?
10. Which technique (CoT, Zero Shot, Few Shot) is most effective on a specific application (Function, Snippet)?

## Usage

Jupyter Notebooks, identified by the .ipynb file extension, are dynamic documents that integrate code, written content, and graphics. They are widely used for analyzing data and conducting computational research. 

All Experiment Jupyter Notebook Files can be located in the ExperimentFiles Folder of this repository. 

Clicking the .ipynb file name will basically render a basic view of the notebook content directly within the GitHub interface. While this approach allows for quick code inspection, it may not offer the full functionality of a specialized Jupyter Notebook environment. 

Opening the .ipynb file using a Jupyter Notebook application installed on your local machine offers full interactivity and execution capabilities within the Jupyter environment.
