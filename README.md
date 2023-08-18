
# MPG Cars Data Analysis

This project involves the analysis of MPG cars data using Python and the Pandas library. The dataset is sourced from the UC Irvine Machine Learning Repository and includes information about different cars' attributes.

## Project Overview

This repository contains Python code for analyzing MPG cars data using the Pandas library. The analysis includes steps to import two datasets, clean and merge them, and add a new column. The primary goals of this project are:

- Import the necessary libraries for data analysis.
- Import the first dataset (cars1) and the second dataset (cars2) from specified URLs.
- Assign each dataset to variables called cars1 and cars2.
- Handle unnamed blank columns in the first dataset (cars1).
- Determine the number of observations in each dataset.
- Join the two datasets into a single DataFrame called cars.
- Create a random number Series for the 'owners' column.
- Add the 'owners' column to the cars DataFrame.

## Analysis Steps

1. Import the required libraries, including Pandas and NumPy.
2. Import the first dataset (cars1) and the second dataset (cars2) from provided URLs.
3. Assign each dataset to variables called cars1 and cars2.
4. Drop unnamed blank columns from the first dataset (cars1).
5. Calculate the number of observations in each dataset.
6. Join the two datasets into a single DataFrame called cars using `pd.concat`.
7. Generate a random number Series for the 'owners' column using `np.random.randint`.
8. Add the 'owners' column to the cars DataFrame.

## Repository Structure

```
MPG-Cars-Data-Analysis/
│
├── mpg_cars_analysis.ipynb  # Jupyter Notebook containing analysis code
└── readme.md                # Project overview and details
```

## Usage

1. Clone the repository using: `git clone https://github.com/your-username/MPG-Cars-Data-Analysis.git`
2. Navigate to the repository: `cd MPG-Cars-Data-Analysis`
3. Open the `mpg_cars_analysis.ipynb` notebook to access the detailed analysis steps and results.

## Acknowledgments

- Special thanks to the source that provided the MPG cars dataset for this analysis.
- Appreciation to the creators and contributors of the Pandas and NumPy libraries for empowering data analysis.

---

