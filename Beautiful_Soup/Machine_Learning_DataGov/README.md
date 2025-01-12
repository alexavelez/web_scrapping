# Machine Learning Datasets Scraper from Data.gov

This project involves scraping information about machine learning datasets from [Data.gov](https://data.gov/), the official open data platform of the United States government. Data.gov currently hosts over 307,958 datasets, and this project extracts specific details about datasets related to machine learning using Python.

## Project Overview
The script uses Python libraries `requests` and `BeautifulSoup` to scrape dataset information, including:
- **Dataset Name**
- **Description**
- **Resorce Type**
- **Metadata Creation Date**
- **Identifier**
- **DOI**
- **Publisher**
- **Maintainer**
- **@ Id**
- **Data Last Modified**
- **Public Access** (Yes/No)
- **Data First Published**

The program is implemented in a Jupyter Notebook, which provides an interactive environment for running the script and viewing the results.

## Features
1. **Link Retrieval**: Collects the links to machine learning-related datasets on Data.gov.
2. **Dataset Scraping**: Extracts details for each dataset using the collected links.
3. **Periodic Updates**: The script is designed to run periodically, ensuring the dataset information remains up to date as new datasets are added to the platform.

## Requirements
The following Python libraries are required:
- `requests`
- `BeautifulSoup4`
- `pandas`
- `jupyter`

Install the dependencies using pip:
```bash
pip install requests beautifulsoup4 pandas notebook
```
The dependencies can be installed using Anaconda as well.

## Output
The script generates a csv file with the structured information containing details about machine learning datasets in data.gov

## License
This project is licensed under the [Creative Commons Zero v1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).

## Acknowledgments
- Data sourced from [Data.gov](https://data.gov/).
