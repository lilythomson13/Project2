# Project2
## Goal
Assess music genre trends over the past century and predict which genre of music will be the most listened to in the upcoming year. 
## Software and Platform
### Types of Software Used: 
- Programming Language: Python
- Data Processing & Analysis:
  - Pandas - Reading, cleaning, filtering, and merging the dataset
  - Facebook Prophet - Time series forecasting of genre popularity
- Data Visualization: Matplotlib & Seaborn
Creating bar charts, line graphs, and other custom visualization aesthetics
- Data Storage & Export: CSV Files
- Cloud Computing: Google Colab
### Packages Installed: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - prophet 
### Platforms Used: 
Windows & Mac

## Map of Documentation

```mermaid
graph TB
  A[Project2]
  A1[README.md]
  A2[LICENSE.md]
  B[SCRIPTS]
  B1[EDA.ipynb]
  B2[cleaning merged data.ipynb.ipynb]
  B3[genre predictive analysis.ipynb.ipynb]
  B4[genre trend analysis.ipynb.ipynb]
  B5[merging tracks and albums.ipynb]
  C[DATA]
  C1[cleaned_merged_tracks.csv]
  C2[raw_albums.csv.csv]
  C3[Data Appendix]
  D[OUTPUT]
]

  A --> A1
  A --> A2
  A --> B
  B --> B1
  B --> B2
  B --> B3
  B --> B4
  B --> B5
  A --> C
  C --> C1
  C --> C2
  C --> C3
  A --> D
  D --> D2
  D --> D3

  %% Styling for main project folder (Dark Blue)
  style A fill:#003366,stroke:#001f3f,stroke-width:2px,color:white;

  %% Styling for main categories (Light Blue)
  style A1 fill:#4a90e2,stroke:#003d5b,stroke-width:2px,color:white;
  style A2 fill:#4a90e2,stroke:#003d5b,stroke-width:2px,color:white;
  style B fill:#4a90e2,stroke:#003d5b,stroke-width:2px,color:white;
  style C fill:#4a90e2,stroke:#003d5b,stroke-width:2px,color:white;
  style D fill:#4a90e2,stroke:#003d5b,stroke-width:2px,color:white;

  %% Styling for subsets (Light Red)
  style B1 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style B2 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style B3 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style B4 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style B5 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style C1 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style C2 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style C3 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;
  style C4 fill:#ff9999,stroke:#8b0000,stroke-width:1px,color:black;

```

## Reproduction Instructions
