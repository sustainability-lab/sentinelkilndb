# SentinelKilnDB Website

This repository contains the Quarto website for the SentinelKilnDB dataset, accepted at NeurIPS 2025.

## About

**SentinelKilnDB** is a large-scale dataset and benchmark for oriented bounding box (OBB) brick kiln detection in South Asia using Sentinel-2 satellite imagery. The dataset contains 62,671 hand-validated brick kilns across 2.8 million km² spanning India, Bangladesh, Pakistan, and Afghanistan.

## Website Structure

- `index.qmd` - Main landing page with overview and abstract
- `dataset.qmd` - Detailed dataset information and download links
- `benchmark.qmd` - Model performance results and comparisons
- `applications.qmd` - Real-world applications and use cases
- `figures/` - All paper figures and visualizations
- `_quarto.yml` - Quarto configuration
- `styles.css` & `custom.scss` - Custom styling

## Local Development

To preview the website locally:

```bash
quarto preview
```

To build the website:

```bash
quarto render
```

## Deployment

The website is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the main branch.

## Citation

```bibtex
@article{mondal2025sentinelkilndb,
  title={SentinelKilnDB: A Large-Scale Dataset and Benchmark for OBB Brick Kiln Detection in South Asia Using Satellite Imagery},
  author={Mondal, Rishabh and Parab, Jeet and Kubadia, Heer and Dubey, Shataxi and Junagade, Shardul and Patel, Zeel B and Batra, Nipun},
  journal={Advances in Neural Information Processing Systems},
  year={2025}
}
```

## Links

- [Dataset on Kaggle](https://kaggle.com/datasets/3eb8e7201b14b158ed841718cb777c5b94a6a6375aaa8499c7376ec831f8d879)
- [Code Repository](https://github.com/rishabh-mondal/NeurIPS_2025)
- [Live Website](https://rishabh-mondal.github.io/sentinelkilndb)

## License

Dataset: CC BY-NC 4.0  
Website: MIT License