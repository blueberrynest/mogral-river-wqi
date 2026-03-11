---

# README.md

# Mogral River Water Quality Index (WQI)

Evaluation of the water quality of Mogral River using the Weighted Arithmetic Water Quality Index method.

This repository archives the original undergraduate research project conducted at:

LBS College of Engineering Kasaragod  
APJ Abdul Kalam Technological University  
Department of Civil Engineering  

--- 

## Study Overview

This study evaluates the physico-chemical characteristics of the Mogral River and computes the Water Quality Index (WQI) to assess its suitability for human use.

The Mogral River is a west-flowing river in Kasaragod district, Kerala, India, with a length of approximately **34 km** and a drainage area of about **132 km²**.

## Sampling Design

Water samples were collected from **24 stations along the Mogral River basin** during:

- January 2021
- February 2021

## Water Quality Parameters

The following physico-chemical parameters were analysed:

- Temperature
- pH
- Dissolved Oxygen (DO)
- Biological Oxygen Demand (BOD)
- Chloride
- Alkalinity

## Water Quality Index Method

The **Weighted Arithmetic Water Quality Index (WQI)** method proposed by **Horton (1965)** was used.

The index integrates multiple water quality parameters into a single indicator representing the overall condition of the river water.

## Key Findings

- Most upstream locations showed **good water quality**.
- Downstream locations showed **very high chloride concentrations**, indicating **saline intrusion near the estuarine region**.
- Some stations exhibited **poor to very poor water quality**, mainly due to anthropogenic activities.

## Repository Structure

```
mogral-river-wqi
│
├── README.md
│
├── 01-study_area
│   ├── 01-basin_description.md
│   ├── 02-climate.md
│   ├── 03-geomorphology.md
│   └── 04-pollution_sources.md
│
├── 02-sampling_design
│   ├── 01-sampling_stations.csv
│   ├── 02-sampling_map.png
│   └── 03-sampling_strategy.md
│
├── 03-laboratory_methods
│   ├── 01-ph_measurement.md
│   ├── 02-dissolved_oxygen.md
│   ├── 03-bod_measurement.md
│   ├── 04-alkalinity.md
│   └── 05-chloride.md
│
├── 04-data
│   ├── 01-raw
│   │   ├── 01-january_2021.csv
│   │   └── 02-february_2021.csv
│   │
│   └── 02-processed
│       ├── 01-qi_january.csv
│       └── 02-wqi_february.csv
│
├── 05-analysis
│   ├── 01-wqi_methodology.md
│   ├── 02-parameter_weights.md
│   └── 03-calculation_tables.md
│
├── 06-results
│   ├── 01-parameter_analysis.md
│   ├── 02-chloride_intrusion.md
│   └── 03-spatial_wqi_pattern.md
│
├── 07-figures
│   ├── 01-study_area
│   ├── 02-pollution_sources
│   ├── 03-sampling_maps
│   ├── 04-fieldwork
│   └── 05-plots
│
└── 08-report
    └── original_report.pdf
```

## Future Work

Planned extensions of this repository include:

- extraction of raw datasets from the report
- reproducible WQI calculations
- GIS mapping of sampling stations
- spatial visualization of water quality trends

## Authors

**Group 12**  
Department of Civil Engineering  
LBS College of Engineering Kasaragod  

- ABDUL FAEEM (KSD17CE001)  
- AHAMMED MISAB CV (KSD17CE004)  
- AYISHATH RUSAINA (KSD17CE020) — Repository owner ([blueberrynest](https://github.com/blueberrynest))
- FATHIMA AB (KSD17CE025)

## License

Academic archive – original work preserved for educational and research reference.

---
