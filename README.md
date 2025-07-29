# 🤖 ChatGPT Market Positioning & Segmentation

**Arizona State University** | Feb 2025 – Mar 2025

---

## 🚀 Project Overview

This project applies perceptual mapping and preference analysis to determine ChatGPT’s market position versus key competitors (DeepSeek, Gemini, Copilot, Claude), and to segment consumers for targeted strategy. We used survey‐based perceptual ratings on six attributes and stated‐preference data to:

- **Visualize** brand positioning on two principal dimensions explaining **99.8%** of variance   
- **Assess** average consumer preference (ChatGPT 7.74 vs. Copilot 4.18, Gemini 4.08, DeepSeek 3.92, Claude 3.46)  
- **Identify** two distinct preference segments  
- **Simulate** market‐share outcomes for hypothetical new entrants

---

## 📊 Data & Resources

- **Survey Instrument:** Google Forms (Perceptual & Preference)   
- **Perceptual Data:**  
  - 6 brands × 6 attributes (`Ease of Use`, `Speed of Response`, `Response Accuracy`, `Range of Capabilities`, `Creative/Innovation`, `Trustworthiness`)  
- **Preference Data:** 39 cleaned responses on a 1–9 scale  
- **Dimensions Retained:** 2 (Dim 1 = 99.5%, Dim 2 = 0.3%)   

---

## 🛠️ Tech Stack

- **Analysis & Modeling:** Python (Pandas, NumPy, Scikit-Learn)  
- **Dimensionality Reduction:** Principal Component Analysis (PCA)  
- **Visualization:** Matplotlib, Seaborn, Enginius for interactive reports  
- **Reporting:** Jupyter Notebooks & PDF/PowerPoint exports

---

## ✨ Key Findings

1. **Primary Dimensions**  
   - **Dim 1:** *Ease of Use & Speed of Response*  
   - **Dim 2:** *Response Accuracy & Innovation*  
   Together they capture **99.8%** of variance .  
2. **Brand Coordinates** (Dim 1 vs Dim 2)  
   - ChatGPT (0.900, −0.012) – clear leader on usability & speed  
   - DeepSeek (−0.140, 0.040), Gemini (−0.225, 0.001), Copilot (−0.096, 0.010), Claude (−0.439, −0.039)  
3. **Attribute Loadings**  
   - `Ease of Use` (0.889, 0.085) & `Speed of Response` (0.795, −0.403) most aligned with Dim 1  
   - `Response Accuracy` (0.466, 0.622) & `Creative/Innovation` (0.500, 0.628) drive Dim 2  
4. **Consumer Preferences**  
   - Average scores: ChatGPT 7.74 > Copilot 4.18 > Gemini 4.08 > DeepSeek 3.92 > Claude 3.46  
   - Two segments emerged:  
     - **Segment 1:** Open to alternatives (preference range 5.1–7.4)  
     - **Segment 2:** Highly loyal to ChatGPT (avg 8.19)  
5. **Market‐Share Simulation**  
   - New entrant positioned at the origin of Dim 3 would capture ~7.2% share under a first‐choice rule

---

## 📈 Strategic Recommendations

Based on our analysis and presentation insights , ChatGPT should:

1. **Reinforce Usability & Speed**  
   - Maintain leadership in UI/UX and response latency  
   - Highlight real‐time performance in marketing  
2. **Enhance Trustworthiness**  
   - Implement explainable‐AI features and bias‐checks  
   - Partner with trusted institutions to boost credibility  
3. **Differentiate from Free Competitors**  
   - Emphasize superior accuracy, innovation, and reliability  
   - Showcase premium integrations & developer tools  
4. **Adopt Tiered Pricing**  
   - Freemium + Premium ($20–25/month) to capture both casual and high‐value users
