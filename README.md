# Brain-tumor-prediction

This project is a **Brain Tumor Prediction System** that uses machine learning / deep learning to detect the presence of a brain tumor from MRI images.
It helps in early diagnosis by analyzing MRI scans and predicting whether a tumor is:

-Present
- Not Present

This project shows how medical image processing and neural networks can support healthcare decisions.

---

## Key Features**

* MRI image classification
* Preprocessing (resizing, normalization, grayscale/RGB conversion)
* Deep learning model (CNN or transfer learning depending on your setup)
* High accuracy on test images
* Ability to predict on new MRI images
* Clear and beginner-friendly code
* Visualization of training graphs (accuracy/loss curves)

---

## **Tech Stack**

Modify this depending on what you used:

* **Python**
* **TensorFlow / Keras** or **PyTorch**
* **OpenCV** or **PIL** for image processing
* **NumPy & Pandas**
* **Matplotlib** for visualizations
* Jupyter Notebook or `.py` scripts

---

# **How to Open & Run the Project on Your Laptop**

### **1. Download the Project**

* Go to your GitHub repository
* Click the **Code** button
* Select **Download ZIP**

### **2. Unzip the File**

* Go to your Downloads folder
* Right-click → **Extract All** (Windows)
* Or double-click to unzip (Mac)

### **3. Open the Project Folder**

Inside the unzipped folder, you will see:

* MRI dataset folders (e.g., `yes/`, `no/`)
* `.ipynb` notebook
* Python scripts
* Model files (if saved)
* `requirements.txt`

---

## **4. Install Required Libraries**

Open your Terminal (Mac) or Command Prompt (Windows) and run:

```
pip install numpy pandas matplotlib tensorflow opencv-python scikit-learn
```

If a `requirements.txt` file exists:

```
pip install -r requirements.txt
```

---

## **5. Run the Code**

### **Option A — Using Jupyter Notebook**

If your project contains a `.ipynb` file:

```
jupyter notebook
```

* Open the notebook
* Run each cell in order

### **Option B — Using Python Script**

If you have a script like `predict.py`:

```
python predict.py
```

### **Option C — Load and test your trained model**

Most projects include a `model.h5` or `.pt` file.
You can load it inside your script or notebook to predict on new images.

---

## **6. Making a Prediction**

If it’s a `.ipynb` notebook:
You will see a cell where you can upload/select an MRI and the model predicts:

```
Tumor Detected   
or  
No Tumor Detected
```

If it's a script:

```
python predict.py --image path/to/mri_image.jpg
```

---

## **7. Outputs**

The program displays:

* Prediction result
* Confidence score
* MRI image preview (optional)
* Training accuracy/loss graphs
