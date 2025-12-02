# Machine Learning Project — Teachable Machine (LIS 500)

This is the repo for **Project 3: Machine Learning**, created for LIS 500. Our project explores basic image classification using Google’s Teachable Machine and examines how concepts from **Joy Buolamwini’s _Unmasking AI_** and **Ellen Pao’s _Tech, Heal Thyself_** connect to issues of bias, representation, and fairness in machine learning.

---

## 📸 What This Project Does
This project includes a simple **image classifier** that runs directly in the browser using a webcam.  
It uses TensorFlow.js and a Teachable Machine–trained model to recognize three object categories based on color:

- **Red Scissors**  
- **Black Bottle**  
- **Blue Sticky Note**

Users can click a “Camera” button to start the webcam and view live predictions, updated in real time.

The project also includes a video demonstration showing the model in action.

---

## 🧠 Model Information
- Built with **Teachable Machine — Image Classifier** | Exported using **TensorFlow.js**
- Uses MobileNet-based architecture under the hood

- Dataset includes roughly 60+ images collected under varied:
  - Angles  
  - Lighting conditions  
  - Backgrounds  
  - Distances  

This intentional variation helped reduce environmental bias and provided more robust predictions.

---

## 💡 Ethical Framework
Our approach was strongly influenced by lessons from:

### **Unmasking AI — Joy Buolamwini**
- Bias is a design choice, not an accident  
- Representation matters  
- Fair AI must be intentional  

We avoided any human subject–based classifications to prevent demographic or facial-recognition related harms.

### **Tech, Heal Thyself — Ellen Pao**
- Power structures shape who builds technology  
- Diversity doesn’t automatically fix biased systems  
- Fair systems require intentional design choices  

These ideas informed our dataset collection process and our decision to focus on harmless object classification.

---

## 🛠️ How To Run Our Project

1. Clone or download this repository.
2. Make sure the exported Teachable Machine model folder is named **project/** with: `model.json`, `metadata.json`, and the `weights.bin` file
3. Open project.html in any modern browser.
4. Click the **Camera** button to start the webcam, and hold one of the trained objects up to the camera to see real-time predictions.

---

## 📁 File Structure

* /project
* ├── model.json
* ├── metadata.json
* ├── weights.bin

* /videos
* └── demo.mp4 (update later)

* index.html
* about-us.html
* resources.html
* tech-heroes.html
* project.html
* README.md
* stylepage.css

---

## 👥 Group Members
- *Jason Thronson*
- *Dhanvi Kanade*
- *Orion King*

---

## 🔗 Demonstration
https://jasonthronson99.github.io/lis500-project3

---

## 📜 License
This project is for educational purposes as part of LIS 500 and is not intended for commercial use.

---
