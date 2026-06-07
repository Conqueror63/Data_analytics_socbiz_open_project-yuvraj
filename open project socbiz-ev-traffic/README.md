# Agentic AI-Driven Dynamic Pricing Framework for EV Charging Infrastructure

**Open Project 2026 · Society of Business**

## Dataset Configuration

The datasets are not bundled with this repository since they were distributed separately through the competition's Google Drive.

Before executing the notebooks, organize the files using the following directory structure:

data/
├── raw/
│   ├── acn/
│   │   └── acndata_sessions.json.xlsx
│   └── st_evcdp/
│       ├── occupancy.csv
│       ├── volume.csv
│       ├── duration.csv
│       ├── price.csv
│       ├── time.csv
│       └── stations.csv

## Environment Setup

1. Create a virtual environment:
   `python -m venv venv`

2. Activate the environment:

   * Windows: `venv\Scripts\activate`
   * macOS/Linux: `source venv/bin/activate`

3. Install the required packages:
   `pip install -r requirements.txt`

## Notebook Execution Sequence

Run the notebooks in the following order:

1. `01_data_preparation.ipynb`
2. `02_exploratory_analysis.ipynb`
3. `03_demand_forecasting_agent.ipynb`
4. `04_dynamic_pricing_agent.ipynb`
5. `05_feedback_learning_agent.ipynb`

## Generated Outputs

The project automatically stores outputs in:

* `outputs/csvs/` — performance metrics, model evaluations, and result tables
* `outputs/plots/` — charts, graphs, and visual analytics
