# React.js Charting Application

This project is a React.js application that displays a chart using the `recharts` library. The chart supports timeframe breakdown (daily, weekly, monthly), zooming, and interactive click events. It also includes functionality to export the chart as PNG or JPG.

## Features

- Timeframe breakdown (daily, weekly, monthly)
- Timeframe zooming
- Interactive click events to display details of the clicked data point
- Export the chart as PNG or JPG formats
- Responsive and user-friendly UI

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/charting-app.git
    cd charting-app
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

    The application will be available at `http://localhost:3000`.

## Usage

1. The application will automatically fetch the chart data from `public/data.json`.

2. You can switch between different timeframes (daily, weekly, monthly) using the buttons provided.

3. Click on any point in the chart to see details about that data point.

4. Use the "Export as PNG" or "Export as JPG" buttons to save the chart as an image.

## Project Structure

- `public/data.json`: JSON file containing the chart data.
- `src/App.js`: The main React component that renders the chart.
- `src/Chart.js`: Component containing the chart logic and UI.
- `src/Chart.css`: CSS file for styling the chart and buttons.

## Example Data

An example of the JSON data structure in `public/data.json`:
```json
[
  { "timestamp": "2023-01-01T00:00:00Z", "value": 10 },
  { "timestamp": "2023-01-02T00:00:00Z", "value": 12 },
  { "timestamp": "2023-01-03T00:00:00Z", "value": 5 },
  ...
]
