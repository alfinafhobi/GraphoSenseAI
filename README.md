# GraphologyAI

**GraphologyAI** is an AI-powered handwriting emotion recognition system that analyzes handwritten text images to predict the writer's emotional state. The project combines **deep learning** with **handcrafted handwriting features** to improve classification performance by capturing both visual and structural characteristics of handwriting.

The system utilizes a **ResNet-18** based Convolutional Neural Network (CNN) along with handcrafted feature fusion to classify handwriting into six emotional categories: **Happy, Calm, Confident, Sad, Angry, and Stressed**.

---

## Features

- AI-powered handwriting emotion recognition
- Hybrid feature extraction using deep learning and handcrafted features
- ResNet-18 based CNN architecture
- Image preprocessing pipeline
- Emotion prediction from handwriting images
- Feature fusion for improved accuracy
- End-to-end training and inference workflow

---

## Emotion Classes

- 😊 Happy
- 😌 Calm
- 💪 Confident
- 😔 Sad
- 😠 Angry
- 😣 Stressed

---

## Dataset

This project is trained using publicly available handwriting datasets:

- **CVL Handwriting Dataset**
- **IAM Handwriting Database**

These datasets provide diverse handwritten text samples that are preprocessed and used for model training and evaluation.

---

## Project Structure

```
GraphologyAI/
│
├── backend/
│   ├── models/
│   ├── utils/
│   ├── dataset/
│   ├── train.py
│   ├── predict.py
│   └── app.py
│
├── frontend/
│
├── uploads/
│
├── requirements.txt
│
└── README.md
```

---

## Tech Stack

- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Flask
- HTML
- CSS
- JavaScript

---

## Workflow

1. Upload a handwriting image.
2. Perform image preprocessing.
3. Extract handcrafted handwriting features.
4. Extract deep visual features using ResNet-18.
5. Fuse both feature sets.
6. Predict the corresponding emotion class.
7. Display the predicted emotion.

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/GraphologyAI.git
cd GraphologyAI
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Future Enhancements

- Support multiple handwriting languages
- Real-time handwriting recognition
- Personality trait analysis
- Mobile application deployment
- Explainable AI (XAI) for prediction visualization
- Improved hybrid feature engineering

---

## Author

**Alfina Fhobi R**.

---

## License

This project is intended for educational and research purposes.
