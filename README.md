# ETL and SQL Analysis on Energy Dataset

## Project Description
This project is a Jupyter Notebook that performs an **ETL (Extract, Transform, Load)** process and **SQL analysis** on a global energy dataset. The workflow includes:

- **Extract**: Loading raw energy data from sources covering 2000 to 2020.
- **Transform**: Cleaning and processing the data to ensure consistency and usability.
- **Load**: Storing the processed data into a SQLite database.
- **Analysis**: Conducting SQL queries to explore:
  - Total energy consumption trends.
  - Greenhouse gas emissions.
  - Per capita energy usage across regions.
- **Visualization**: Generating insightful charts and graphs to highlight key trends and findings.

## Chart Preview
![Chart Preview](./chart%20preview.png)

## Installation
Follow these steps to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/codewithbharat/ETL-and-SQL-Analysis-on-Energy-Dataset.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd ETL-and-SQL-Analysis-on-Energy-Dataset
   ```
3. **Install dependencies**:
   Create a `requirements.txt` file with the following packages:
   ```
   jupyter
   numpy
   pandas
   sqlite3
   matplotlib
   seaborn
   ```
   Then run:
   ```bash
   pip install -r requirements.txt
   ```
4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## Usage
- Open the `.ipynb` files in Jupyter Notebook.
- Run the cells sequentially to execute the ETL pipeline, SQL queries, and visualizations.
- Modify the code as needed for custom analysis or experimentation.

## Run in Google Colab
To explore this project in **Google Colab** and load the dataset directly, click the button below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/codewithbharat/ETL-and-SQL-Analysis-on-Energy-Dataset/blob/main/ETL_and_SQL_Analysis.ipynb)

> **Note**: Ensure you upload the dataset to your Google Drive or provide the correct dataset URL in the Colab notebook.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.
4. For significant changes, please open an issue first to discuss.

## License
This project is licensed under the [MIT License](LICENSE).