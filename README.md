# README.md

--- 

# Mogral River Water Quality Index (WQI) 

Evaluation of the water quality of the Mogral River using the Weighted Arithmetic Water Quality Index method.

This repository archives the original undergraduate research project conducted at:

Department of Civil Engineering  
LBS College of Engineering Kasaragod  
APJ Abdul Kalam Technological University (KTU)  
Kerala, India  

Year: 2021

---

## Project Guide

Mrs. Anjali MS  
Assistant Professor  
Department of Civil Engineering  
LBS College of Engineering Kasaragod

---

## Study Overview

This study evaluates the physico-chemical characteristics of the Mogral River and computes the Water Quality Index (WQI) to assess its suitability for human use.

The Mogral River is a west-flowing river located in Kasaragod district, Kerala, India.  
It has an approximate length of **34 km** and a drainage area of **132 km²**.

The river basin supports agriculture, domestic water use, and local livelihoods. Increasing anthropogenic pressures such as domestic waste discharge, agricultural runoff, and sand mining have raised concerns regarding water quality.

The study integrates multiple physico-chemical parameters into a single indicator — the **Water Quality Index (WQI)** — to evaluate the overall condition of the river.

---

## Sampling Design

Water samples were collected from **24 sampling stations (S1–S24)** distributed along the Mogral River basin.

Sampling period:

- January 2021
- February 2021

Grab sampling techniques were used and laboratory analysis was conducted following standard procedures.

---

## Water Quality Parameters

The following physico-chemical parameters were analysed:

- Temperature
- pH
- Dissolved Oxygen (DO)
- Biological Oxygen Demand (BOD)
- Chloride
- Alkalinity

The results were compared with standards prescribed by:

- Bureau of Indian Standards (BIS)
- Surface water quality criteria

---

## Water Quality Index Method

The **Weighted Arithmetic Water Quality Index (WQI)** method proposed by **Horton (1965)** was used to compute water quality.

This method:

1. Assigns a **weight to each water quality parameter**
2. Converts measured values to **quality ratings**
3. Aggregates them into a **single index value**

Water quality classification used in the study:

-----------------------------------------------
| WQI Range | Water Quality           | Grade |
|-----------|-------------------------|-------|
| 0 – 25    | Excellent               | A     |
| 26 – 50   | Good                    | B     |
| 51 – 75   | Poor                    | C     |
| 76 – 100  | Very Poor               | D     |
| >100      | Unsuitable for drinking | E     |
-----------------------------------------------

---

## Key Findings

The analysis of water samples showed the following trends:

- Most upstream locations exhibited **good water quality**.
- Several midstream locations showed **moderate deterioration**.
- Downstream locations near the estuarine region recorded **extremely high chloride concentrations**, indicating **saline intrusion**.
- Certain stations showed **poor to very poor water quality**, primarily due to anthropogenic activities and sewage entry.

The results highlight the need for **continuous monitoring and improved waste management practices in the river basin**.

---

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

---

## Future Extensions

Planned improvements to the repository include:

- Extraction of full **raw datasets from the original report**
- Reproducible **Water Quality Index calculations**
- **GIS mapping of sampling stations**
- Spatial analysis of water quality trends
- Integration with **QGIS workflows**

---

## Authors

Department of Civil Engineering  
LBS College of Engineering Kasaragod  

- Abdul Faeem — KSD17CE001  
- Ahammed Misab CV — KSD17CE004  
- Ayishath Rusaina — KSD17CE020  
- Fathima AB — KSD17CE025  

Repository maintained by:  
Ayishath Rusaina

---

## License

This project is licensed under the  

**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**

See `LICENSE` for details.
