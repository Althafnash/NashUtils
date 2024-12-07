#  NashUtils

NashUtils is a lightweight, versatile Python utility library designed to simplify everyday programming tasks. It provides a collection of tools and modules to handle data manipulation, file conversions, and other common utility functions, helping developers streamline their workflows and write cleaner, more efficient code.

# CSV to JSON Converter
This project provides a Python script for converting CSV files into JSON format. It is designed to handle structured data efficiently and can be easily customized for different use cases.

## Features
- Converts CSV files to JSON format with ease.
- Handles large datasets.
- Simple and lightweight implementation.
  
- Clone the repository:
  ```bash
      git clone https://github.com/yourusername/csv-to-json-converter.git

- Download depedencies 
  ```bash
      pip install -r requirements.txt

- Running the script
  ```bash
  from Utils.CSV_to_JSON import csv_to_json
  
  Convetor = csv_to_json
  CSV = 'data.csv'
  JSON = 'data.json'
  Convetor.run(CSV,JSON)

