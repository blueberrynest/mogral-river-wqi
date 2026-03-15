# Mogral River Water Quality Index (WQI)

A structured research archive and reproducible dataset for the **Water Quality Index evaluation of the Mogral River, Kerala, India**, based on an undergraduate civil engineering research project conducted in **2021**.

This repository preserves the study’s datasets, methodology, analysis, and visual material in a structured format to support transparency, documentation, and future research.

---

# Project Information

**Institution**

Department of Civil Engineering
LBS College of Engineering Kasaragod
APJ Abdul Kalam Technological University (KTU)
Kerala, India

**Year of Study**

2021

**Project Guide**

Mrs. Anjali MS
Assistant Professor
Department of Civil Engineering
LBS College of Engineering Kasaragod

---

# Study Overview

This study evaluates the **physico-chemical water quality of the Mogral River** and assesses its suitability for human use using the **Weighted Arithmetic Water Quality Index (WQI)** method.

The Mogral River is a **west-flowing coastal river located in Kasaragod district, Kerala**, with:

* **River length:** ~34 km
* **Drainage basin area:** ~132 km²

The basin supports agriculture, domestic water use, and local livelihoods. Increasing anthropogenic pressures such as **domestic wastewater discharge, agricultural runoff, and sand mining** have raised concerns about the river’s water quality.

The Water Quality Index integrates multiple water quality parameters into a **single numerical indicator representing overall water condition**.

---

# Sampling Design

Water samples were collected from **24 sampling stations (S1–S24)** distributed along the Mogral River basin.

Sampling period:

* **January 2021**
* **February 2021**

Sampling involved grab collection methods followed by laboratory analysis using standard procedures.

Sampling station locations and spatial clustering are documented in:

```
02-sampling_design/
```

---

# Water Quality Parameters

The study analysed the following physico-chemical parameters:

* Temperature
* pH
* Dissolved Oxygen (DO)
* Biological Oxygen Demand (BOD)
* Chloride
* Alkalinity

Measured values were compared with water quality standards prescribed by:

* **Bureau of Indian Standards (BIS)**
* Surface water quality criteria.

---

# Water Quality Index Method

Water quality was evaluated using the **Weighted Arithmetic Water Quality Index method** proposed by **Horton (1965)**.

The method involves three steps:

1. Assigning a **unit weight (Wi)** to each parameter based on standard limits
2. Computing a **quality rating (Qi)** for each parameter
3. Aggregating weighted ratings to obtain a **single WQI value**

### Water Quality Classification

| WQI Range | Water Quality           | Grade |
| --------- | ----------------------- | ----- |
| 0 – 25    | Excellent               | A     |
| 26 – 50   | Good                    | B     |
| 51 – 75   | Poor                    | C     |
| 76 – 100  | Very Poor               | D     |
| >100      | Unsuitable for drinking | E     |

---

# Key Findings

The study identified spatial variation in water quality along the river:

* **Upstream locations** generally showed **good water quality**.
* **Midstream locations** exhibited moderate degradation.
* **Downstream stations near the estuary** recorded **very high chloride concentrations**, indicating **saline intrusion**.

Some stations exhibited **poor to very poor water quality**, influenced by anthropogenic activities and tidal effects.

The findings highlight the need for **continuous monitoring and improved waste management practices in the basin**.

---

# Repository Structure

This repository is organized to reflect the **scientific workflow of the study**.

```
mogral-river-wqi
│
├── README.md
├── LICENSE
│
├── 01-study_area
│   ├── basin description
│   ├── climate
│   ├── geomorphology
│   └── pollution sources
│
├── 02-sampling_design
│   ├── sampling station dataset
│   ├── sampling strategy
│   ├── sampling location descriptions
│   └── sampling maps
│
├── 03-laboratory_methods
│   ├── pH measurement
│   ├── dissolved oxygen measurement
│   ├── BOD measurement
│   ├── alkalinity measurement
│   └── chloride measurement
│
├── 04-data
│   ├── raw datasets
│   │   ├── january_2021.csv
│   │   └── february_2021.csv
│   │
│   └── processed datasets
│       ├── wqi_january.csv
│       └── wqi_february.csv
│
├── 05-analysis
│   ├── WQI methodology
│   ├── parameter weights
│   └── calculation tables
│
├── 06-results
│   ├── parameter analysis
│   ├── chloride intrusion discussion
│   └── spatial WQI pattern
│
├── 07-figures
│   ├── study area figures
│   ├── pollution source illustrations
│   ├── sampling maps
│   ├── fieldwork photographs
│   └── result visualizations
│
└── 08-report
    └── original_report.pdf
```

---

# Visual Archive

The repository includes a curated visual archive extracted from the original project report.

```
07-figures/
```

This directory contains:

* study area maps
* pollution source illustrations
* sampling location maps
* fieldwork photographs
* analysis figures

These assets document the spatial and environmental context of the study.

---

# Authors

Department of Civil Engineering
LBS College of Engineering Kasaragod

* Abdul Faeem — KSD17CE001
* Ahammed Misab CV — KSD17CE004
* Ayishath Rusaina — KSD17CE020
* Fathima AB — KSD17CE025

Repository maintained by:

**Ayishath Rusaina**

---

# License

This project is licensed under the

**Creative Commons Attribution–NonCommercial–ShareAlike 4.0 International License**

See the `LICENSE` file for details.
