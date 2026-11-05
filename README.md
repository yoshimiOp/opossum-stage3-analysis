# opossum-stage3-analysis
analyzing Stage III of PN duration in Monodelphis domestica embryos

# Stage III Embryo Duration Analysis
This repository contains Python code used to analyze the duration of PN's Stage III in *Monodelphis domestica* embryos, as described in our paper.
- Process 3D pronuclear tracking data generated via TrackMate (ImageJ/Fiji).
- Integrate pronuclear radius dynamics to evaluate stage transitions.
- Calculate and plot the duration of Stage III in hours.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Usage
1. Ensure all required Python libraries are installed.
2. Place your TrackMate output CSV files and `radius.xlsx` in the designated `data/` directory.
3. Open `code.ipynb` and run the cells sequentially to reproduce the Stage III duration analysis and boxplot.
