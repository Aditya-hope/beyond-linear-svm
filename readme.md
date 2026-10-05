# SVM Kernels: Intuition and Implementation

A hands-on notebook showing why SVM kernels matter. It builds two concentric circles (a dataset no straight line can separate) and compares how the **linear**, **polynomial**, **RBF** and **sigmoid** kernels handle it.

## What's inside
- Generating a two-class concentric circle dataset with NumPy
- Visualising the data with Matplotlib and 3D Plotly scatter plots
- Manual polynomial feature expansion (`X1²`, `X2²`, `X1*X2`)
- Training `SVC` with each kernel and comparing accuracy

## Setup
```bash
git clone https://github.com/Aditya-hope/svm-kernels.git
cd svm-kernels
python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook SVM_Kernels_Implementation.ipynb
```

## Tech
Python, NumPy, Pandas, Matplotlib, Plotly, scikit-learn

## License
MIT