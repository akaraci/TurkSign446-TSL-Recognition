# TurkSign446 - Turkish Sign Language Recognition

This repository contains the source code for the paper:

**"TurkSign446: A Comprehensive Dataset and Hybrid Deep Learning Approach for Real-Time Turkish Sign Language Recognition"**  
Authors: Cumhur Torun, Abdulkadir Karacı  
Submitted to *The Visual Computer (Springer)*, 2025.  

---

## 📊 Dataset
The dataset **TurkSign446** includes **446 Turkish Sign Language (TSL) words** (133 static, 313 dynamic), collected from 10 participants with 10 repetitions each.  
- Total videos: 44,600  
- Total frames: 1.3 million+  
- Features extracted with **MediaPipe Holistic** (1662 features per frame, stored in NumPy format).  

👉 The dataset is openly available on Zenodo:  
[Zenodo Dataset DOI - to be added after upload]  

Please cite both the dataset DOI and the manuscript when using this dataset.  

---

## ⚙️ Requirements

The code was developed and tested with the following environment:

- Python 3.9+
- TensorFlow 2.13
- Keras 2.13
- MediaPipe 0.10.0
- NumPy 1.24
- OpenCV 4.7
- Matplotlib 3.7
- Scikit-learn 1.3

📖 Citation
If you use this dataset or code, please cite:
@article{Karaci2025_TurkSign446,
  title={TurkSign446: A Comprehensive Dataset and Hybrid Deep Learning Approach for Real-Time Turkish Sign Language Recognition},
  author={Torun, Cumhur and Karacı, Abdulkadir},
  journal={The Visual Computer},
  year={2025},
  publisher={Springer}
}

🧠 Models Implemented
CNN
LSTM
GRU
Bi-LSTM
Hybrid models: CNN+GRU, CNN+LSTM, CNN+Bi-LSTM, GRU+LSTM, GRU+Bi-LSTM

Best-performing model: CNN+GRU, achieving 97.88% accuracy (offline) and 85.5% accuracy (real-time, user-dependent) / 80.27% accuracy (real-time, user-independent)


