# Data Visualization

Data Visualization is a JavaScript library for creating various types of charts and plots to visualize data in web applications.

## Installation

You can install the Data Visualization library via npm:

```bash
npm install data-visualization
```

## Usage

```javascript
const DataVisualization = require('data-visualization');

// Sample data for visualization
const data = [10, 20, 30, 40, 50];
const options = { title: 'Sample Bar Chart' };

// Create a new DataVisualization instance
const dv = new DataVisualization(data, options);

// Render a bar chart
dv.renderBarChart();
```

### Available Charts

- `renderBarChart()`: Renders a bar chart.
- `renderLineChart()`: Renders a line chart.
- `renderPieChart()`: Renders a pie chart.
- `renderScatterPlot()`: Renders a scatter plot.

You can customize the data and options as per your requirements for each chart type.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
