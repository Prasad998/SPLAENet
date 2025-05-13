# SPLAENet

**Emotion-aware Dual Cross-Attentive Neural Network with Label Fusion for Stance Detection in Misinformative Social Media Content**

---

## 🧠 Overview

**SPLAENet** is a novel neural architecture for **stance detection** in **misinformative social media content**, where user opinions can be highly polarized and emotionally charged. The model leverages:

- **Dual cross-attention** to model interdependencies between source and reply posts.
- **Emotion-aware representation learning** to capture affective alignment or divergence.
- **Label fusion using distance metric learning** to improve stance-label alignment.
- **Hierarchical attention networks** to enhance intra- and inter-text relationships.

SPLAENet achieves **significant improvements** over existing methods, with up to **17% F1-score gain** on benchmark datasets.

---

## 📰 Paper Abstract

> The rapid evolution of social media has generated an overwhelming volume of user-generated content, conveying implicit opinions and contributing to the spread of misinformation. Stance detection has emerged as a crucial approach for analyzing biases in shared information. This paper proposes **SPLAENet**: a **Label-fused Dual Cross-Attentive Emotion-aware Neural Network** for stance detection in misinformative content.  
>
> SPLAENet integrates dual cross-attention between source and reply texts, emotional context modeling, and label fusion using distance-metric learning. Extensive experiments show substantial gains over state-of-the-art models across **RumourEval**, **SemEval**, and **P-Stance** datasets.

---

## 📊 Datasets

The model has been evaluated on the following benchmark datasets:

1. **RumourEval 2019**  
   [📥 Download](https://figshare.com/articles/dataset/RumourEval_2019_data/8845580?file=16188500)

2. **SemEval 2016**  
   [📥 Download](https://www.saifmohammad.com/WebPages/StanceDataset.htm)

3. **P-Stance**  
   [📥 Download](https://drive.google.com/drive/folders/1so8lY1XKpnhUtTvb15edEz6aeHt7CSuh)

---

## 🔍 Model Architecture

SPLAENet integrates multiple attention-based components to model both **contextual relevance** and **emotional alignment**:

- **Dual Cross-Attention:** Focuses on important words between source ↔ reply.
- **Emotion Embeddings:** Captures sentiment-based stance cues.
- **Hierarchical Attention:** Learns multi-level textual relationships.
- **Label Fusion:** Uses distance-based learning to align features with stance labels.

<p align="center">
  <img src="https://raw.githubusercontent.com/Prasad998/SPLAENet/main/SPLAENet-flowchart.png" alt="SPLAENet Flowchart" width="600"/>
</p>
---

## 📈 Results

SPLAENet outperforms prior methods with significant gains:

| Dataset     | Accuracy ↑ | F1-score ↑ |
|-------------|------------|------------|
| RumourEval  | +8.92%     | +17.36%    |
| SemEval     | +7.02%     | +10.92%    |
| P-Stance    | +10.03%    | +11.18%    |

---

## 📂 Repository

Code and usage instructions are available on GitHub:  
🔗 [github.com/prasad998/SPLAENet](https://github.com/prasad998/SPLAENet)

---

## 📌 Keywords

> Attention Mechanism · Emotion Analysis · Label Fusion · Stance Detection · Social Media · NLP
