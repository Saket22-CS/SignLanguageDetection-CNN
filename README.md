# 🧠 Sign Language Detection Using Deep Learning 🤟

This project focuses on recognizing hand gestures from static images using a custom Convolutional Neural Network (CNN) built with TensorFlow/Keras. The model is trained to classify six basic hand gestures representing sign language digits using grayscale image data and OpenCV-based image preprocessing.

---

## 📁 Project Structure

```bash
├── Code/
│   ├── TrainingHandGesture.py         # CNN model training script
│   ├── HandGestureRecognitionOpenCV.py# Real-time hand gesture detection with OpenCV
│   └── test.py                        # Script to test trained model on individual images
├── HandGestureDataset/               # Image dataset (train/test)
├── model.h5                          # Trained CNN model
├── requirements.txt                  # Required Python libraries
```

---

## 📌 Features

✅ Real-time hand gesture detection with OpenCV  
✅ Custom CNN for classification (trained on 256x256 grayscale images)  
✅ Easy testing on new data  
✅ Works offline, lightweight  
✅ Uses six classes: `NONE`, `ONE`, `TWO`, `THREE`, `FOUR`, `FIVE`

---

## 🏗️ How It Works

1. **Training**
   - Run `TrainingHandGesture.py` to train the CNN on your dataset.
   - The model is saved as `model.h5`.

2. **Testing on New Images**
   - Use `test.py` to classify new images in a folder.

3. **Real-Time Detection**
   - Launch `HandGestureRecognitionOpenCV.py` to detect gestures in webcam feed.

---

## 🔧 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Dependencies include:
- `tensorflow`
- `opencv-python`
- `numpy`
- `keras`

---

## 🚀 Future Scope

To improve this project, consider:
- Integrating MediaPipe Hands for more reliable tracking.
- Adding dynamic gesture recognition using LSTM.
- Deploying via Streamlit or Flask for a web interface.
- Expanding the gesture vocabulary to cover full ASL.

---

## 🤝 Contributing

Feel free to fork this repo, improve the code, and submit pull requests. Contributions are welcome!

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- Dataset and inspiration from self-collected and open gesture sets.
- Built during AI internship learning sessions using OpenCV and TensorFlow.

---

## 👨‍💻 Author

**Saket Chaudhary**  
📧 saketrishu64821@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/saket-chaudhary22) | [GitHub](https://github.com/Saket22-CS)