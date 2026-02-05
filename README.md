# College Guard Tracking Sample – Applied Basketball Analytics  
*A demonstration of basketball tracking analysis using Python, Pandas, and Matplotlib.*
---

## 📌 Project Overview  
This project demonstrates how possession-level tracking data can be transformed into **actionable basketball insights**.  
Using a small simulated dataset (created to mimic real tracking structures such as SkillCorner), the notebook walks through:

- Cleaning and preparing tracking data  
- Calculating speed, direction, acceleration, defender distance, and possession context  
- Identifying attacking advantage  
- Visualizing drive corridors, defender matchups, and positional tendencies  
- Generating scouting-style insights for coaches and performance staff  

This project is built to serve as a **basketball analytics sample** for applied sport science, scouting, and player development roles.
---

## 📁 Repository Contents
📦 college_guard_tracking_sample  
│  
├── `tracking_college_guard_sample.csv` – Example possession-level data  
├── `college_guard_tracking_analysis.ipynb` – Google Colab / Python analysis  
└── `README.md` – Project description  

---

## 🏀 What This Analysis Demonstrates  

### **1. Drive Lane Profiling**  
Heat-like visualization showing the guard’s path relative to the ball and defender.  
Useful for:  
- Identifying preferred attack angles  
- Anticipating tendencies vs. hedges or switches  
- Supporting scouting reports with visuals  

### **2. Speed + Advantage Mapping**  
Plot showing when speed peaks occur relative to defender distance.  
Shows:  
- Burst ability  
- Whether separation is created through acceleration or angles  
- How advantage changes during a possession  

### **3. Shot Context Visualization**  
Overlay of shots taken relative to defender proximity.  
Supports:  
- Evaluating shot selection  
- Understanding spacing and timing  
- Teaching “quality shot windows”  

---

## 🧪 Technical Stack  

### **Languages & Libraries**
- Python 3.10+  
- Pandas – data cleaning and feature creation  
- NumPy – vector calculations for velocity and acceleration  
- Matplotlib / Seaborn – movement maps and scouting visualizations  

### **Environment**
- Google Colab  
- Jupyter Notebook workflow for coaching and sport science environments  

### **Data Structures**
- Wide-format tracking dataset with frame-level positions  
- Derived metrics such as:  
  - velocity  
  - acceleration  
  - defender distance  
  - possession context  
  - calculated advantage  

### **Tools & Workflow**
- CSV ingestion  
- Preprocessing and feature engineering  
- Visualization and interpretation  
- Coach-facing insight summaries  
- GitHub version control  

### **Application Areas**
- Basketball sport science  
- Performance analysis  
- Scouting and draft preparation  
- Player development workflows  
- Sport tech (SkillCorner, Second Spectrum-style tracking)  

---

## 🚀 Future Improvements  

### **1. Add richer possession context**
Incorporate screen locations, help rotations, tagging, spacing, and role-based interactions.

### **2. Build an expected advantage model**
Create an ML or logistic model predicting advantage from speed, separation, and angle.

### **3. Automate drive classification**
Use logic or ML to classify:  
- straight-line  
- reject  
- snake  
- hesitation burst  
- crossover escape  

### **4. Extend to full games**
Build shift-by-shift or game-based player reports for deeper scouting value.

### **5. Create an interactive dashboard**
Streamlit interface for easy coaching and performance conversations.

### **6. Integrate orientation + off-ball tracking**
Simulate or add heading data, space control metrics, and help-side involvement.

### **7. Build a reusable Python template**
Allow others to drop in new tracking CSVs and instantly generate visual reports.

---

## ▶️ How to Run the Notebook  

1. Upload `tracking_college_guard_sample.csv` into your Colab session  
2. Open the notebook  
3. Run all cells  
4. Visual outputs will generate:  
   - Drive path chart  
   - Speed vs. advantage scatter  
   - Shot-context visualization  

All dependencies are handled automatically in Colab.

---

## 👥 Why This Project Matters  
This project shows how **raw tracking data → becomes usable insight** for:

- Player development staff  
- Video coordinators  
- Sport scientists  
- Scouting departments  
- Sport tech companies  

It demonstrates practical Python work applicable to **college, professional, and sport-tech environments**.

---

## 📬 Contact  

If you’d like to discuss basketball analytics, sport science workflows, or tracking data:

**Chris Cothern**  
Website: https://www.chriscothern.com  
LinkedIn: https://www.linkedin.com/in/chriscothern  

---

*This sample project is intended for demonstration, education, and portfolio use.*
