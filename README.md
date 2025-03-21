# YogaProject
A Yoga Pose Estimation project using a Teachable Machine-trained model. It classifies different yoga poses in real-time through webcam input using pose estimation and body landmarks.
# 🧘‍♀️ Yoga Pose Estimator – Teachable Machine Based Project

This project uses a pose estimation model trained on [Teachable Machine](https://teachablemachine.withgoogle.com/) to classify various yoga poses in real-time using a webcam feed. It leverages body landmarks and posture recognition to predict poses like Tree, Warrior, and Cobra.

---

## 🎯 Features

- Real-time pose detection through webcam
- Pre-trained model from Teachable Machine
- Easy-to-use and deployable in browser or Python environment
- Ideal for yoga practice feedback or educational demos

---

## 🧠 How It Works

1. Teachable Machine is used to train a custom pose estimation model.
2. The trained model is exported in `pose_model` format (`model.json` and weights).
3. Webcam captures real-time video.
4. Pose landmarks are extracted and passed to the model for prediction.

---

## 🗂️ Project Structure

