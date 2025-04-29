# VM Monitoring Dashboard (Python)

This project simulates the analysis of virtual machine (VM) health and performance in a cloud infrastructure setting using Python. 
It's designed to demonstrate practical skills in cloud resource monitoring, data analysis, and reporting.

## Project Overview

- Simulated dataset of virtual machines across different regions
- Analyzed key metrics: CPU/Memory utilization, uptime, patching, and cost
- Identified performance issues
- Produced summary reports for critical VMs

## Key Features

- KPI calculations for average CPU, uptime, and total cost
- Visualization of:
  - VM distribution by region and status
  - CPU usage trends
  - Uptime distribution
  - Correlation matrix of performance metrics
- Highlighted:
  - Idle VMs (low uptime)
  - Over-utilized VMs (CPU > 85%)
  - Outdated patching (older than 30 days)

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Simulated data generated manually

## Sample Visuals
- Seen in the `images` folder

## Future Ideas

- Integrate with real Azure Monitor data using APIs
- Auto-refresh with scheduler scripts (e.g. using `cron` or `Airflow`)
- Add basic alert system for flagged VMs

## Files

- `vm_monitoring_analysis.ipynb` – full notebook with logic and visuals
- `vm_monitoring_dataset.csv` – base dataset

Built as part of my career transition into cloud/data center roles.
