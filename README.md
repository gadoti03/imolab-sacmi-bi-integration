# ImoLab Sacmi BI Integration

## Overview
This project implements a data integration and business intelligence solution developed during the ImoLab Hackathon in collaboration with Sacmi.  
The goal is to consolidate data from multiple ERP systems, build a unified data model, and provide analytical dashboards in Power BI.

![Pagina 1](ImoLab_Sacmi_Pitch.pdf)

---

## Project Structure
```
.
├── data/                         # Raw and processed datasets
├── imolab-scami-pbi.pbip         # Power BI project file
├── ScreenRecording.zip           # Dashboard demo recording
└── README.md
```

---

## Data
The `data/` folder contains the datasets used for the BI model.  
These datasets are integrated into a Medallion architecture:
- Bronze: raw ingested data
- Silver: cleaned and standardized data
- Gold: aggregated KPI-ready tables

---

## Power BI Project
The main dashboard is available in:
```
imolab-scami-pbi.pbip
```

To open the project:
1. Open Power BI Desktop
2. Load the `.pbip` file
3. Ensure the `data/` folder path is correctly mapped if required

---

## Demo
<Screen recording of the application in action>

![Demo](ScreenRecording.gif)

> Demonstration of the Power BI dashboard integrated with multi-ERP data pipeline and KPI visualization

It shows:
- Dashboard navigation and insights

---

## Requirements
- Power BI Desktop (latest version recommended)
- Access to local dataset folder (`data/`)

---

## Author
Developed as part of ImoLab Hackathon collaboration with Sacmi.
