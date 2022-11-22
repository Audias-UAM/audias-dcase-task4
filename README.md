# DCASE Task 4 / AUDIAS 
Sound Event Detection and Separation in Domestic Environments

---

This repository is the AUDIAS-UAM fork of the DCASE Challenge Task 4 Baseline system. The code developed for our participations in the challenge and related publications will be published here (work in progress). Additionally, a list of our publications and results in the challenge is provided.

## Publications

* Diego de Benito-Gorrón, Katerina Zmolikova, and Doroteo T. Toledano, “Source Separation for Sound Event Detection in Domestic Environments Using Jointly Trained Models”. 2022 International Workshop on Acoustic Signal Enhancement (IWAENC), Bamberg, Germany, Sep. 2022.

* Diego de Benito-Gorrón, Daniel Ramos, and Doroteo T. Toledano, “An Analysis of Sound Event Detection under Acoustic Degradation Using Multi-Resolution Systems”. Applied Sciences. 2021; 11(23):11561. DOI: 10.3390/app112311561 

* Diego de Benito-Gorrón, Sergio Segovia, Daniel Ramos, and Doroteo T. Toledano, “Multiple Feature Resolutions for Different Polyphonic Sound Detection Score Scenarios in DCASE 2021 Task 4”. Detection and Classification of Acoustic Scenes and Events Workshop (DCASE), Barcelona, Spain, Nov. 2021.

* Diego de Benito-Gorrón, Daniel Ramos, and Doroteo T. Toledano, “A Multi-resolution CRNN-based approach for semi-supervised Sound Event Detection in DCASE 2020 challenge”. IEEE Access, vol. 9, pp. 89029-89042, (2021). DOI: 10.1109/ACCESS.2021.3088949

* Diego de Benito-Gorrón, Daniel Ramos, and Doroteo T. Toledano, “A Multi-resolution Approach to Sound Event Detection in DCASE 2020 Task4”. Detection and Classification of Acoustic Scenes and Events Workshop (DCASE), Tokyo, Japan, Nov. 2020.


## AUDIAS-UAM participations in DCASE Challenge Task 4

### 2022
[Technical report](https://dcase.community/documents/challenge2022/technical_reports/DCASE2022_deBenito_61_t4.pdf) | [Challenge ranking](https://dcase.community/challenge2022/task-sound-event-detection-in-domestic-environments-results) 
| Submission                                                    | PSDS1 (evaluation) | PSDS2 (evaluation) | F1% (evaluation) | PSDS1 (dev-test) | PSDS2 (dev-test) | F1% (dev-test) |
|---------------------------------------------------------------|--------------------|--------------------|------------------|------------------|------------------|----------------|
| 10-Resolution CRNN+Conformer                                  | 0.400              | 0.646              | 45.0             | 0.410            | **0.665**            |                |
| 10-Resolution CRNN+Conformer with class-wise median filtering | 0.310              | 0.642              | 37.7             | 0.347            | 0.663            |                |
| 7-Resolution CRNN+Conformer                                   | 0.407              | 0.643              | **46.5**         | 0.422            | 0.656            |                |
| 7-Resolution CRNN+Conformer with class-wise median filtering  | **0.432**          | **0.649**          | **46.5**         | **0.428**        | 0.655            |                |

### 2021

### 2020



