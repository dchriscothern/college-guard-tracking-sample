College Guard Tracking Sample — Applied Basketball Tracking Analysis

A demonstration of how frame-level tracking data can be transformed into clean, interpretable insights for coaches, scouts, and performance staff.

📌 Project Overview

This project analyzes a college guard’s movement using simulated tracking-style positional data.
The goal is to show a SkillCorner-style workflow:

Clean and structure frame-level tracking data

Compute movement metrics (speed, acceleration, COD load, distance traveled)

Evaluate spacing through defender-distance trends

Identify moments of advantage creation

Map trajectories onto a true NBA half-court for intuitive interpretation

Summarize insights in a client-ready format suitable for coaching and scouting conversations

The notebook is designed as a portfolio sample demonstrating applied tracking analysis, communication clarity, and basketball-specific context.

📁 Repository Contents
📦 college-guard-tracking-sample
│
├── tracking_college_guard_sample.csv   # Sample tracking-like dataset
├── college_guard_tracking_sample.ipynb # Full analysis notebook
└── README.md                           # Project documentation

🏀 What This Analysis Demonstrates
1. NBA Court–Mapped Movement Path

A clean scatter plot of the guard’s track points scaled to a true half-court.
Reveals:

Primary attack lanes

Where drives start and finish

Tempo change areas (color-coded speed)

2. Advantage Map (Separation + Pressure)

A court-overlay scatter showing where advantage states occur.
Useful for:

Understanding where the guard tends to create separation

Identifying whether spacing advantages happen early or late in the possession

Supporting scouting and player development workflows

3. Derived Movement Metrics

Automatically computed from tracking data:

Computed speed

Acceleration & deceleration load (COD load)

Distance traveled per possession

High-speed effort identification

4. Key Insight Summary

Printed summary includes:

Total distance covered

Peak speed and acceleration

Mean defender distance

Frames spent in advantage states

Number of high-speed efforts

These metrics provide a compact view of the guard’s physical and tactical behavior during the possession.

🧪 Technical Stack

Languages & Libraries

Python

pandas

NumPy

Matplotlib

Seaborn

Methods Included

Data cleaning & validation

Derived metric engineering

Coordinate transformation to NBA court space

Matplotlib-based court overlay construction

Movement visualization

Advantage-state mapping

Summary reporting

Environment

Google Colab (recommended)

Jupyter Notebook compatible

🚀 How to Run the Notebook

Open the notebook in Google Colab

Upload the included CSV when prompted

Run all cells

Generated visuals will include:

Movement Path (NBA Half Court)

Advantage Map

Key insight summary printout

No external dependencies beyond standard Python data libraries.

🔎 Why This Project Matters

This analysis demonstrates the ability to:

Work directly with tracking-style positional data

Apply sport science reasoning to basketball movement

Communicate findings clearly for coaches and scouts

Build reproducible workflows for client-facing use

Understand spatial context—an essential part of interpreting SkillCorner data

It reflects the type of applied analysis often used in:

Scouting & game-model profiling

Player development planning

Performance analysis

Client onboarding & education (SkillCorner-style workflows)

📬 Contact

If you'd like to discuss tracking data, applied sport science, or basketball analytics:

Chris Cothern
Website: https://www.chriscothern.com

LinkedIn: https://www.linkedin.com/in/chriscothern
