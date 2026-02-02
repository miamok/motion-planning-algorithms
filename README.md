# Motion Planning for Autonomous Delivery Robots

This repository contains an MSc research project focused on **motion planning for autonomous delivery robots (ADR)** in smart city environments.

The project compares **classical**, **machine learning–based**, and **hybrid** approaches to trajectory planning in dynamic urban scenes with pedestrians.

---

##  Implemented Methods

- **A\*** — classical global path planning on an occupancy grid  
- **Social-LSTM** — pedestrian trajectory prediction with social interactions  
- **Hybrid A\* + Social-LSTM** — dynamic cost map + socially-aware planning  

 The hybrid approach combines the **stability of A\*** with the **adaptability of machine learning**.

---

## Datasets

- **Stanford Drone Dataset (SDD)** — training pedestrian trajectories
-  https://www.kaggle.com/datasets/aryashah2k/stanford-drone-dataset
- **nuScenes** — urban maps, testing, and hybrid planning
-  https://www.nuscenes.org/

Due to licensing and size constraints, datasets are not included in this repository.
---

## Tech Stack

- Python 3.9  
- PyTorch  
- NumPy, Pandas  
- OpenCV  
- Matplotlib  
- Jupyter Notebook  
- nuScenes DevKit  

---
