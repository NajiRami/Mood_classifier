<h1 align="center">🏠✨ Smart Smile Gate – AI Face Access Control</h1>

<p align="center">
An AI-powered system that analyzes the user's face, and if the person is <b style="color:green">smiling</b>, they are granted access.  
If not smiling ❌ access is denied.
</p>

---

## 🔍 Concept
Instead of using fingerprint or access cards, this system relies on Facial Expression Recognition to decide whether to open the door.  
Smile = Access ✅  
No Smile = Denied ❌

---

## 🧠 How It Works
1. 📷 Capture a face image using a camera
2. 🧠 An AI model detects the facial expression
3. ✅ If a smile is detected → the door opens
4. ❌ If no smile is detected → access is denied

---

## 📸 Examples (Placeholders)

| Status | Image | Result |
|--------|--------|--------|
| 😊 Smiling | ![smile-placeholder](images/smile.png) | ✅ Access Granted |
| 😐 Not Smiling | ![nosmile-placeholder](images/nosmile.png) | ❌ Access Denied |

---

## ⚙ Technologies Used
- 🐍 Python
- 🧠 TensorFlow / Keras
- 👁 OpenCV
- 📊 Deep Learning (CNN)

---

## ▶ Run the Project
```bash
git clone https://github.com/NajiRami/Mood_classifier.git
cd Mood_classifier
pip install -r requirements.txt
