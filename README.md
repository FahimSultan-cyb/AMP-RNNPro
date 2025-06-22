# 🦠 AMP-RNNpro: A Two-Stage Meta-Learning Framework for Antimicrobial Peptide Prediction

> **A novel probabilistic feature fusion model with RNN backbone and SHAP interpretability for AMPs**

📄 **Paper Title**: *AMP-RNNpro: A two-stage approach for identification of antimicrobials using probabilistic features*  
👨‍🔬 **Authors**: Md. Shazzad Hossain Shaon, Tasmin Karim, Md. Fahim Sultan, Md. Mamun Ali, Kawsar Ahmed, Md. Zahid Hasan, Ahmed Moustafa, Francis M. Bui & Fahad Ahmed Al-Zahrani  
🌐 **Web Tool**: [AMP-RNNpro Server](http://13.126.159.30/)  
📈 **Performance**: 97.15% Accuracy | 96.48% Sensitivity | 97.87% Specificity  
🧬 **Model**: Two-stage prediction + Meta RNN model  

---

## 🧠 Abstract

Antimicrobial peptides (AMPs) are critical agents in combating multidrug-resistant pathogens. This study proposes **AMP-RNNpro**, a novel machine learning framework using Recurrent Neural Networks and probabilistic feature fusion for AMP prediction. The model employs **eight feature encodings** grouped into compositional, autocorrelation, and pseudo-amino acid-based categories.

We first evaluated **33 machine learning models** across all feature sets. Then, the top six models per feature encoding were selected. Their probability outputs were aggregated to form meta-features, which were used to train the final RNN-based classifier. SHAP analysis highlighted that **AAC**, **ASDC**, and **CKSAAGP** were the most impactful features. The final model achieved **97.15% accuracy** and demonstrated superior performance in identifying AMPs.

---

## 🧩 Methodology Overview

<p align="center">
  <img src="figures/methodology.png" alt="AMP-RNNpro Methodology" width="700"/>
</p>



## ✅ Key Contributions

- 🔁 **Two-stage prediction system** with model evaluation and probabilistic fusion.
- 🔍 **33 models evaluated** across eight biologically motivated encodings.
- 🔗 **Top-6 ensemble scores fused** and fed into a meta-RNN classifier.
- 🧬 **SHAP explainability** uncovers 20 impactful biological features for drug discovery.
- 🌐 Deployed as an accessible **web server**: [http://13.126.159.30/](http://13.126.159.30/)

---

```bibtex
@article{shaon2024amprnnpro,
  title={AMP-RNNpro: A two-stage approach for identification of antimicrobials using probabilistic features},
  author={Shaon, Md. Shazzad Hossain and Karim, Tasmin and Sultan, Md. Fahim and others},
  journal={TBD},
  year={2024}
}
