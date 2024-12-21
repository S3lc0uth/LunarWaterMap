# Lunar Water Visualization

This project focuses on visualizing and analyzing remotely sensed data of the Bullialdus Crater on the Moon, sourced from Chandrayaan-1's Moon Mineralogy Mapper (M3). The dataset, provided in `.tif` format, is processed to explore potential water distribution and mineralogical features within the crater.  

Bullialdus Crater, located in the lunar near side's southern highlands, is a site of interest due to its mineral-rich composition, including pyroxenes and feldspars. The crater's geologic diversity makes it a prime candidate for studying water retention and lunar evolution.  

## Objectives  
- Process and analyze high-resolution spectral data of Bullialdus Crater.  
- Apply clustering and classification algorithms to identify water-rich regions.  
- Create engaging and interactive visualizations to represent the findings.  

## Dataset  
The data used in this project comes from the Moon Mineralogy Mapper (M3), which provided multi-band spectral imaging of the Moon during Chandrayaan-1’s mission. Specifically, the dataset focuses on the Bullialdus Crater, a region of interest for its unique mineralogical composition and potential traces of water.  

**Dataset**: Kaggle(https://www.kaggle.com/datasets/yash92328/lunar-water-discovery)  

## Methodology  
1. **Data Preprocessing**:  
   - Import `.tif` files and clean data for noise and redundancy.  
   - Extract spectral bands of interest for water detection.  

2. **Analysis**:  
   - Apply clustering algorithms (e.g., k-means) to group regions based on mineralogical and water content signatures.  
   - Perform statistical analysis to confirm patterns.  

3. **Visualization**:  
   - Generate 2D and 3D plots for spectral band intensity across the crater.  
   - Highlight water-rich regions using color-coded maps.  

## Tools & Technologies  
- **Programming Language**: Python  
- **Libraries**: Rasterio, NumPy, Pandas, Matplotlib, Seaborn, SciKit-Learn  
- **Visualization Frameworks**: Plotly 

## Results  
The analysis aims to reveal water-rich zones and unique mineralogical features within Bullialdus Crater, contributing to a deeper understanding of lunar resources and geologic history.  






