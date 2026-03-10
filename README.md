# Healthcare Access and Emergency Demand in Nova Scotia

This project was developed for a **DataJam competition** to explore how healthcare accessibility affects emergency system pressure across Nova Scotia.

Our team analyzed whether **distance to hospitals and availability of primary care** may influence **emergency demand and response capacity** in different regions of the province.

## Research Question

**Do regions farther from hospitals and with fewer family doctors experience higher emergency demand and longer response times?**

## Approach

We combined multiple datasets from the **Nova Scotia Open Data Portal** and performed spatial analysis to:

- Calculate the **distance from communities to the nearest hospital**
- Aggregate accessibility metrics by **health zones**
- Compare healthcare access with **emergency department closure hours**

## Visualization Preview

![Healthcare Access Map](visuals/distance_map.png)
![Hist Plot](visuals/distance_map.png)
![ER Demand per 10k Residents vs Avg Dist Scatter Plot](visuals/distance_map.png)

## Key Insight

Regions with **greater distance to hospitals and limited primary care availability** may experience **higher strain on emergency services**, highlighting geographic disparities in healthcare access.

## Tools

- Python  
- Pandas  
- GeoPandas  
- Matplotlib  

## Results

The project received an **average score of 70/100** in the DataJam evaluation.

## Team

This project was led by me, with valuable support from:

- Alex Zhang  
- Luciana de Costa  
- Joyce Wong  
