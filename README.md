
# Macroinvertebrate image analysis system

## Project overview
This project is a Python-based image analysis system for freshwater macroinvertebrate images. It performs exploratory data analysis, trains a Random Forest classification model, and provides a simple console menu application.

## Dataset
The project uses the Stream Macroinvertebrates dataset from Kaggle.

## Main features
- Loads macroinvertebrate image folders
- Creates dataset summary
- Generates EDA charts
- Trains a Random Forest classifier
- Produces accuracy, classification report and confusion matrix
- Saves the trained model using joblib
- Provides a console menu application for summary, EDA, report and prediction

## Python packages used
- pathlib: file path management
- pandas: image metadata table
- numpy: numerical array handling
- OpenCV: image loading, resizing and preprocessing
- matplotlib: charts and image display
- scikit-learn: model training and evaluation
- joblib: saving and loading the trained model
- PIL: image display

## How to run
1. Open the notebook in Google Colab.
2. Mount Google Drive.
3. Extract the dataset into data/raw.
4. Run the EDA section.
5. Run the classification section.
6. Run the console app section.

## Outputs
- outputs/eda/class_distribution.png
- outputs/eda/image_width_distribution.png
- outputs/eda/image_height_distribution.png
- outputs/eda/sample_image_grid.png
- outputs/eda/summary_table.csv
- outputs/reports/classification_report.txt
- outputs/reports/confusion_matrix.png
- outputs/models/macroinvertebrate_random_forest_model.joblib

## Testing
Manual testing evidence is included in MANUAL_TESTING.md.
