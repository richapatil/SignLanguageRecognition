# ✋ Sign Language Recognition (SLR) using Computer Vision and Deep Learning

## 📌 About the Project
This is a **BTech Final Year Project** focused on **Sign Language Recognition**.  
The project uses **Python, OpenCV, and Deep Learning** to capture, process, and classify hand gestures.  

Key functionality includes:
- Hand detection and histogram creation
- Gesture image collection and preprocessing
- Training and evaluating a CNN model for gesture recognition
- Real-time display of recognized gestures

---

## 🎯 Objectives
- Capture hand gestures using a webcam  
- Preprocess images and extract features using HSV color histograms  
- Train a Convolutional Neural Network (CNN) for gesture classification  
- Recognize and display gestures in real time

---

## 🛠️ Technologies Used
- Python  
- OpenCV  
- NumPy  
- TensorFlow / Keras (for CNN model)  
- Pickle (for saving hand histograms)  
- Jupyter Notebooks  

---

## 📂 Project Structure




---

## ⚙️ How the Project Works
1. **Hand Histogram Setup**:  
   - Run `set_hand_histogram.ipynb` to capture your hand and generate a histogram.  
   - Press `C` to capture histogram and `S` to save and exit.

2. **Create Gestures**:  
   - Run `Create_gesture.ipynb` to capture gesture images for the dataset.  

3. **Preprocessing**:  
   - Use `Rotate_images.ipynb` and `load_images.ipynb` to augment and load images.  

4. **CNN Training**:  
   - Train the model using `cnn_modle_train.ipynb`.  
   - The trained model is saved as `cnn_model_keras2.h5`.

5. **Display Gestures**:  
   - Run `display_gesturers.ipynb` or `final.ipynb` for real-time gesture recognition.  

---

## ▶️ How to Run
### 🔹 Prerequisites
```bash
pip install opencv-python numpy tensorflow keras
```

### 🔹Running Notebook Scripts

Open Jupyter Notebook in the gestures/ folder:

```bash
jupyter notebook
```

Run the notebooks in the order:

1. set_hand_histogram.ipynb
2. Create_gesture.ipynb
3. Rotate_images.ipynb
4. cnn_modle_train.ipynb
5. display_gesturers.ipynb or final.ipynb

### Output

- hist → Hand histogram file
- cnn_model_keras2.h5 → Trained CNN model
- Gesture images → stored in train_images, val_images, test_images
- Labels → train_labels, val_labels, test_labels

--- 

## 🚀 Future Scope

- Enhance CNN model for higher accuracy
- Real-time sentence recognition using multiple gestures
- Integrate text-to-speech for sign language output
- Deploy as a web or mobile application

---

## 👩‍💻 Contributors

1. Riteeka Purnekar
2. Richa Patil
3. Nilesh Mahajan

