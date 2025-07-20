# Precipitation Temporal Clustering Analysis  using Python API (Xee) for Sinharaja, Sri Lanka

## Overview
This project analyzes long-term monthly precipitation patterns (2000–2025) over the Sinharaja Rainforest region, one of the wettest zones in Sri Lanka, using NASA GPM IMERG V07 satellite data. The analysis applies unsupervised clustering (K-Means) to categorize precipitation into distinct intensity classes such as heavy, high, moderate, and low rainfall periods.

Understanding temporal rainfall behavior in this biodiverse and hydrologically critical zone is essential for:
- Rainfall pattern monitoring
- Water resource management
- Forest ecosystem protection
- Agricultural planning and climate resilience modeling

This project demonstrates how Earth Engine + Xarray (via xee) and machine learning can be used for climate classification in data-scarce regions like Sri Lanka.

## Data Sources
Precipitation: NASA/GPM_L3/IMERG_MONTHLY_V07
- Monthly precipitation (mm/hr) reprocessed and scaled to approximate mm/month.

### Monthly Precipitation Clustering over Sinharaja Region (2000–2025)
<img width="1625" height="505" alt="image" src="https://github.com/user-attachments/assets/2cd54047-fcfb-4af3-989e-367c1318aeea" />

## Notes
1. K-Means clustering assumes roughly spherical clusters. It may not fully capture seasonal transitions or irregular rainfall patterns.
2. You can modify the number of clusters or try other clustering methods like DBSCAN or Gaussian Mixture Models for comparison.
3. GPM monthly data is originally in mm/hr. This script approximates mm/month by multiplying by 730 (average hours per month). For more precision, use actual monthly hour counts.
   








