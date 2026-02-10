# College Guard Tracking Sample – Applied Basketball Performance Analytics  
*A portfolio demonstration of basketball tracking analysis using Python, Seaborn, and custom NBA court visualizations.*

---

## 📌 Project Overview  
This project showcases how frame-level tracking data can be transformed into **actionable basketball insights** for coaches, scouts, and performance staff.  

Using a small sample dataset (structured similarly to providers like SkillCorner or Second Spectrum), this notebook:

- Processes player movement and defender proximity  
- Generates key performance and spatial metrics  
- Maps all actions onto a **true NBA-calibrated halfcourt**  
- Creates high-value scouting and sport-science visualizations  
- Summarizes movement load, advantage creation, and spacing patterns  

The project is intentionally lightweight so hiring managers can quickly evaluate both the analytics workflow and the communication quality.

---

## 🏀 Key Visualizations & What They Mean  

### **1. Movement Path Mapped to NBA Court**  
Shows the player’s physical route during the possession, overlaid with true court geometry.  
**Interpretation:**  
- Identifies driving angles  
- Shows lane access and route efficiency  
- Highlights how early or late the guard bends into the middle or rejects a ball screen  

---

### **2. Movement Density Heatmap**  
A contour “hot spot” map showing where the guard spent the most time.  
**Interpretation:**  
- High density around slot → indicates POA creation, pick-and-roll initiation  
- Density at the nail → suggests mid-paint touch frequency or hesitation points  
- Spread toward wing/corner → indicates drift patterns vs. switches  

This is one of the *highest-value visuals* for scouts because it reveals *tendencies without watching film*.

---

### **3. Defender Distance Heatmap**  
Weighted KDE showing where the defender was closest/furthest during the possession.  
**Interpretation:**  
- Warm areas = defender giving space (potential pull-up windows)  
- Cool areas = tight coverage  
- Spatial matchup profile helps evaluate advantage creation and reading drops  

---

### **4. Advantage Map (Color-Coded)**  
Scatter plot showing where the guard gained or lost advantage, mapped to the court.  
**Interpretation:**  
- Advantage clusters indicate where the guard reliably creates separation  
- Helps differentiate between guards who create advantage **from speed**, **angles**, or **deception**  
- Useful for scouting reports and matchup planning  

---

## 🧪 Technical Stack  

**Languages & Libraries**  
- Python 3.10  
- Pandas (data processing)  
- NumPy (vector math)  
- Seaborn & Matplotlib (visuals)  
- Custom NBA court geometry (Arc, Circle, Rectangle patches)

**Workflow**  
- CSV ingestion → feature engineering → coordinate normalization  
- Speed, acceleration, COD load  
- Continuous advantage profiling  
- Heatmaps + scouting overlays  
- Insight summary  

**Environment**  
- Google Colab (fully reproducible, no dependencies to install)

---

## 📁 Repository Contents  
