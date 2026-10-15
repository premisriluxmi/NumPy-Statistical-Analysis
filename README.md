# NumPy Statistical Analysis

A beginner-level Python project that analyzes student marks using NumPy statistical functions.

## Objective

To analyze numerical data and calculate:

- Mean
- Median
- Standard deviation
- Minimum value
- Maximum value
- Unusually high and low values

## Technologies Used

- Python 3
- NumPy
- Jupyter Notebook

## Python Functions and Concepts Used

- `np.array()` – to create a numerical dataset
- `np.mean()` – to calculate the mean
- `np.median()` – to calculate the median
- `np.std()` – to calculate the standard deviation
- `np.min()` – to find the minimum value
- `np.max()` – to find the maximum value
- Boolean indexing – to identify values outside the selected range

## Results

| Statistical Measure | Result |
|---|---:|
| Number of Observations | 10 |
| Mean | 79.8 |
| Median | 79.0 |
| Standard Deviation | 9.12 |
| Minimum | 65 |
| Maximum | 95 |
| Unusually Low Values | 65, 70 |
| Unusually High Values | 90, 95 |

## Explanation

A dataset containing 10 student marks was analyzed using NumPy.

The mean was 79.8 and the median was 79.0. The standard deviation was approximately 9.12.

The minimum mark was 65 and the maximum was 95.

Values more than one standard deviation below or above the mean were flagged for further inspection. These are simple screening thresholds rather than definitive outlier classifications.

## How to Run

1. Open `NumPy_Statistical_Analysis.ipynb` in VS Code or Jupyter Notebook.
2. Ensure NumPy is installed. If necessary, run `pip install numpy`.
3. Select the Python kernel.
4. Run all notebook cells from top to bottom.
5. Review the statistical summary.

## Learning Outcome

- Learned to calculate statistical measures using NumPy.
- Understood the difference between mean and median.
- Practiced calculating standard deviation.
- Learned to identify values for further inspection.
- Gained experience in numerical data analysis.

## Project Structure

```text
NumPy-Statistical-Analysis/
│
├── NumPy_Statistical_Analysis.ipynb
└── README.md
```