# 🧬 Thesis Project – Early Prediction of Prediabetes & Concept Drift-Aware Bayesian Modeling

This ongoing M.Sc. thesis focuses on the **early prediction of prediabetes** using real-world longitudinal EHR data.  
The project aims to identify **early biomarkers and evolving risk patterns** up to a decade before clinical diagnosis.

## 📌 Work Completed So Far

- 🏥 **Real-world clinical dataset**: 13,736 prediabetic patients and matched controls from Clalit & Soroka
- ⚙️ **Data preprocessing**: outlier removal, pregnancy exclusion, timeline anchoring
- 🧩 **Missing value imputation**: multi-step approach using interpolation, extrapolation, and profile-based filling
- 🧪 **Temporal feature selection**: Welch’s t-test, bootstrapping, FDR correction, and Cohen’s d across time windows
- 📈 **Multi-year aggregation**: transforming raw labs and BMI into meaningful time-windowed features
- 🔬 **Trend analysis**: comparison of biomarker evolution (e.g., glucose, VLDL, triglycerides, uric acid) in prediabetics vs. controls

## 🔄 Next Phase – Concept Drift & Bayesian Network Modeling

- 🧠 **Modeling disease progression** via **Bayesian Networks**
- 📉 **Detecting Concept Drift** using **CDDRL (Concept Drift Detection and Re-Learning)** to:
  - Identify temporal shifts in variable behavior
  - Adapt model structure and maintain relevance over time
- 📊 **Causal analysis**: identifying key interactions and risk factors driving prediabetes onset
- 🧬 **Risk group stratification**: clustering patients into distinct disease trajectory profiles for tailored intervention

## 🔒 Data Privacy Notice

Due to medical data privacy regulations, all code and data are stored securely on a **Clalit research server**  
and **cannot be publicly shared**.  
Instead, a **project summary presentation** is available to demonstrate the methodology and findings.

