# Time series analysis for electrical grid loss prediction

This notebook aims to present the analysis and proposed solution to the problem of electrical grid loss.

The repository has the following structure

| Notebook     |      Description      |   |
|:----------|:-------------|------:|
| [Exploratory Data Analysis](https://github.com/fabiobif/VoltageLoss/blob/main/Analysis_LossTransmission.ipynb)  | Presents the preliminary analysis on the data (notebook: Analysis_LossTransmission)  |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiobif/VoltageLoss/blob/main/Analysis_LossTransmission.ipynb) |
| [Solution](https://github.com/fabiobif/VoltageLoss/blob/main/Model_LossTransmission.ipynb) | Presents a trained model to detect voltage losses in a power line (notebook: Modelo_PredicaoFalha_Rede) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fabiobif/VoltageLoss/blob/main/Model_LossTransmission.ipynb)|
| [Datasets](https://github.com/fabiobif/VoltageLoss/tree/main/datasets) | Folder containing the created datasets |  |

---
### Problem description
> Power lines run for hundreds of kilometers to supply cities with power. These great distances make the job of manually inspecting the lines for damage a complex and expensive task. This damage leads to a phenomenon known as partial discharge - partial discharges are electrical discharges that occur from defects in the insulation of cables, they can also occur at their interfaces (insulating and semiconducting) or at splices and terminals. Among its causes are the aging of components, contamination of the insulating material, and installation failure, among others. Partial discharges gradually damage voltage lines, so if they are not repaired, they can lead to a power outage, damage equipment, or cause environmental disasters.
