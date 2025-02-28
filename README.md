# INFORMS Data-Driven Challenge 2024

## Overview

Hi, I am Tsai, the project owner, this project is part of the INFORMS Data-Driven Challenge and focuses on analyzing pharmaceutical manufacturing process data, including contextual data, machine operation data, and ingredient feeding records. The goal is to identify patterns and relationships between input variables (e.g., raw materials, process conditions) and output variables (e.g., quality indicators).

## Folder Structure

```
/processed_data          # Processed data files
/raw_data                # Raw data sources (Machine, Temperature, Humidity, etc.)
/dev.ipynb               # Development and modeling scripts
/preprocess.ipynb        # Data preprocessing and integration
/models                  # Machine Learning Model
```

## Dependencies

The project requires the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install the necessary dependencies using:

```sh
pip install pandas numpy matplotlib seaborn
```

## Data Processing Workflow

### Preprocessing (`preprocess.ipynb`)

- Load raw machine data (e.g., feeder, blender, tablet press, temperature, humidity).
- Map raw materials to feeder IDs.
- Align contextual data with process time slots.
- Merge different process segments into a unified dataset.

### Development & Analysis (`dev.ipynb`)

- Load processed data files.
- Perform descriptive statistical analysis (e.g., variance computation).
- Identify relationships between input parameters and output results.
- Visualize data trends.

## Execution

To preprocess the data, open and run `preprocess.ipynb` in Jupyter Notebook:

```sh
jupyter notebook preprocess.ipynb
```

For further analysis, open and execute `dev.ipynb`:

```sh
jupyter notebook dev.ipynb
```

## Pending Issues

- Some target data points are influenced by a range of records rather than a single record.
- Variability needs to be evaluated at both overall and per-sample-slot levels.

## Contributors

- Research and Development Team
- Data Analysts

For any questions or contributions, please reach out to the project maintainers.
