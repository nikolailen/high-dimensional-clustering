# High-Dimensional Clustering Research

🌐 [Project page](https://nikolailen.github.io/high-dimensional-clustering/)

👤 Project contact: [Nikolai Len](https://www.linkedin.com/in/niklen/)

## Overview

This repository contains an **R** research project on high-dimensional data analysis and clustering.  
The workflow combines dimensionality reduction and unsupervised learning to study structure in station-level data.

Datasets used:
- `data/high_dimensional_station_data.RData`: main high-dimensional station dataset (1,189 observations, 181 features in `velib$data`, plus station coordinates in `velib$position`).
- `data/synthetic_cluster_points.csv`: small synthetic 2D dataset used to demonstrate k-means clustering behavior.

## Methods

- Principal Component Analysis (PCA)
- Hierarchical clustering (complete linkage)
- k-means clustering and elbow-style model selection

## Repository Structure

- `high_dimensional_clustering_research.Rmd` - main R Markdown research report
- `index.md` - GitHub Pages entry document
- `index_files/` - generated figures for markdown publication
- `data/high_dimensional_station_data.RData` - high-dimensional station dataset
- `data/synthetic_cluster_points.csv` - synthetic 2D dataset used in the k-means demonstration
- `LICENSE` - MIT License

## Reproducibility (R)

Render the project page from the R Markdown source:

```bash
Rscript -e "rmarkdown::render('high_dimensional_clustering_research.Rmd', output_format = 'github_document', output_file = 'index.md')"
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
