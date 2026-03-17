# 🧠 Intent Prediction from Human Movement (CNN + LSTM)

## 📌 Overview

This project focuses on predicting human actions using **early visual cues** from image sequences.
Instead of recognizing actions after they occur, this model attempts to **predict intent from initial frames**.

This approach is useful in:

* 🚗 Autonomous driving (predict pedestrian movement)
* 🏥 Healthcare (fall detection & prevention)
* 🎮 Sports analytics (anticipating player actions)
* 🛡️ Surveillance systems (early threat detection)

---

## ⚙️ Tech Stack

* Python
* OpenCV
* NumPy
* TensorFlow / Keras
* Scikit-learn

---

## 🧠 Model Architecture

The model combines:

* **CNN (Convolutional Neural Network)** → Extracts spatial features from frames
* **LSTM (Long Short-Term Memory)** → Learns temporal patterns

### Pipeline:

```
Image Sequence → CNN → Feature Extraction → LSTM → Action Prediction
```

---

## 📂 Dataset

* Dataset: **HMDB51**
* Type: Image sequences (video frames)
* Classes: 51 human actions
* Example actions:

  * Running
  * Jumping
  * Kicking
  * Climbing

---

## 🔄 Data Processing

* Frames resized to fixed resolution (e.g., 64x64)
* Normalization applied
* Fixed-length sequences created
* Padding for shorter sequences

---

## 🧪 Training

* Loss: Categorical Crossentropy
* Optimizer: Adam
* Train/Test Split: 80/20

---

<img width="1152" height="507" alt="image" src="https://github.com/user-attachments/assets/acbffa58-db14-472d-918d-9a9a9b1b863c" />
<img width="1162" height="524" alt="image" src="https://github.com/user-attachments/assets/af49b163-618b-4465-85a7-a52ae6320434" />


## 📊 Results

* Achieved baseline accuracy on subset of HMDB51
* Model successfully learns temporal motion patterns

---

## 🚀 Future Improvements

* 🔥 Use Transformer-based models
* 🎯 Add attention mechanism
* 📈 Increase dataset size
* ⚡ Real-time prediction using webcam

---

## 💡 Key Insight

> This project shifts from *action recognition* to *intent prediction*, enabling earlier and smarter decision-making systems.

---

## 🧑‍💻 Author

**Jeeva M I**
AI & Data Science

---

## ⭐ If you like this project

Give it a ⭐ on GitHub

<img width="1150" height="676" alt="image" src="https://github.com/user-attachments/assets/0757d7ca-36bd-4094-a856-f4c2725d5944" />
<img width="1117" height="369" alt="image" src="https://github.com/user-attachments/assets/a47f4a99-8000-4d98-b1fd-65954d231d52" />

