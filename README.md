# Generalized Spectral Graph Networks for Traffic Flow Forecasting - Datasets

This repository hosts the benchmark and real-world traffic datasets used in the research paper: **"Generalized Spectral Graph Networks for Traffic Flow Forecasting"**.

---

## 📂 Repository Contents

This repository is dedicated solely to the dataset files required for training, evaluating, and testing our spectral graph network framework.

### 1. Benchmark Datasets
* **PeMSD4:** Caltrans Performance Measurement System (PeMS) District 4 dataset, covering 307 sensor stations across the Bay Area, California. Provided in standard graph-structured time-series format (5-minute aggregation intervals).
* **PeMSD8:** Caltrans PeMS District 8 dataset, covering 170 sensor stations in Los Angeles County.

### 2. Real-World Curated Datasets
* **Kayseri8:** Real-world traffic flow data collected from 8 major signalized intersections in Kayseri, Türkiye, recorded between January and April 2023 (15-minute intervals).
* **Konya6:** Real-world traffic dataset collected from 6 major intersections in Konya, Türkiye, recorded during June 2025 (10-minute intervals).

---

## 🛠️ Data Structure & Usage

Each dataset folder typically includes:
* **Node Features / Traffic Flow Matrix (`.csv` / `.h5` / `.npz`):** Temporal traffic flow observations.
* **Adjacency / Spatial Distance Matrix (`.csv` / `.pkl`):** Graph topology representing road network connectivity.

---

## 📝 Citation

If you use these datasets in your research, please cite our paper:

```bibtex
@article{coskun2026generalized,
  title={Generalized Spectral Graph Networks for Traffic Flow Forecasting},
  author={Coskun, Mustafa and Bakir-Gungor, Burcu},
  journal={...},
  year={2026}
}
