 Galaxy Classification Project
 
This is my first project in data science domain. This project is about to build a machine learning pipeline for classifying galaxies into morphological categories using NASA skyview data.

📌 Objectives
- Gain hands-on experience with **image processing** and astronomical data (FITS format).  
- Enhance skills in **data science & deep learning** through an end-to-end ML project.  
- Create an **industry-ready GitHub project** demonstrating dataset acquisition, preprocessing, modeling, and evaluation.  

 🛰️ Dataset
- NASA SkyView Virtual Observatory ([link](https://skyview.gsfc.nasa.gov/current/cgi/query.pl))  
- Surveys like **DSS**, **2MASS**, or **SDSS** depending on coverage and quality.  

The pipeline will automatically download images of galaxies and prepare them for training.

## ⚙️ Project Structure

galaxy-classification/
│
├── data/
│   ├── raw/        # Raw FITS images from NASA SkyView
│   ├── processed/  # Converted PNG/JPEG, resized
│   └── labels.csv  # Metadata (object name, class label, survey info)
│
├── notebooks/
│   ├── 01_data_download.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_evaluation_visualization.ipynb
│
├── src/
│   ├── data_loader.py     # Script to download FITS images
│   ├── preprocess.py      # FITS → PNG, resizing, normalization
│   ├── model.py           # CNN model (PyTorch / TensorFlow)
│   └── utils.py           # Helper functions
│
├── environment.yml        # Conda environment (dependencies)
├── README.md              # Project overview
└── requirements.txt       # Pip dependencies

🔧 Tools & Libraries
- Python 3.13.5
- `astroquery` – for fetching NASA SkyView data  
- `astropy` – for handling FITS files  
- `opencv` / `PIL` – for image processing  
- `tensorflow` / `pytorch` – for deep learning models  
- `matplotlib` / `seaborn` – for visualization  

 🚀 Roadmap
1. Acquire galaxy images from **NASA SkyView**.  
2. Convert and preprocess images for ML.  
3. Build and train a **CNN classifier**.  
4. Evaluate with metrics & visualizations.  
5. Document results and improvements.  

## 📂 Status
Project in **early development** (Step 1: Setup & Dataset acquisition).  

---


