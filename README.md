**🚀 Introduction to the Geospatial Embeddings Project**

The way we analyze Earth Observation (EO) data is undergoing a revolution. Traditional remote sensing workflows are often burdened by data complexity, requiring extensive preprocessing like cloud masking, atmospheric correction, and manual feature engineering across dozens of spectral bands and sensor types (e.g., optical, radar, climate). This complexity is a major bottleneck for global-scale, real-time environmental monitoring.

**The Embedding Solution**

This project leverages the power of Geospatial Embeddings, a cutting-edge approach that transforms massive, multi-modal EO data into concise, analysis-ready vectors. An embedding is a low-dimensional numerical vector (like the 64-dimensional vector in the AlphaEarth Embeddings) that acts as a semantically rich signature for every pixel on Earth. Crucially, these vectors capture not just surface appearance but also the underlying spatial and temporal context learned from years of multi-sensor data.

**Project Goal**

The primary objective is to demonstrate how these embeddings unlock faster, more scalable, and more accurate geospatial applications. By working in this simplified, consistent feature space, we can bypass the complexity of raw satellite imagery and focus directly on core analytical tasks.

**Applications**

The project will showcase several "cool" applications that are dramatically accelerated and improved by using the embedding space:

- Land Use/Land Cover (LULC) Classification: Training a classifier with minimal ground truth data (like ESA WorldCover labels) and achieving high-quality LULC maps across large, diverse regions.
- Similarity Search & Anomaly Detection: Instantly identifying locations on Earth that share similar environmental or human-use characteristics, or flagging areas where the embedding vector has changed significantly, indicating events like deforestation, urban sprawl, or wildfire impact.

In essence, this project is a demonstration of AI-powered pixels, proving that by encoding the planet's complexity into compact, intelligent vectors, we can generate custom, high-detail maps and insights on demand, enabling more informed decision-making on critical issues like food security and climate change.

***Notebooks***

-> notebooks/lulc-GEE.ipynb it shows how satellite embeddings can help to create LULC maps and highlight differences between consecutive years

-> notebooks/water-bodies-change-detection.ipynb it shows a practical application to map water bodies change as Lake Urmia in Iran

-> notebooks/crop_type_detection.ipynb it is a POC in which satellite embeddings are used to map crop type with very good results. More details abotu results are provided in docs/crop_type.md

## Licensing

### Software Code
All source code, scripts, and software components are licensed under 
**Apache License 2.0** - see [LICENSE_CODE](LICENSE_CODE).
