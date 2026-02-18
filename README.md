# High-Dimensional Clustering Research

🌐 [Project page](https://nikolailen.github.io/high-dimensional-clustering/)

👤 Project contact: [Nikolai Len](https://www.linkedin.com/in/niklen/)

## Overview

This repository contains an **R** research project on high-dimensional data analysis and clustering.  
The workflow combines dimensionality reduction and unsupervised learning to study structure in station-level data.

## Documentation

- Main documentation: [GitHub Pages site](https://nikolailen.github.io/high-dimensional-clustering/)
- Source report: `high_dimensional_clustering_research.Rmd`
- Published page source: `index.md`

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
- `archive/legacy_report_2025.html` - archived legacy render
- `archive/legacy_report_2025.pdf` - archived legacy render
- `LICENSE` - MIT License

## Reproducibility (R)

Render the project page from the R Markdown source:

```bash
Rscript -e "rmarkdown::render('high_dimensional_clustering_research.Rmd', output_format = 'github_document', output_file = 'index.md')"
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
