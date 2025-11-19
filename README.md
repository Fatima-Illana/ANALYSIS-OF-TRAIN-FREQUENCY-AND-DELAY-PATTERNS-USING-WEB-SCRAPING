# ANALYSIS OF TRAIN FREQUENCY AND DELAY PATTERNS USING WEB SCRAPING

This project uses web scraping to collect and analyze data on medium- and long-distance trains from Renfe. It gathers schedules, arrivals, and delays at different stations using web scraping techniques and stores the data in a CSV file. The results are then visualized through charts to identify usage and delay patterns.

## Objective

The objective of this project is to analyze which types of medium- and long-distance trains are most frequently used and which experience the longest delays at different Renfe stations. Using this information, visualizations are created to facilitate the analysis of train punctuality and frequency trends.

## Web Scraping Process Preview

<img src="./Graficas/PrevisualizacionWebScraping.png" alt="Web Scraping Process Preview" width="1000"/>

## Results Preview

<img src="./Graficas/PrevisualizacionResultados1.png" alt="Results Preview 1" width="1000"/>

<img src="./Graficas/PrevisualizacionResultados2.png" alt="Results Preview 2" width="1000"/>

## Project Structure

```text

🚅 ANALYSIS OF TRAIN FREQUENCY AND DELAY PATTERNS USING WEB SCRAPING
├── 📁 Datos
│       → Folder where the generated CSV files with extracted data are stored.
│       → 🟩 CSVAcumulativo.csv: A CSV file that compiles the results of running 'VariasEstacionesWebScraping.py' over multiple days. This CSV is used for the final analysis to include more data from several days.
├── 📁 Graficas
│       → Folder where the visualizations generated from the data are stored.
├── 🐍 HorariosRenfeWebScraping.py
│       → Python script that performs web scraping of data from a single Renfe station page and stores it in the file 'HorariosLargaDistancia.csv'.
├── 🐍 VariasEstacionesWebScraping.py
│       → Python script that performs web scraping of multiple station pages and stores the data in 'HorariosLargaDistancia2.csv'.
├── 🐍 GraficasAnalisis.py
│       → Python script that analyzes the data and generates the final charts.
├── 📄 README.md
│       → Documentation of the project.
└── 🟥 InformeAnalisisRenfe.pdf
        → Report that visually shows the data extraction process and the final charts.
```

This content is only available in spanish.

## Requirements

To run this project, you need:

- **Python 3.x**
- Python libraries:
  - `Driver` (to enable interaction with a web browser, in this case Chrome)
  - `Selenium` (for data extraction via web scraping)
  - `BeautifulSoup` (for HTML parsing)
  - `pandas` (for data manipulation)
  - `matplotlib` (for data visualization)
 
## Author

- [Fátima Fuchun Illana Guerra](https://github.com/Fatima-Illana)
