# 🌿 AI-Driven ESG Analysis in Bangladesh's Textile & Apparel Industry

## Overview
The global Textile and Apparel (T&A) industry faces growing pressure to reduce its environmental footprint — producing **92 million tons of waste annually** and contributing to **20% of global water pollution**.  
As a major apparel exporter, **Bangladesh** must integrate transparent **Environmental, Social, and Governance (ESG)** practices to remain globally competitive and meet sustainability standards.

This project presents an **AI and Machine Learning-based framework** to analyze ESG practices among **LEED-certified Bangladeshi T&A factories**, leveraging **Natural Language Processing (NLP)** and **Topic Modeling** to extract, classify, and interpret ESG information.

---

## 🔍 Key Features
- **Automated ESG Text Analysis** using NLP pipelines  
- **Topic Extraction** via Non-Negative Matrix Factorization (NMF)  
- **ESG Category Classification** using Random Forest (achieving 86% accuracy)  
- **Centrality Analysis** linking ESG focus areas with LEED certification levels  
- **Data-Driven Insights** for sustainable manufacturing and responsible sourcing  

---

## 📊 Core Findings
| ESG Category | Focus (%) | Example Themes |
|---------------|------------|----------------|
| 🌱 Environmental Sustainability | 46% | Energy conservation, waste management |
| 🧍‍♀️ Social I – Workplace Safety & Compliance | 28% | Worker safety, compliance standards |
| 🎓 Social II – Education & Community Programs | 16% | Training, community outreach |
| ⚖️ Governance | 10% | Transparency, management accountability |

Factories with **higher certification levels (Platinum)** show a **balanced ESG focus**, while lower-certified ones primarily emphasize **environmental efforts**.

---

## 🧠 Methodology

**1. Data Collection:**  
Textual ESG data extracted from LEED-certified factory reports and sustainability disclosures.  

**2. Preprocessing:**  
- Tokenization and lemmatization  
- Stopword removal and TF-IDF vectorization  

**3. Topic Modeling:**  
- NMF-based topic extraction to uncover latent ESG themes  

**4. Classification:**  
- Random Forest model trained to predict ESG categories  
- Achieved **86% accuracy**, outperforming rule-based and keyword-driven baselines  

**5. Network & Centrality Analysis:**  
- Examined correlations between certification levels and ESG category distributions 
