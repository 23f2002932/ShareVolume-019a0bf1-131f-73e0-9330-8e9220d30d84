# Cadence Design Systems Stock Data Fetcher

## Summary

This project retrieves and processes share data for Cadence Design Systems (CIK 0000813672) from the SEC's XBRL API. It filters for shares outstanding since the fiscal year 2021, identifies the maximum and minimum share values, and saves the results in a structured JSON format. Additionally, it provides a user-friendly HTML interface that displays this data dynamically.

## Setup Instructions

### Prerequisites

- Ensure you have a modern web browser for rendering the HTML page.
- Node.js installed on your machine if you want to run a local server or build tooling.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/cadence-design-systems-stock-data-fetcher.git
   cd cadence-design-systems-stock-data-fetcher
   ```

2. **Install dependencies** (if any available, not specified in the brief):
   ```bash
   npm install
   ```

3. **Run the data fetching script:**
   Use the command line to execute the data fetching script. This can be done using Node.js or directly in the browser's console depending on how you've set up the project.

4. **Open `index.html`:**
   Open the `index.html` file in any web browser. For testing with different CIKs, add `?CIK=0001018724` to the URL.

### Usage

Once you have the HTML file open in your browser, you will see the entity name, maximum shares value, maximum fiscal year, minimum shares value, and minimum fiscal year presented clearly. You can modify the URL query string to fetch data for different CIKs without needing to refresh the page.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.