# Dify Retrieval Test

This repository contains the analysis code and data for testing Dify's retrieval precision and robustness.

## Project Structure

### Notebooks
- `Sampling.ipynb`: Contains the code for sampling and testing retrieval results
- `Analysis.ipynb`: Contains the analysis of retrieval results and performance metrics

### Data Files
The repository includes several CSV files containing test data and results:

#### Retrieval test results 
- `document_list_0.14.2_automatic.csv`
- `document_list_0.14.2_custom.csv`
- `document_list_1.2.0_automatic.csv`
- `document_list_1.2.0_custom.csv`
- `document_list_0.14.2_automatic_title_in_contnent.csv`
- `document_list_0.14.2_custom_title_in_contnent.csv`
- `document_list_1.2.0_automatic_title_in_contnent.csv`
- `document_list_1.2.0_custom_title_in_contnent.csv`
- `document_list_with_subcategories_v2.csv`

#### Retrieval test results with business names or problem types varied
- `bn_pt_0.14.2_automatic.csv`
- `bn_pt_0.14.2_custom.csv`
- `bn_pt_1.2.0_automatic.csv`
- `bn_pt_1.2.0_custom.csv`

## Usage

1. Clone this repository
2. Open the Jupyter notebooks in your preferred environment
3. Follow the instructions in the notebooks to run the analysis

## Requirements

- Python 3.9.7
- Jupyter Notebook
- Required Python packages (listed in the notebooks)

## Notes

- The notebooks contain detailed comments and explanations
- Make sure to set up your environment variables for API access
- Some files may require specific permissions or access rights

## License

This project is licensed under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication. 
