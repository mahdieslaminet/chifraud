# Datasets

## Overview

This project, **Telecom Fraud Text Detection (CHIFRAUD)**, leverages multiple **multilingual text datasets** for spam and telecom fraud detection, covering **English, Arabic, and Chinese**.  
The datasets are used to evaluate and reproduce experiments based on transformer-based NLP models for fraud detection.

⚠️ **Important note**:  
All datasets remain the property of their original authors and providers.  
This repository **does not redistribute raw datasets**; it only provides **references, links, and preprocessing guidance** to ensure transparency and reproducibility.

---

## Datasets Used

### A) English — SMS Spam Collection (Kaggle mirror)

**Name**: SMS Spam Collection  
**Access link**:  
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download

**Description**:  
A widely used benchmark dataset for SMS spam detection consisting of **5,574 English SMS messages**, annotated with binary labels:
- `ham` (legitimate messages)
- `spam` (fraudulent or unsolicited messages)

The dataset contains two primary columns:
- `v1`: label (`ham` / `spam`)
- `v2`: message text

#### Original source & citation

- Original dataset page:  
  http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/

- Reference paper:  
  Almeida, T. A., Gómez Hidalgo, J. M., & Yamakami, A.  
  *Contributions to the Study of SMS Spam Filtering: New Collection and Results.*  
  Proceedings of DOCENG 2011.

---

### B) Arabic — Arabic Spam Tweets Dataset (Mendeley)

**Name**: Arabic spam tweets dataset  
**Access link**:  
https://data.mendeley.com/datasets/86x733xkb8/1

**Description**:  
This dataset was collected using the **Twitter API** between **January 27, 2021 and March 10, 2021**, and contains **13,241 Arabic tweets** annotated for spam detection:
- **1,924 Spam**
- **11,299 Ham**

The original release format is **XLSX**.  
In this project, the dataset is **converted to CSV using Python** for downstream NLP preprocessing and modeling.

#### Citation

Kaddoura, S., Alex, S. A., Itani, M., Henno, S., AlNashash, A., & Hemanth, D. J. (2023).  
*Arabic spam tweets classification using deep learning.*  
Neural Computing and Applications.

---

### C) Chinese — CHIFRAUD Dataset

**Name**: CHIFRAUD dataset  
**Dataset link**:  
CHIFRAUD Dataset (GitHub): `<ADD_LINK_HERE>`

**Article link**:  
CHIFRAUD Article: (https://aclanthology.org/2025.coling-main.398/)

**Description**:  
CHIFRAUD is a **long-term benchmark dataset for Chinese telecom fraud detection**, designed to reflect realistic fraud scenarios in large-scale communication systems.  
It serves as the core Chinese-language benchmark in this project.

#### Citation

Tang, Zou, Liang, Jin, Wang, & Cui (2025)
