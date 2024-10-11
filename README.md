# Cruise Ship Performance Analysis

This project focuses on analyzing the performance trends of two cruise ships, **Vessel 1** and **Vessel 2**, over time. The analysis considers key performance indicators (KPIs) related to power consumption, fuel flow rates, wind speed, propulsion, and other operational metrics. The goal is to develop a narrative explaining performance trends, focusing on regulatory compliance and efficiency improvements.

## Project Structure

- **processe_vessel_data/**: Contains raw and processed datasets for both vessels.
- **notebooks/**: Jupyter notebooks for data exploration, analysis, and visualization.
- **scripts/**: Python scripts used for data processing and model building.
- **results/**: Outputs, charts, and final KPIs.
- **README.md**: Project overview and instructions.
- **requirements.txt**: List of Python dependencies.

## Key Performance Indicators (KPIs)

- **Power Consumption**: Power used by different subsystems (galley, HVAC, propulsion, etc.)
- **Fuel Flow Rates**: Fuel consumption by boilers and main engines.
- **Propulsion Power**: Propulsion power split between port side, starboard side, and thrusters.
- **Wind Data**: Relative and true wind angles and speeds.
- **Speed**: Speed over ground and through water.
- **Efficiency**: A measure of the overall operational efficiency based on the above metrics.

## Analysis Steps

1. **Data Loading**: Load the dataset and preprocess for missing values and outliers.
2. **Feature Engineering**: Create new features such as total power consumption and fuel efficiency.
3. **KPI Calculation**: Calculate KPIs like total fuel flow, efficiency, and wind impact.
4. **Visualization**: Use charts and plots to identify trends and anomalies in the data.
5. **Report Generation**: Summarize findings with visualizations and explanations in a final report.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/username/cruise-ship-performance-analysis.git
    cd cruise-ship-performance-analysis
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis:
    - You can use Jupyter notebooks located in the `notebooks/` folder to explore the data and execute the analysis step-by-step.

## Datasets

The data used in this project includes:
- **Vessel 1**: Performance data over a specific period, including power usage, fuel flow, wind conditions, etc.
- **Vessel 2**: Performance data over a similar time frame, allowing for comparative analysis.

## Results

The results will include:
- **KPI trends**: Graphs showing power consumption, fuel flow rates, propulsion power, and other KPIs.
- **Efficiency Analysis**: Insights into how the vessels' performance can be optimized.

## Contributing

Feel free to fork this project, make your changes, and submit a pull request.
