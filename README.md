# Ocean Water Prediction

## Project Overview

This project involves analyzing satellite data for sea surface temperature (SST) and salinity. The pipeline includes data preparation, exploratory data analysis (EDA), model training, and predictions.

## Project Structure

```
├── data_preparation.py  # Processes NetCDF files and extracts variables
├── eda.py  # Performs data visualization and statistical analysis
├── training.py  # Trains a model on extracted data
├── prediction.py  # Uses the trained model to make predictions
├── model.py  # Handles model saving and loading
├── processed_data.csv  # Preprocessed dataset
├── trained_model.pkl  # Saved trained model
├── README.md  # Project documentation
```

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

### Data Preparation

```sh
python data_preparation.py
```

### Exploratory Data Analysis

```sh
python eda.py
```

### Training Model

```sh
python training.py
```

### Making Predictions

```sh
python prediction.py
```

## License

MIT License

