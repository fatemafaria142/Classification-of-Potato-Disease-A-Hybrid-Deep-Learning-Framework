# Classification-of-Potato-Disease-A-Hybrid-Deep-Learning-Framework
## Abstract
Potatoes are among the major vegetables in agricul- 
tural regions, and it is farmed and utilized all over the world. 
Potatoes are a high-protein food with several health beneﬁts, but 
there are numerous diseases associated with potatoes that hamper 
production. In this research, we developed a hybrid approach 
that employs image processing and combines MobileNet V2 with 
LSTM, GRU, and Bidirectional LSTM to evaluate potato disease 
classes known as Black Scurf, Common Scab, Blackleg, Dry Rot, 
Pink Rot, Healthy, and Miscellaneous. We examined the outcomes 
of each architecture after applying it independently to determine 
the optimal architecture conﬁguration for categorizing potato 
diseases. In terms of accuracy, the results show that the hybrid 
MobileNet V2-GRU with Stochastic Gradient Descent optimizer 
strategy exceeds the other alternative. On the test dataset, we 
achieved 99% accuracy.

## Table of Contents
- [Paper](#paper-link)
- [Proposed Methodology](#experimental-methodology)
- [Dataset Availability](#dataset-availability)
- [Results](#results)
- [Contact Information](#contact-information)
- [Citation](#citation)

## Paper Link
Explore our research on "Classification of Potato Diseases" to delve into our innovative hybrid deep learning framework for accurate disease classification. To view our detailed findings and methodologies, access the full paper [here](https://ieeexplore.ieee.org/document/10099162).

## Proposed Methodology
![Methodology](potato_diagram.jpg)

    
## Dataset Availability

The dataset can be accessed from [here](https://github.com/Wasi34/Comprehensive-Potato-Disease-Dataset).

### Specifics of the Core Data:

| Disease Name   | Total Images | Causes of Disease |
|----------------|--------------|-------------------|
| **Common scab**| 47           | Bacteria          |
| **Blackleg**    | 40           | Bacteria          |
| **Dry rot**     | 44           | Fungus            |
| **Pink rot**    | 46           | Fungus            |
| **Black scurf** | 36           | Fungus            |


## Results
### Comparative Analysis of Pre-trained Language Models for Different Performance Metrics

| Model         | Accuracy | Precision | Recall  | F1-Score |
|---------------|----------|-----------|---------|----------|
| **BanglaBERT**| **0.8204** | **0.8222** | **0.8204** | **0.8203** |
| Bangla BERT Base | 0.6803 | 0.6907 | 0.6812 | 0.6833 |
| DistilBERT    | 0.6320   | 0.6358    | 0.6320  | 0.6317   |
| mBERT         | 0.6427   | 0.6496    | 0.6428  | 0.6153   |
| sahajBERT     | 0.6708   | 0.6791    | 0.6709  | 0.6707   |


### Comparative Analysis of Large  Language Models for Different Performance Metrics

| LLMs   | Metric    | Zero-shot | 5-shot | 10-shot | 15-shot |
|--------|-----------|-----------|--------|---------|---------|
| GPT 3.5 Turbo | Accuracy  | 0.8500    | 0.8900 | 0.9133  | **0.9400** |
|              | Precision | 0.8467    | 0.8867 | 0.9200  | **0.9467** |
|              | Recall    | 0.8533    | 0.8926 | 0.9079  | **0.9342** |
|              | F1-Score  | 0.8495    | 0.8896 | 0.9139  | **0.9404** |
| Gemini 1.5 Pro | Accuracy  | 0.8608    | 0.8981 | 0.9200  | **0.9633** |
|              | Precision | 0.8931    | 0.8846 | 0.9333  | **0.9667** |
|              | Recall    | 0.8477    | 0.9205 | 0.9091  | **0.9603** |
|              | F1-Score  | 0.8698    | 0.9022 | 0.9211  | **0.9635** |




## Contact Information

For any questions, collaboration opportunities, or further inquiries, please feel free to reach out:

- **Fatema Tuj Johora Faria**
  - Email: [fatema.faria142@gmail.com](mailto:fatema.faria142@gmail.com)

- **Mukaffi Bin Moin**
  - Email: [mukaffi28@gmail.com](mailto:mukaffi28@gmail.com)

- **Rabeya Islam Mumu**
  - Email: [rabeya.islammomo@gmail.com](mailto:rabeya.islammomo@gmail.com)
    
- **Md Mahabubul Alam Abir**
  - Email: [mahbubabir09@gmail.com](mailto:mahbubabir09@gmail.com)
- **Abrar Nawar Alfy**
  - Email: [abraralfy49@gmail.com](mailto:abraralfy49@gmail.com)
    
## Citation

<!--If you find the dataset or the associated research work helpful, please consider citing our paper: -->

```bibtex
@inproceedings{faria2023classification,
  title={Classification of potato disease with digital image processing technique: a hybrid deep learning framework},
  author={Faria, Fatema Tuj Johora and Moin, Mukaffi Bin and Al Wase, Ahmed and Sani, Md Rabius and Hasib, Khan Md and Alam, Mohammad Shafiul},
  booktitle={2023 IEEE 13th Annual Computing and Communication Workshop and Conference (CCWC)},
  pages={0820--0826},
  year={2023},
  organization={IEEE}
}


