
# FoodNExTDB 🍽️  

This repository hosts the FoodNExTDB dataset and materials from our study evaluating Vision-Language Models (VLMs) for food image recognition. The dataset will be publicly available soon.

---

![graphical-abstract](img/graphicalabstract.png)

## 📌 Introduction

**FoodNExTDB** is a new expert-labeled food image database developed to evaluate the capabilities of VLMs in automatic dietary assessment tasks. The **FoodNExTDB** is a food image database derived from the [AI4FoodDB](https://github.com/AI4Food/AI4FoodDB) [[1]](https://academic.oup.com/database/article/doi/10.1093/database/baad049/7226275), a **comprehensive multimodal database acquired from a one-month randomized controlled trial (RCT) with 100 overweight and obese participants undergoing a nutritional intervention**. The FoodNExtdb includes food images collected over 14 days per participant, with many food products reflecting Spanish and Mediterranean cuisine characteristics.

In our paper titled "**Are Vision-Language Models Ready for Dietary Assessment? Exploring the Next Frontier in AI-Powered Food Image Recognition**, accepted at **CVPR 2025 Workshops** (see the full paper on [arXiv](https://arxiv.org/abs/2504.06925)), we assess six state-of-the-art VLMs (ChatGPT, Gemini, Claude, Moondream, DeepSeek, and LLaVA) on their ability to recognize food items at different semantic levels — including food category (e.g., *protein source*), subcategory (e.g., *poultry*), and cooking style (e.g., *grilled*).

The database consists of:

- **9,263 food images**  
- **10 high-level food categories**  
- **62 fine-grained subcategories**  
- **9 cooking styles**  
- **50,000+ expert-generated annotations**, verified by seven nutrition professionals

We also introduce **Expert-Weighted Recall (EWR)**, a new metric that considers inter-annotator variability, to evaluate food recognition performance more realistically.

## References

[1] [S. Romero-Tapiador, B. Lacruz-Pleguezuelos, R. Tolosana, et al. AI4FoodDB: A Database for Personalized e-Health Nutrition and Lifestyle through Wearable Devices and Artificial Intelligence. Database, 2023: baad049, 2023](https://academic.oup.com/database/article/doi/10.1093/database/baad049/7226275).

---

## 🗂️ Dataset Access

📌 **The FoodNExTDB dataset will be made publicly available soon.**  
Stay tuned for the release and citation guidelines.

---

## 📄 Citation

If you use this database or the evaluation protocol, please cite:

```bibtex
@inproceedings{romerotapiador2025foodnextdb,
  title     = {Are Vision-Language Models Ready for Dietary Assessment? Exploring the Next Frontier in AI-Powered Food Image Recognition},
  author    = {Sergio Romero-Tapiador and Ruben Tolosana and Blanca Lacruz-Pleguezuelos and Laura Judith Marcos-Zambrano and Guadalupe X. Bazán and Isabel Espinosa-Salinas and Julian Fierrez and Javier Ortega-Garcia and Enrique Carrillo de Santa Pau and Aythami Morales},
  booktitle = {In Proc. of the IEEE/CVF Conference on Computer Vision and Pattern Recognition workshops},
  year      = {2025}
}
```
---

## Contact
If you have any questions, please get in touch with us at sergio.romero@uam.es.
