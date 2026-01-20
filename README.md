# UIDAI-HACKATHON
# AadhaarInsight AI  
### Unlocking Societal Trends in Aadhaar Enrolment & Updates

AadhaarInsight AI is a **browser-based analytical platform** designed to analyze, normalize, and visualize large-scale Aadhaar enrolment and update datasets provided by UIDAI.  
The system transforms raw data into **actionable insights** using statistically sound normalization, anomaly detection, and cross-dataset correlation.

This tool is built specifically to address the **UIDAI Data Hackathon problem statement**:  
> *“Unlocking Societal Trends in Aadhaar Enrolment and Updates”*

---

## 🚀 Key Capabilities

- ✅ **Browser-based execution** (Android & Desktop compatible)
- ✅ **Handles 10+ lakh records efficiently**
- ✅ **No demo or synthetic data** – works only on real UIDAI datasets
- ✅ **Topic-wise guided analysis** (step-by-step execution)
- ✅ **Persistent results** (each analysis step is stored and revisitable)
- ✅ **Fully normalized analytics** (no misleading raw counts)
- ✅ **Animated, interactive graphs**
- ✅ **Explainable insights with confidence scores**
- ✅ **Cross-dataset combined intelligence**
- ✅ **Auto-generated PDF report for submission**

---

## 📊 Datasets Used

The system works on **three official UIDAI datasets** (converted from PDF to CSV):

1. **Aadhaar Enrolment Dataset**
   - Age groups: 0–5, 5–17, 18+
   - Time-based enrolment trends
   - Regional (state/district) coverage

2. **Aadhaar Biometric Update Dataset**
   - Fingerprint, Iris, Face updates
   - Modality imbalance analysis
   - Regional intensity & anomaly detection

3. **Aadhaar Demographic Update Dataset**
   - Address, gender, demographic corrections
   - Migration and update-frequency indicators

⚠️ Raw counts are **never** used directly for inference.  
All analysis is performed on **normalized metrics**.

---

## 🧠 Analytical Methodology

### 1. Data Normalization
To ensure fair comparison across regions and time:
- Age-group ratios instead of raw enrolment counts
- Monthly aggregation to remove daily noise
- Regional share normalization (district/state)

### 2. Anomaly Detection
- Z-score based statistical detection
- Thresholds:
  - |Z| > 2 → Warning
  - |Z| > 3 → Significant anomaly

### 3. Topic-wise Execution
Each dataset is analyzed **sequentially by topic**, for example:
- Enrolment → School-age trend → Stored
- Enrolment → Child enrolment → Stored
- Biometric → Fingerprint updates → Stored

Results are persisted and can be revisited at any time.

### 4. Cross-Dataset Intelligence
Normalized outputs from all three datasets are combined to derive a **System Health Index**, enabling insights such as:
- Institutional enrolment vs organic growth
- Biometric ageing effects
- Migration-driven demographic updates

---

## 📈 Visualizations

- 📉 **Animated time-series line charts**
- 📊 **Comparative bar charts**
- 🔥 **Heatmaps for regional intensity**
- 🧩 **Final merged graph combining all datasets**

All graphs:
- Are generated dynamically from normalized data
- Support state/district filtering
- Are fully animated (time-series aware)

---

## 🧾 Explainable Insights

Each insight includes an **“Explain this insight”** option showing:
- Metric used
- Normalization formula
- Statistical baseline
- Z-score deviation
- Data volume analyzed
- Confidence score

This ensures **full transparency and auditability**.

---

## 📄 PDF Export (Submission Ready)

The system can generate a **UIDAI-ready consolidated PDF** containing:
- Problem statement & approach
- Dataset description
- Methodology
- Graphs with observations
- Impact analysis
- Recommendations

The PDF is generated directly from computed results.

---

## 🛠️ Tech Stack

### Frontend
- HTML5, CSS3
- JavaScript
- Chart.js (animated graphs)

### Backend
- Python
- FastAPI
- Pandas
- NumPy
- ReportLab (PDF generation)

---

## 📁 Project Structure
