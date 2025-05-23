# Air Quality and Storm Tide Data Analysis

This repository contains Jupyter notebooks and data files for exploring air quality and storm tide data, including working with XML and JSON APIs, and exporting processed data to CSV.

## Purpose

This project was built as an experiment to explore consuming apis in both JSON and XML formats and to serve a quick personal reference

## Repository Structure

- `Air Quality Data XML.xml` — Example XML file with air quality data for Queensland, Australia.
- `json_api_notebook.ipynb` — Jupyter notebook for fetching and processing storm tide data from a JSON API.
- `storm_tide_data.csv` — CSV output generated from the JSON API notebook.
- `xml_api_notebook.ipynb` — Jupyter notebook for exploring air quality data from an XML API (note: API endpoint is outdated, see below).
- `xml_file_notebook.ipynb` — Jupyter notebook for parsing the local XML file and exporting selected data to CSV.
- `xmloutairquality.csv` — CSV output generated from the XML file notebook.

## Requirements

- [Jupyter Notebook](https://jupyter.org/install) (install via `pip install notebook` or `conda install notebook`)
- Alternatively, you can use the [Jupyter extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) for an integrated experience.
- Python 3.6 or higher
- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/) (`pip install beautifulsoup4`)

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/joncaudill/air-quality-storm-tide-data.git
   cd air-quality-storm-tide-data
   ```

2. **Install dependencies:**
   ```sh
   pip install notebook beautifulsoup4
   ```

3. **Launch Jupyter Notebook:**
   - Traditional way:
     ```sh
     jupyter notebook
     ```
   - Or, open the folder in Visual Studio Code and use the Jupyter extension to run and edit notebooks.

4. **Open and run the notebooks:**
   - `json_api_notebook.ipynb` — Fetches storm tide data from a JSON API and exports to CSV.
   - `xml_file_notebook.ipynb` — Parses the local XML file and exports air quality data to CSV.
   - `xml_api_notebook.ipynb` — (Note: The API endpoint is outdated; use the local XML file as shown in `xml_file_notebook.ipynb`.)

## Notes

- The XML API endpoint referenced in `xml_api_notebook.ipynb` is no longer available. Use the local file workflow in `xml_file_notebook.ipynb` for air quality data analysis.
- Output CSV files are generated in the repository root.

## License

This project is provided for educational purposes.

---

GitHub: [joncaudill](https://github.com/joncaudill)