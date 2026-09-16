NumPy Array Creation and Data Types: Student Performance Analysis

A practical data science project demonstrating foundational NumPy concepts, array creation, attribute exploration, and vectorized numerical operations using the Student Performance dataset.

📌 Project Overview

This project is part of a data science internship task designed to master the fundamentals of NumPy, Python's core library for numerical computing. By leveraging the StudentsPerformance dataset, we transition from standard Python data structures to efficient, vectorized NumPy arrays to analyze student test scores in math, reading, and writing.

🚀 Features & Deliverables

One-Dimensional (1D) Arrays: Extracting individual feature columns (e.g., math scores) for sequential analysis.

Two-Dimensional (2D) Arrays: Grouping multiple related features (math, reading, and writing scores) into matrix structures.

Array Attributes: Exploring fundamental metadata properties including .shape, .ndim, .size, and .dtype.

Numerical & Statistical Operations: Performing vectorized arithmetic, broadcasting, boolean masking, and computing descriptive statistics (mean, median, std, min, max).

Array Creation Methods: Utilizing advanced creation functions like np.array(), np.zeros(), np.ones(), np.arange(), and np.linspace().

🛠️ Tech Stack & Tools

Language: Python 3.x

Libraries: NumPy, Pandas

Environment: Jupyter Notebook

💻 Code Implementation

Here is a quick snippet demonstrating how arrays are initialized and analyzed:

import numpy as np
import pandas as pd

# Load dataset and extract scores into NumPy arrays
df = pd.read_csv("StudentsPerformance.csv")
math = df["math score"].to_numpy()

# Inspect array attributes
print("Shape:", math.shape)
print("Dimensions:", math.ndim)
print("Data Type:", math.dtype)

# Statistical computations
print("Mean Math Score:", np.mean(math))


📈 Key Takeaways

Performance: NumPy arrays operate significantly faster than native Python lists due to continuous memory allocation and vectorized execution.

