# Field-boundary-detection-using-satelite-imagery
The project aims to integrate crop classification with field boundary detection for precision agriculture. This integration addresses the need for high-quality data to improve agricultural practices in Kenya, particularly in crop classification and field boundary delineation.The initial challenge was the scarcity of adequate, high-resolution data on crop fields, which is critical for accurate analysis. The project is structured in three key phases:
# Phase 1: Building a High-Resolution Cropland Dataset
In this phase, i created a high-resolution dataset specifically for Kenyan croplands by leveraging NDVI (Normalized Difference Vegetation Index), derived from satellite imagery. NDVI captures the unique growth patterns and seasonal stages of various crops, with each crop type exhibiting a distinct NDVI time series profile. This enables precise differentiation between crops based on their growth characteristics. Shapefiles of crop fields were extracted from Google Earth Pro, allowing us to construct a dataset that reflects crop variability and seasonality, providing a strong foundation for accurate analysis in subsequent phases.
![Screenshot from 2024-11-06 02-01-36](https://github.com/user-attachments/assets/c4381240-9f42-455a-855e-dbc2d01cc17f) ![Screenshot from 2024-11-06 02-03-17](https://github.com/user-attachments/assets/d0bbe922-8c74-4f85-b438-ae6d054e4df6)
# Phase 2: Crop Classification
Building on the dataset from Phase 1, this phase focuses on classifying different crop types using machine learning algorithms. By analyzing crop-specific features within the dataset,  i applied classification models to distinguish between crop types effectively.
# Phase 3: Integrating Crop Classification with Field Boundary Detection
The final phase combines crop classification results with field boundary detection algorithms, enabling precise delineation of field boundaries. This integration is essential for monitoring crop health and managing resources effectively in precision agriculture.


