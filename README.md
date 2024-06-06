# COVID-19's Influence on Global Socio-Economic Landscape

This project was conducted for the practical project for the Smart Analysis in Big Data Systems course within the Master's in Computer Engineering program at the University of Minho. It aims to analyze the impact of the COVID-19 pandemic on various socio-economic variables, including **Inflation**, **Migration**, **Gross Domestic Product** (GDP), **Unemployment**, **Population**, **Tax rates** and **COVID-19** statistics. The analysis is conducted on a global scale, with a specific focus on **G8** and **G20** countries as well as different **Continents**. Utilizing comprehensive datasets and advanced data processing tools such as **Pandas** and **Apache Spark**, the project derives meaningful insights into these variables and their interrelations during the pre-pandemic period and the pandemic period as well.

## Team Members
- **PG50380** - Francisco Claudino
- **PG53597** - Afonso Bessa

- ## Index of Contents

### `Documents`: Contains the Article, the Report and the PowerPoint Presentation

- **`Article.pdf`**: Is the Article of this project.
- **`Report.pdf`**: Is the Report of this project.

### `MongoDB`: Contains a Notebook for Data Extraction to MongoDB

- **`LoadMongoDB.ipynb`**: Jupyter Notebook to extract data and load it into a MongoDB database.

### `PowerBI`: Contains the Power BI Dashboard for Data Visualization

- **`BigData.pbix`**: Power BI dashboard file for visualizing the impact of COVID-19 on various Socio-Economic .

### `PreProcessing`: Contains All PreProcessing Work

- **`ProcessingAllInOne.ipynb`**: Notebook for preprocessing all data using Pandas.
- **`ProcessingAllInOneSpark.ipynb`**: Notebook for preprocessing all data using Apache Spark.

#### `Files`: Contains Raw Data Extracted from Various Sources

- **`Inflation.xlsx`**: Raw data on inflation rates.
- **`Migration.csv`**: Raw data on migration statistics.
- **`Tax.csv`**: Raw data on tax rates.
- **`Covid.csv`**: Raw data on COVID-19 statistics.
- **`Population.csv`**: Raw data on population statistics.
- **`Unemployment.csv`**: Raw data on unemployment rates.
- **`GDP.csv`**: Raw data on GDP statistics.

#### `FilesParquet`: Contains Preprocessed Data in Parquet Format

- **`Population.parquet`** : Preprocessed population data.
- **`GDP.parquet`** : Preprocessed GDP data.
- **`Inflation.parquet`** : Preprocessed inflation data.
- **`Tax.parquet`** : Preprocessed tax data.
- **`Covid.parquet`** : Preprocessed COVID-19 data.
- **`Migration.parquet`** : Preprocessed migration data.
- **`Unemployment.parquet`** : Preprocessed unemployment data.

#### `FinalAllInOneParquet`: Contains Datasets Merged by Country in a Single Parquet File

#### `FinalFiles`: Contains Final Preprocessed Data Files in Various Formats

- **`Migration.csv`**: Final preprocessed migration data.
- **`Tax.csv`**: Final preprocessed tax data.
- **`Covid.csv`**: Final preprocessed COVID-19 data.
- **`Population.csv`**: Final preprocessed population data.
- **`Inflation.csv`**: Final preprocessed inflation data.
- **`Unemployment.csv`**: Final preprocessed unemployment data.
- **`GDP.csv`**: Final preprocessed GDP data.

#### `FinalParquet`: Contains Separately Preprocessed Merged Datasets in Parquet Format

#### `PreProcessedFiles`: Contains Both Preprocessed Merged Datasets

- **`FinalFilePP.csv`**: Preprocessed merged dataset (processed separately).
- **`FinalFile.csv`**: Preprocessed merged dataset (processed together).

#### `ProcessingFiles`: Contains Notebooks for Preprocessing Individual Datasets using Pandas and for Merging

- **`MergeFilesPP.ipynb`**: Notebook for merging preprocessed files.
- **`ProcessingGDP.ipynb`**: Notebook for preprocessing GDP data.
- **`ProcessingUnemployment.ipynb`**: Notebook for preprocessing unemployment data.
- **`ProcessingInflation.ipynb`**: Notebook for preprocessing inflation data.
- **`ProcessingCovid.ipynb`**: Notebook for preprocessing COVID-19 data.
- **`ProcessingTax.ipynb`**: Notebook for preprocessing tax data.
- **`ProcessingPopulation.ipynb`**: Notebook for preprocessing population data.
- **`ProcessingMigration.ipynb`**: Notebook for preprocessing migration data.

#### `ProcessingFilesSpark`: Contains Notebooks for Preprocessing Individual Datasets using Apache Spark and for Merging

- **`ProcessingCovidSpark.ipynb`**: Notebook for preprocessing COVID-19 data.
- **`ProcessingGDPSpark.ipynb`**: Notebook for preprocessing GDP data.
- **`MergeFilesSpark.ipynb`**: Notebook for merging files.
- **`ProcessingTaxSpark.ipynb`**: Notebook for preprocessing tax data.
- **`ProcessingUnemploymentSpark.ipynb`**: Notebook for preprocessing unemployment data.
- **`ProcessingPopulationSpark.ipynb`**: Notebook for preprocessing population data.
- **`ProcessingMigrationSpark.ipynb`**: Notebook for preprocessing migration data.
- **`ProcessingInflationSpark.ipynb`**: Notebook for preprocessing inflation data.

## Technologies Used

- **Pandas**: A powerful Python library for data manipulation and analysis.
- **Apache Spark**: An open-source unified analytics engine for large-scale data processing.
- **MongoDB**: A NoSQL database known for its high performance and easy scalability, used for storing and retrieving large volumes of data.
- **Microsoft Power BI**: A business analytics service that provides interactive visualizations and business intelligence.
