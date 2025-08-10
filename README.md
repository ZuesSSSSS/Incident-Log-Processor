# Incident Log Processor

A Python automation tool that ingests security incident logs (CSV/JSON), processes the data, and generates summary reports for faster decision-making.

## Features

- Reads CSV and JSON log formats
- Cleans and validates data entries
- Generates summary statistics (incident type counts, frequency over time)
- Outputs reports as CSV and PDF
- Configurable thresholds for high-priority alerts

## Tech Stack

- Python 3
- Pandas
- Matplotlib
- FPDF (for PDF reports)

## Usage

```bash
# Clone repository
git clone https://github.com/YOURUSERNAME/incident-log-processor.git
cd incident-log-processor

# Install dependencies
pip install -r requirements.txt

# Run script
python main.py logs.csv
