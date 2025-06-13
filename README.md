# ML-aadhaar-authentication
A lightweight, real-time Aadhaar card image Validation system using Support Vector Machine (SVM) and OpenCV. Built with Python and Tkinter, this tool classifies Aadhaar images as valid or invalid using machine learning and image preprocessing techniques.
A real-time Aadhaar validation system built entirely in a **single Jupyter Notebook**. This project uses image processing and machine learning (SVM) to classify Aadhaar card images as **valid** or **invalid**, with a fully integrated GUI for prediction.

---

## 📌 Features

- 📄 Extracts text from Aadhaar PDFs
- 🖼️ Converts PDF to image using `pdf2image`
- 🧼 Filters non-English (Gujarati) characters
- 🧠 Trains an SVM classifier on real Aadhaar images
- 🧪 Simulates invalid Aadhaar images via image flipping
- 🖥️ Built-in Tkinter GUI for live image prediction
- ✅ Output: “VALID” or “INVALID” based on model prediction



> **Note**: All training, preprocessing, GUI logic, and prediction steps are contained within the notebook.

---

## 🧠 Technologies Used

- **Python** (Jupyter Notebook)
- **OpenCV** — image preprocessing
- **scikit-learn** — SVM, GridSearchCV
- **Tkinter** — GUI for image validation
- **PyPDF2 / pdf2image** — Aadhaar PDF handling
- **joblib** — for model saving/loading

---

## 🧪 Dataset

- ✅ 21 real valid Aadhaar card images
- ❌ Simulated invalids created by flipping valid images
- Dataset directory: `Downloads/archive (7)`

---

## 📊 Performance

- Accuracy: **~97%**
- F1-Score: **0.98**
- Model: **SVM with RBF kernel (C=1)**

---

## 🖥️ GUI Snapshot

> Tkinter-based GUI includes:
- Upload Aadhaar image
- Preview selected image
- Instant prediction result (green ✅ or red ❌)

---

## 🔮 Future Enhancements

- Replace simulated invalids with real-world samples
- CNN or Transformer-based classifier
- Web-based interface (Flask/Streamlit)
- Integration with Aadhaar OCR + database matching

---

## 👤 Author

**Nensi Chavda**  
B.Tech CSE  — G H Patel College of Engineering & Technology  
📧 nensichavda7@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/nensi-chavda-b7baa3253/) • [GitHub](https://github.com/Nensi7)

---

> 💡 *This is a compact, offline-friendly, ML-based Aadhaar validator project — ideal for practical demos, student portfolios, and low-resource systems.*

