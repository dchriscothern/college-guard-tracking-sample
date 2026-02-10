# College Guard Tracking Sample – Applied Basketball Analytics  
A demonstration of how tracking data can be transformed into clear, coach-ready basketball insight using Python, Pandas, Seaborn, and Matplotlib.

---

## 📌 Project Overview  
This project showcases how frame-level tracking data can be turned into **actionable information** for coaches, scouts, and performance teams.  

Using a simulated possession modeled after SkillCorner-style tracking, this analysis demonstrates:

- Data cleaning and transformation of positional and velocity data  
- Calculation of speed, acceleration, COD load, defender distance, and separation metrics  
- Visualization of movement paths over a true NBA halfcourt  
- Heatmaps that reveal driving tendencies and spatial behavior  
- Contextual insights tied to advantage creation and decision-making  

The goal is to bridge **data → basketball language**, showing how analytics enhances player development, scouting, and performance workflows.

---

## 📁 Repository Contents
📦 college_guard_tracking_sample/
│
├── tracking_college_guard_sample.csv # Example tracking dataset
├── college_guard_tracking_analysis.ipynb # Full Python notebook
└── README.md # This documentation


---

## 🏀 What This Analysis Demonstrates  

### **1. Movement Path (NBA Court Overlay)**
Shows how the guard moves in space across the possession.  
Useful for identifying:
- attack angles  
- paint access  
- pacing and tempo changes  
- decision-making zones  

This is often the first visual used with coaches because it mirrors film, but with objective detail.

---

### **2. Movement Density Heatmap**
A KDE heatmap illustrating where the guard spends the most time.

Reveals:
- preferred drive lanes  
- strong-hand vs. weak-hand tendencies  
- control points (e.g., nail, slot, free-throw line)  
- hesitation or pacing areas  

A dense area at the **nail** generally reflects a guard comfortable initiating reads from the middle.

---

### **3. Defender Distance Heatmap**
A weighted heatmap that shows where the defender gives cushion or applies pressure.

Useful for:
- identifying pull-up pockets  
- understanding how opponents defend the player  
- recognizing when advantage is created via spacing vs. speed  

This visualization blends biomechanics, tactics, and decision-making.

---

### **4. Advantage Map**
Every frame plotted and colored by advantage state (losing, neutral, gaining).

Helps answer:
- Where does he create separation?  
- Does advantage come from burst or angle manipulation?  
- Do advantages sustain long enough to create shots or passes?  

This is directly relevant to SkillCorner’s *Game Intelligence* metrics.

---

### **5. Radar Profile – Movement & Separation**
A quick snapshot summarizing:
- average & peak speed  
- acceleration load  
- change-of-direction load  
- defender separation  

This serves as a compact athlete overview in scouting or player development contexts.

---

## 🧪 Technical Stack  
**Languages**  
- Python 3.10

**Core Libraries**  
- Pandas – data cleaning & feature engineering  
- NumPy – velocity & acceleration calculations  
- Matplotlib / Seaborn – tracking-style visualizations  
- Custom NBA court drawing function for accurate spatial context  

**Environment**  
- Google Colab / Jupyter Notebook  
- Designed for easy use by coaches, analysts, sport science teams

---

## 🚀 Why This Project Matters  
This workflow represents a practical example of:

- building reproducible analytics processes  
- communicating clearly with non-technical stakeholders  
- connecting movement data to tactical and performance questions  
- generating visuals suitable for scouting, coach reports, and sport-tech clients  

It demonstrates the type of applied analysis used at:
- SkillCorner  
- NBA / WNBA performance & scouting groups  
- NCAA athlete monitoring departments  
- Sports technology & player development companies  

---

## 🎯 Application Areas
- Player development  
- Scouting & draft preparation  
- Team performance analysis  
- Load monitoring & movement profiling  
- Sport tech data pipelines (e.g., SkillCorner tracking data)

---

## ▶️ How to Run the Notebook  
1. Open the notebook in Google Colab  
2. Upload `tracking_college_guard_sample.csv`  
3. Run all cells  
4. Automatically generates all visuals:
   - Court overlay movement map  
   - Density heatmap  
   - Defender-distance heatmap  
   - Advantage scatter map  
   - Radar profile  

No installation or setup required.

---

## 📬 Contact  
**Chris Cothern, DPT, CSCS, CPSS**  
Applied Sports Scientist | Basketball Analytics  
Website: https://www.chriscothern.com  
LinkedIn: https://www.linkedin.com/in/chriscothern  

---

*Built to translate tracking data into meaningful basketball insight.*
