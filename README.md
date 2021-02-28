# COVID-19 Image Summary

## 0. COVID-19 CXR and CT Resources:
- https://radiopaedia.org/articles/covid-19-4?lang=us
- https://github.com/ieee8023/covid-chestxray-dataset
- http://medicalsegmentation.com/covid19/
- https://aimi.stanford.edu/resources/covid19#data
- https://github.com/HzFu/COVID19_imaging_AI_paper_list
---

## 1. Chest X-Ray (CXR)

### 1.1. CXR Dataset

##### Dataset 2: Darwin
- 517 cases of COVID-19
- https://github.com/v7labs/covid-19-xray-dataset

##### Dataset 3: BIMCV-COVID19+: a large annotated dataset of RX and CT images of COVID19 patients [[Download](https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/)]
- Data size: >70GB
- BIMCV COVID-19+: a large annotated dataset of RX and CT images from COVID-19 patients [[Paper](https://arxiv.org/abs/2006.01174)][[GitHub](https://github.com/BIMCV-CSUSP/BIMCV-COVID-19)]


##### Brixia-score: a multi-regional score conveying the degree of lung compromise in COVID-19 patients
- https://github.com/BrixIA/Brixia-score-COVID-19

### 1.2. CXR Papers

##### 1.2.1. CXR Severity Prediction
- Predicting COVID-19 Pneumonia Severity on Chest X-ray with Deep Learning [[Paper](https://arxiv.org/pdf/2005.11856.pdf)]
- (Brixia-score) End-to-end learning for semiquantitative rating of COVID-19 severity on Chest X-rays [[Paper](https://arxiv.org/pdf/2006.04603.pdf)][[Code](https://github.com/BrixIA/Brixia-score-COVID-19)][[Data](https://github.com/BrixIA/Brixia-score-COVID-19/blob/master/data/public-annotations.csv)]
- Automated assessment of COVID-19 pulmonary disease severity on chest radiographs using convolutional Siamese neural networks [[Paper](https://www.medrxiv.org/content/10.1101/2020.05.20.20108159v1.full.pdf)]

---
## 2. CT Scan

### 2.1. CT Scan Datasets
##### Dataset 1: 100 axial CT images from >40 patients with COVID-19 as training data
- Training images (151.8 Mb) -> 100 slices
- Covid19 (ground-glass, consolidation and pleural effusion) masks (1.4 Mb) -> 100 masks
- Test images (14.2 Mb) -> 10 slices

##### Dataset 2: 9 axial volumetric CTs
- Image volumes (308 Mb) -> 800 slices
- Covid19 (ground-glass, consolidation) masks (0.3 Mb) -> 350 annotated slices
- Lung (left/right lungs) masks (1 Mb) -> 700 annotated slices

##### Dataset 3: 20 labeled COVID-19 CT scans. Left lung, right lung, and infections [[Download](https://zenodo.org/record/3757476#.XwwN8JNKimn)]
- Image volumes (1.1Gb) -> 3500+ slices
- Covid19 infection masks (2.5Mb) -> 1800+ slices
- Lung (left/right lungs) masks (9.7Mb) -> 1800+ slices

COVID-19-CT-Seg-Benchmark [[Paper](https://arxiv.org/pdf/2004.12537.pdf)][[Code](https://gitee.com/junma11/COVID-19-CT-Seg-Benchmark)]

##### Dataset 4 (MOSMED Dataset): 1110 axial volumetric CTs, 50 Covid19 labels [[Download](https://mosmed.ai/en/)][[Paper](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1.full.pdf)]
- Findings: https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1
- https://www.eurekalert.org/pub_releases/2020-05/mrap-csd050820.php

##### Dataset 5: BIMCV-COVID19 [[Download](https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/)]
- BIMCV-COVID19+ (>70GB)
- BIMCV-COVID19- (To Release)
- BIMCV-COVID19-PADCHEST (153GB)

##### Dataset 6: China Consortium of Chest CT Image Investigation (CC-CCII) [[Download](http://ncov-ai.big.ac.cn/download?)]

##### Others: https://github.com/ncbi-nlp/COVID-19-CT-CXR
- https://github.com/ncbi-nlp/COVID-19-CT-CXR/releases/

##### **Internal Data Visualization Tool: To be updated

### 2.2. CT Scan Papers

##### 2.2.1. CT Scan Segmentation
- Lung Infection Quantification of COVID-19 in CT Images with Deep Learning [[Paper](https://arxiv.org/pdf/2003.04655.pdf)]
- Rapid AI Development Cycle for the Coronavirus (COVID-19) Pandemic: Initial Results for Automated Detection & Patient Monitoring using Deep Learning CT Image Analysis [[Paper](https://arxiv.org/pdf/2003.05037.pdf)]
- Automated lung segmentation in CT under presence of severe pathologies [[GitHub](https://github.com/JoHof/lungmask)]
- Inf-Net: Automatic COVID-19 Lung Infection Segmentation from CT Images [[Paper](https://arxiv.org/pdf/2004.14133.pdf)][[GitHub](https://github.com/DengPingFan/Inf-Net)]


##### 2.2.2. CT Scan Classification



## 3. CT Scan Scout View (CXR like Images from CT Scan)



## 4. Coding Misc
- https://medium.com/@hbjenssen/covid-19-radiology-data-collection-and-preparation-for-artificial-intelligence-4ecece97bb5b