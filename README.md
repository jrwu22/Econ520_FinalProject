# Final Project ECON 520

## Description
This repository contains the R Markdown document and dataset for the final project of ECON 520. The project conducts a detailed analysis of salary data, showcasing data manipulation and visualization techniques using R. The analysis explores various aspects of salary distributions and trends over time.

## Files
- `Econ520_final_Jingrui Wu.Rmd`: Main project file containing all the code and documentation.

## Code Overview
The code within the R Markdown document includes:
- **Data Loading:** The dataset `salaries.csv` is loaded into R using `read.csv`.
- **Data Manipulation:** Uses `dplyr` to filter, summarize, and manipulate salary data.
- **Visualization:** Generates multiple plots using `ggplot2` to visualize trends and distributions in the data. This includes histograms, scatter plots, and time series graphs.
- **Scaling:** Adjusts plot scales and themes using `scales` and `ggplot2` to improve readability and aesthetics.

## Requirements
To run the R Markdown document, you will need R installed on your machine along with the following R packages:
- `dplyr`
- `ggplot2`
- `scales`

You can install these packages using the following R command:
```R
install.packages(c("dplyr", "ggplot2", "scales"))
```

## Usage
To run this document, open it in RStudio and run the chunks sequentially or knit the document to produce an HTML output.

## Contributing
Feel free to fork this repo and submit pull requests with improvements or additional analyses.

## Author
- Jingrui Wu

## License
This project is licensed under the MIT License - see the LICENSE file for details.

