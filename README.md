# olist-delivery-delay-analysis
Analysis of late deliveries in the Olist Brazilian e-commerce dataset
# Olist Delivery Delay Analysis

Analysis of late deliveries in the Brazilian E-Commerce dataset by Olist (~96k delivered orders, 2016–2018).

## Key findings
- **6.8%** of delivered orders arrived after the estimated delivery date.
- Most orders arrive **well before** the estimate, so the estimates are very conservative.
- Late orders get much worse reviews: **2.27★** vs **4.29★** for on-time orders.
- Late delivery is highest in **North-East states** (AL ~21%, MA ~17.5%, SE ~15%) and low in São Paulo (~4.5%).
- Delays spike in peak periods: **Nov 2017 (Black Friday)** and **Feb–Mar 2018**.

## Tools
Python, pandas, matplotlib, Google Colab

## Data
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), loaded in the notebook with `kagglehub`.
