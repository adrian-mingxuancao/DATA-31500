# Illegal Animals as Pets in NYC - Data Visualization Project

This project visualizes data on illegal animals kept as pets across New York City, mapped by census regions. It uses **D3.js** and **Svelte** to create an interactive experience that highlights the distribution of incidents by specific animal types, including **Snake**, **Roosters**, and **Farm Animals**.

## Features

- **Choropleth Map**: A color-coded map of NYC displaying the distribution of illegal animal incidents by population density across regions.
- **Interactive Histograms**: Three separate histograms illustrate the frequency of incidents for Roosters, Farm Animals, and Snakes, which is the three most common illegal animals as pet in NYC. Users can filter data by specific ranges for each animal type.
- **Dynamic Legend**: The legend adjusts based on data distribution, displaying both minimum and maximum values in each color range for better interpretability.

## Data

The data includes various types of illegal animals reported as pets within NYC, categorized by:
- **Animal Types**: Roosters, Farm Animals, and Snakes among others.
- **Incident Counts**: Aggregated counts per census region, representing the population of illegal animals.

## Technologies Used

- **Svelte**: Provides a reactive framework for building user interfaces.
- **D3.js**: Used for data-driven document manipulation, scales, and creating visualizations.
- **GeoJSON**: Represents NYC's geographic boundaries for census regions, used in the map.

## Project Setup

1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

## Project Goals

This visualization aims to provide insights into the spatial patterns of illegal pet ownership in NYC, highlighting trends by animal type and frequency across regions. It can be a valuable tool for policymakers and researchers interested in understanding and addressing illegal pet ownership.

## License

This project is licensed under the MIT License.

This `README.md` provides an overview of the project, its features, data, and technologies used, along with setup instructions and goals. Let me know if you’d like to add or adjust any specific details!