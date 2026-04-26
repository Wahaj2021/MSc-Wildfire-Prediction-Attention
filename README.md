# Enhancing Wildfire Prediction Using Attention-Based Deep Learning Models on WSN Data

## MSc Project — University of Roehampton

### Overview
This project extends the work of Haq et al. (2026) by implementing attention-based 
deep learning models for wildfire prediction using wireless sensor network data.

### Key Results
- **MHA Hybrid: 95.85% accuracy** (beats paper's 92.3% by +3.55%)
- ANN baseline: 95.44% accuracy
- 6 attention types tested: Bahdanau, Luong, Scaled Dot-Product, SE-Net, CBAM, Multi-Head
- 46 engineered temporal features from meteorological data

### Files
- `WildFire_MSC_Project_Final_.ipynb` — Complete Jupyter notebook (run on Google Colab)
- `wwo_bejaia_data.csv` — World Weather Online historical data for Bejaia, Algeria

### How to Run
1. Open `WildFire_MSC_Project_Final_.ipynb` in Google Colab
2. Upload `wwo_bejaia_data.csv` to the Colab environment
3. Run all cells from top to bottom

### Base Paper
B. Haq, M. A. Jamshed, B. Kasi, and M. K. Kasi, "Predicting Wildfires With Advanced 
Deep Learning Models on Wireless Sensor Data," IEEE Sensors Journal, vol. 26, no. 2, 
pp. 2797-2804, Jan. 2026.
