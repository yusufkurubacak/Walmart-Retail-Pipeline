# Walmart Retail Data Pipeline

&nbsp;This repository contains a Jupyter notebook containing custom functions to extract, transform, aggregate, load and validate a sample e-commerce data and 2 source datasets in the form of CSV and Parquet, can be found in 'datasets/' folder.  
&nbsp;With custom functions defined in the notebook, several pipeline steps can be conducted seamlessly and quickly which is crucial for stream processing data operations.

## About the Dataset
&nbsp;In this project, 2 datasets were used.  
First one, 'grocery_sales.csv', contains following features:

- "index" - unique ID of the row
- "Store_ID" - the store number
- "Date" - the week of sales
- "Weekly_Sales" - sales for the given store

Second one,'extra_data.parquet', contains following features:

- "IsHoliday" - Whether the week contains a public holiday - 1 if yes, 0 if no.
- "Temperature" - Temperature on the day of sale
- "Fuel_Price" - Cost of fuel in the region
- "CPI" – Prevailing consumer price index
- "Unemployment" - The prevailing unemployment rate
- "MarkDown1", "MarkDown2", "MarkDown3", "MarkDown4" - number of promotional markdowns
- "Dept" - Department Number in each store
- "Size" - size of the store
- "Type" - type of the store (depends on Size column)

## Project Overview

&nbsp;This project includes pipeline stages to perform streaming data operations in an automated method.  
Steps of the project are as follows:

- Importing Libraries
- Initial Exploration
- Data Extraction and Integration
- Data Transformation
- Data Aggregation
- Data Exportation
- Data Validation

## How to Use
&nbsp;You can run the project by cloning it or downloading the files on your local machine. It is recommended to use a Python development environment such as Jupyter Notebook or Anaconda. By running the project files or examining the visualizations, you can learn more about the dataset.

```bash
git clone https://github.com/yusufkurubacak/Walmart-Retail-Pipeline.git
```

## Contributing
&nbsp;If you would like to contribute to this project, please fork it and make your changes. Then submit a pull request to propose your changes. Any contributions and feedback are welcome.

## License
&nbsp;This project is licensed under MIT. For more information, see the LICENSE file.

## Contact
&nbsp;If you have any questions or feedback about the project, feel free to contact me at yusufkurubacakk@gmail.com.



