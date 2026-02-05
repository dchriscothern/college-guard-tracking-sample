College Guard Tracking Sample – Applied Basketball Analytics
A demonstration of basketball tracking analysis using Python, Pandas, and Matplotlib.

📌 Project Overview

This project demonstrates how possession-level tracking data can be transformed into actionable basketball insights.
Using a small simulated dataset (created to mimic real tracking structures such as SkillCorner), the notebook walks through:

Cleaning and preparing tracking data
Calculating speed, direction, acceleration, defender distance, and possession context
Identifying attacking advantage
Visualizing drive corridors, defender matchups, and positional tendencies
Generating scouting-style insights for coaches and performance staff
Creating movement heatmaps to profile spatial tendencies and defensive pressure

This project is built to serve as a basketball analytics sample for applied sport science, scouting, and player development roles.

📁 Repository Contents

📦 college_guard_tracking_sample
│
├── tracking_college_guard_sample.csv – Example possession-level data
├── college_guard_tracking_analysis.ipynb – Google Colab / Python analysis
└── README.md – Project description

🏀 What This Analysis Demonstrates
1. Drive Lane Profiling

Heat-like visualization showing the guard’s path relative to the ball and defender.
Used to identify:

Preferred attack angles
Tendencies versus hedges or switches
Scouting visuals for spacing and decision making

2. Speed + Advantage Mapping

Scatter plot showing when speed peaks occur relative to defender distance.
Shows:

Burst ability
Whether separation is created through acceleration or angles
How advantage evolves during a possession

3. Shot Context Visualization

Overlay of potential shot locations relative to defender proximity.
Useful for:

Evaluating shot selection
Understanding spacing and timing
Teaching quality-shot principles

4. Movement Density Heatmap (New)

This heatmap shows where the guard spent the most time on the floor.
It highlights:

Preferred driving corridors
Natural spacing patterns
High-frequency positional tendencies

This is similar to outputs used by tracking providers like SkillCorner, Second Spectrum, and Synergy.

5. Defender Distance Heatmap (New)

A heatmap that visualizes defender proximity across the possession.
It helps identify:

Areas where the guard gained separation
Zones of defensive pressure
Situations where advantage was likely created

6. Advantage State Map (New)

Scattermap showing each frame colored by advantage state.
Supports:

Understanding when and where advantage occurs
Linking positional data to tactical decision making
Scouting how a guard manipulates space

🧪 Technical Stack
Languages and Libraries

Python 3.10+
Pandas – data cleaning and feature creation
NumPy – vector calculations for velocity and acceleration
Matplotlib / Seaborn – movement maps and scouting visualizations

Environment

Google Colab
Jupyter Notebook workflow for coaching and sport science environments

Data Structures

Wide-format tracking dataset with frame-level positions.
Derived metrics include:

velocity
acceleration
defender distance
possession context
calculated advantage
change-of-direction load

Tools and Workflow

CSV ingestion
Preprocessing and feature engineering
Heatmap and movement-map visualization
Coach-facing insight summaries

GitHub version control

🚀 Future Improvements

Add richer possession context
Incorporate screen locations, help rotations, tagging, spacing, and role-based interactions.

Build an expected advantage model
Predict advantage from separation, acceleration, and angle.

Automate drive classification
Model straight-line drives, rejects, snake dribbles, hesitation bursts, and crossovers.

Extend to full games
Build game-based player reports for scouting or player development workflows.

Create an interactive dashboard
Use Streamlit for live coach-facing decision support.

Integrate orientation and off-ball tracking
Add heading, space control, and tactical involvement metrics.

Build a reusable Python template
Allow other practitioners to drop in a CSV and instantly generate a visual report.

▶️ How to Run the Notebook

Upload tracking_college_guard_sample.csv into your Colab session

Open the notebook
Run all cells
Visual outputs will generate:
Drive path chart
Speed vs advantage scatter
Shot-context visualization
Movement density heatmap
Defender distance heatmap
Advantage map
COD and speed timelines

All dependencies are handled automatically in Colab.

👥 Why This Project Matters

This project shows how raw tracking data becomes usable basketball insight for:

Player development staff, Video coordinators, Sport scientists, Scouting departments, Sport tech companies

It demonstrates practical Python work applicable to college, professional, and sport-tech environments.

📬 Contact

If you would like to discuss basketball analytics, sport science workflows, or tracking data:

Chris Cothern
Website: https://www.chriscothern.com
LinkedIn: https://www.linkedin.com/in/chriscothern

This sample project is intended for demonstration, education, and portfolio use.
