# Object-Oriented-Image-Data-Processing-Analysis-Pipeline
The project implements a complete data processing and analysis pipeline using object-oriented programming (OOP) principles in Python, with a focus on image-based datasets.

The goal of the project is to:
Load and preprocess a dataset of images
Extract meaningful numerical features using NumPy
Analyze those features with Pandas
Visualize insights using Matplotlib and Seaborn
All components are structured into distinct Python classes to ensure modular, scalable, and reusable code design.

## Project Structure
DataLoader: Loads and preprocesses images (resizing, filtering, color mode conversion) and stores them as NumPy arrays.
FeatureExtractor: Extracts image features such as mean intensity, standard deviation, contrast, and aspect ratio into a Pandas DataFrame.
DataAnalyzer: Performs statistical analysis and data operations like grouping, sorting, and filtering.
Visualizer: Generates at least five meaningful plots (e.g., histograms, scatter plots, box plots) with full labeling for interpretability.
