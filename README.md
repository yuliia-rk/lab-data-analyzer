# lab-data-analyzer
A robust and user-friendly Python tool for performing statistical analysis on numerical data from lab experiments. It reads data from a text file and calculates key descriptive statistics.
## Features

- **Calculates Comprehensive Statistics:** Mean, median, standard deviation, maximum, and minimum values.
- **Robust Data Handling:** Automatically handles European decimal formats (commas) and ignores empty lines.
- **Error Resilience:** Gracefully handles missing files, empty files, and non-numeric data with clear error messages.
- **User-Friendly Interface:** Interactive command-line interface with the option to analyze multiple files in one session.

## How to Use

1.  **Prepare your data file:** Create a `.txt` file with one number per line. Decimals can use periods (.) or commas (,).
    Example (`data.txt`):
    ```
    15,2
    17.8
    14,1
    16.5
    19.0
    13.2
    ```

2.  **Run the analyzer:**
    ```bash
    python lab_analyzer.py
    ```

3.  **Follow the prompts:** Enter the name of your data file when prompted (e.g., `data` or `data.txt`).

## Example Output
Welcome to Lab Data Analyzer!
Please print your file name here: experiment_data

Data Analysis for file: 'experiment_data.txt'
Number of readings: 6
Average value: 16.13
Median value: 16.15
Standard Deviation: 2.13
Maximum value: 19.00
Minimum value: 13.20

Would you like to analyze another file? (yes/no): no
Goodbye!

## Technical Skills Demonstrated

- **Python Fundamentals:** Functions, loops, conditionals, user input/output.
- **File I/O:** Reading and processing data from external files.
- **Data Cleaning:** String manipulation to handle different decimal formats.
- **Error Handling:** Comprehensive use of `try/except` blocks for robust operation.
- **Statistics:** Use of the `statistics` module to calculate advanced metrics.
- **Software Design:** Creating a logical, reusable function and a clear main program loop.

## Code

The main script is in [`lab_analyzer.py`](lab_analyzer.py).
