# Weather Data Analysis

This project analyzes global weather data using Python and Jupyter Notebook. It includes data cleaning, exploratory data analysis (EDA), and predictive modeling to understand weather patterns and forecast "feels like" temperature using linear regression.

## Project Structure

- `weather_analysis.ipynb`: Main Jupyter Notebook containing all code for data loading, cleaning, visualization, and modeling.
- `GlobalWeatherRepository.csv`: Weather dataset (CSV format).
- `WeatherDataSummary.pdf`: PDF summary of the dataset, with data last updated on **July 16, 2025**.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- The following Python packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - statsmodels

You can install the required packages using pip:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

### Download the Latest Data

Please ensure you download the **latest version** of `GlobalWeatherRepository.csv` before running the notebook, as the included PDF summary is based on data last updated on **2025-07-16**.

### Running the Notebook

1. Open `weather_analysis.ipynb` in Jupyter Notebook or JupyterLab.
2. Run each cell in order to:
   - Load and inspect the data
   - Perform exploratory data analysis (EDA)
   - Build and evaluate a linear regression model for "feels like" temperature

## Running the Notebook in Visual Studio Code

You can also run this notebook in Visual Studio Code.

1. **Install Visual Studio Code**  
   Download and install [VS Code](https://code.visualstudio.com/).

2. **Install the Python Extension**  
   In VS Code, go to the Extensions view (`Ctrl+Shift+X`) and install the official **Python** extension by Microsoft.

3. **Install Jupyter Support**  
   The Python extension will prompt you to install Jupyter support if it’s not already installed. Accept the prompt, or install the **Jupyter** extension manually.

4. **Open the Project Folder**  
   Use `File > Open Folder...` to open the `Weather Analysis` folder.

5. **Open the Notebook**  
   Double-click `weather_analysis.ipynb` in the Explorer sidebar.

6. **Select a Python Interpreter**  
   If prompted, select a Python interpreter with the required packages installed.

7. **Run the Notebook**  
   Use the "Run All" button or run cells individually using the play (`▶`) icons next to each cell.

**Tip:**  
Make sure `GlobalWeatherRepository.csv` is in the same folder as the notebook, and download the latest version before running.

## Notes

- The notebook expects the CSV file to be in the same directory.
- The PDF file provides a summary of the dataset as of July 16, 2025.

## License

This project is for educational and research purposes.
