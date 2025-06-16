# Unveiling Hidden Patterns: A Deep Learning Framework Utilizing PCA for Fraudulent Scheme Detection in Supply Chain Analytics

[![DOI](https://img.shields.io/badge/DOI-10.5815/ijisa.2025.02.02-blue.svg)](https://doi.org/10.5815/ijisa.2025.02.02)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

    

> 📂 **Source code is [here](https://github.com/kowshik14/FraudDetection-SupplyChain/tree/main/src).**


## Abstract

Supply chain fraud, a persistent issue over the decades, has seen a significant rise in both prevalence and sophistication in recent years. In the current landscape of supply chain management, the increasing complexity of fraudulent activities demands the use of advanced analytical tools. Despite numerous studies in this domain, many have fallen short in exploring the full extent of recent developments. Thus, this paper introduces an innovative deep learning-based classification model specifically designed for fraud detection in supply chain analytics. To enhance the model's performance, hyperparameters are fine-tuned using Bayesian optimization techniques. To manage the challenges posed by high-dimensional data, Principal Component Analysis (PCA) is applied to streamline data dimensions. In order to address class imbalance, the SMOTE technique has been employed for oversampling the minority class of the dataset. The model's robustness is validated through evaluation on the well-established 'DataCo smart supply chain for big data analysis' dataset, yielding impressive results. The proposed approach achieves a 94.71% fraud detection rate and an overall accuracy of 99.42%. Comparative analysis with various other models highlights the significant improvements in fraud transaction detection achieved by this approach. While the model demonstrates high accuracy, it may not be directly transferable to more diverse or real-world datasets. As part of future work, the model can be tested on more varied datasets and refined to enhance generalizability, better aligning it with real-world scenarios. This will include addressing potential overfitting to the specific dataset used and ensuring further validation across different environments to confirm the model's robustness and generalizability.

## 🚀 Features

- 🔍 **Deep Learning Architecture for Fraud Detection:**  
  A unique deep learning model specifically designed to detect fraudulent activities within supply chain analytics.

- 🎯 **Dimensionality Reduction with PCA:**  
  Principal Component Analysis (PCA) is utilized to streamline high-dimensional data, ensuring optimal performance while avoiding the curse of dimensionality.

- ⚙️ **Bayesian Optimization for Hyperparameter Tuning:**  
  Hyperparameters are fine-tuned using advanced Bayesian optimization techniques to maximize the model's accuracy.

- ⚖️ **Class Imbalance Handling with SMOTE:**  
  Synthetic Minority Over-sampling Technique (SMOTE) effectively balances the dataset by oversampling the minority class, enhancing fraud detection.

- 📊 **Benchmark Evaluation on Real-World Data:**  
  Evaluated on the 'DataCo smart supply chain for big data analysis' dataset, the model delivers a 94.71% fraud detection rate and an overall accuracy of 99.42%.

- 🛠️ **Comparative Analysis with Other Models:**  
  The model is benchmarked against individual machine learning and deep learning classifiers, as well as state-of-the-art models in supply chain analytics, demonstrating superior performance.


## Dataset Link
[![DOI](https://img.shields.io/badge/DOI-10.17632/8gx2fvg2k6.5-blue.svg)](https://doi.org/10.17632/8gx2fvg2k6.5)


## Citation

If you find this work useful, please cite our paper:  
Kowshik Sankar Roy, Pritom Biswas Udas, Bashirul Alam, Koushik Paul, "Unveiling Hidden Patterns: A Deep Learning Framework Utilizing PCA for Fraudulent Scheme Detection in Supply Chain Analytics", International Journal of Intelligent Systems and Applications(IJISA), Vol.17, No.2, 2025. 

## Installation

To install, run the following command:

```bash
git clone https://github.com/kowshik14/FraudDetection-SupplyChain.git
