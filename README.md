# Is Expert-Labeled Data Worth the Cost? Exploring Active and Semi-Supervised Learning Across Imbalance Scenarios in Financial Crime Detection

This repository contains the experimental results for the paper **"Is Expert-Labeled Data Worth the Cost? Exploring Active and Semi-Supervised Learning Across Imbalance Scenarios in Financial Crime Detection"**, accepted for presentation and publication at the 17th International Symposium on Foundations & Practice of Security (FPS 2024) conference.

## Authors
- **Bahar Emami Afshar** – [ORCID](https://orcid.org/0009-0005-5925-4720)  
  *EECS, Faculty of Engineering, University of Ottawa, Ottawa, Ontario, Canada*  
- **Paula Branco** – [ORCID](https://orcid.org/0000-0002-9917-3694)  
  *EECS, Faculty of Engineering, University of Ottawa, Ottawa, Ontario, Canada*  
- **Tolga Kurt** – [ORCID](https://orcid.org/0009-0003-5267-3776)  
  *H3M Analytics Inc., Montreal, Quebec, Canada*  
- **Utku Gorkem Ketenci** – [ORCID](https://orcid.org/0000-0002-7890-7548)  
  *H3M Analytics Inc., Montreal, Quebec, Canada*  
- **Hikmet Mazmanoglu** – [ORCID](https://orcid.org/0009-0007-3293-1183)  
  *H3M Analytics Inc., Montreal, Quebec, Canada*  

## Overview
The paper explores the application of machine learning (ML) techniques, particularly **active learning** and **semi-supervised learning**, to address the challenges of detecting financial fraud in highly imbalanced datasets. Fraud detection often suffers from limited labeled data and extremely rare fraud cases. This study provides a comparative analysis of how active and semi-supervised learning perform under varying imbalance ratios and resampling techniques. The findings suggest that both approaches can improve fraud detection, especially in highly imbalanced scenarios. Active learning tends to perform better in less imbalanced domains, while the performance gap narrows as the imbalance increases. The study highlights the importance of adjusting the imbalance ratio and applying appropriate sampling techniques to enhance the effectiveness of fraud detection models.

## Datasets
The following datasets were used in the experiments:

- **CCT Dataset**: Credit Card Transactions Fraud Detection  
  Altman, E., Nitsure, A., Mroueh, Y. (2019).  
  Available on Kaggle: [Credit Card Transactions Dataset](https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions)  
  Accessed: 2024-06-20

- **BAF Dataset**: Turning the Tables: Biased, Imbalanced, Dynamic Tabular Datasets for ML Evaluation  
  Jesus, S., Pombal, J., Alves, D., Cruz, A., Saleiro, P., Ribeiro, R.P., Gama, J., Bizarro, P. (2022).  
  Published in Advances in Neural Information Processing Systems (NeurIPS 2022).

## Repository Structure
Each folder in this repository corresponds to a dataset used in the experiments. Within each folder, you will find:
- **Tables**: Performance metrics such as accuracy, precision, recall, F1-score, and more.
- **Figures**: Graphs and visualizations of the results, highlighting performance across different configurations and algorithms.

## How to Use
To explore the results:
1. Navigate to the folder corresponding to the dataset of interest.
2. Open the `.csv` files for detailed performance metrics.
3. Review the figures to visualize the performance across different imbalance scenarios and budget configurations.

## Citation
If you use this repository or any part of the data in your research, please cite the paper as follows:

## Contact Info
For any questions or further information, please feel free to reach out to me at bemam006@uottawa.ca.
