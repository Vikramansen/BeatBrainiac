# BeatBrainiac

Implemented a [Research paper](https://ieeexplore.ieee.org/document/9449177) on Music Genre Classification by emplying LSTM. 

BeatBrainiac is an advanced Music Genre Classification tool utilizing LSTM (Long Short-Term Memory) networks, alongside Time and Frequency Domain Features. This project aims to accurately classify music into various genres, providing a unique blend of time-series analysis and machine learning techniques.

---

## Installation and Usage

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Installation
1. **Clone the Repository**
   ```
   git clone [https://github.com/Vikramansen/BeatBrainiac.git]
   cd BeatBrainiac
   ```

2. **Install Dependencies**
   ```
   pip install -r requirements.txt
   ```

### Usage
1. **Run Preprocessing**
   - Execute `preprocessing.ipynb` to prepare your dataset.

2. **Train and Evaluate Models**
   - Use `LSTM.ipynb` for LSTM model training and evaluation.
   - Optionally, explore `SVM_KNN.ipynb` for SVM and KNN models.

3. **Perform Classification**
   - Apply the trained models in `classification.ipynb`.

4. **Utilize Utilities**
   - Employ `utils.py` for additional functions.

### Running Notebooks
- Launch Jupyter Notebooks:
  ```
  jupyter notebook
  ```
- Open and run each notebook via the Jupyter interface.

### Troubleshooting
- For issues, ensure pip is up-to-date and retry dependencies installation.

### Support
- For assistance or bug reporting, contact me or use the issue tracker on GitHub.
