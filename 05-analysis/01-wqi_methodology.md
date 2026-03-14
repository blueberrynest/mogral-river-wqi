# Water Quality Index (WQI) Methodology

> Extracted from: *Evaluation of Water Quality Index for River Mogral (2021)*
> Source pages (PDF): 35–37

Water Quality Index (WQI) represents the overall quality of water using a single numerical value derived from multiple water quality parameters. It reflects the combined influence of different physicochemical parameters and provides a simplified method for communicating water quality status.

In this study, the **Weighted Arithmetic Water Quality Index method** proposed by Horton (1965) was used. The parameters considered were:

* pH
* Dissolved Oxygen (DO)
* Biochemical Oxygen Demand (BOD)
* Chloride
* Alkalinity

The index was calculated through the following steps.

## Step 1 — Unit Weight (Wi)

The unit weight of each parameter is inversely proportional to its recommended standard value.

[
W_i = \frac{K}{S_n}
]

Where:

* (W_i) = unit weight of the parameter
* (S_n) = standard permissible value
* (K) = proportionality constant

The constant (K) is calculated using:

[
K = \frac{1}{\sum (1/S_n)}
]

---

## Step 2 — Quality Rating (Qi)

The quality rating for each parameter is calculated using:

[
Q_i = \left( \frac{V_n - V_{ideal}}{S_n - V_{ideal}} \right) \times 100
]

Where:

* (Q_i) = quality rating of the parameter
* (V_n) = observed value of the parameter
* (V_{ideal}) = ideal value in pure water
* (S_n) = standard permissible value

Ideal values used:

* pH = 7.0
* DO = 14.6 mg/L
* Other parameters = 0

---

## Step 3 — Overall WQI

The final Water Quality Index is calculated as:

[
WQI = \frac{\sum (Q_i W_i)}{\sum W_i}
]

---

## Water Quality Classification

| WQI Range | Water Quality           | Grade |
| --------- | ----------------------- | ----- |
| 0–25      | Excellent               | A     |
| 26–50     | Good                    | B     |
| 51–75     | Poor                    | C     |
| 76–100    | Very Poor               | D     |
| >100      | Unsuitable for drinking | E     |
