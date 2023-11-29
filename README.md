# EU-PowerDataFetcher

This Python script efficiently fetches energy data from the European Network of Transmission System Operators for Electricity (ENTSO-E). Utilizing the `entsoe` Python package, it gathers various types of energy data including day-ahead prices, demand, generation, installed generation capacity, and hydro storage data.

## Key Features:

- **Dynamic Data Querying**: Capable of fetching data for multiple European countries with specified time ranges.
- **Error Handling**: Each data type query is encapsulated in individual `try-except` blocks, ensuring continuous operation even in the event of partial failures.
- **Data Storage**: Efficiently stores fetched data into structured CSV files for each country and data type, facilitating easy access and further analysis.
- **Scalability**: Easily scalable to include more countries or different types of energy data from the ENTSO-E API.

## Usage:

Users can specify the desired country codes and date ranges, and the script will handle fetching and storing the relevant data.

This tool is ideal for researchers, data analysts, and enthusiasts in the field of energy data analysis, providing a way to access and analyze European energy market data.
