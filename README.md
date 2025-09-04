# 🎛️ GestuMedia Control ✋

A **gesture-based system control project** built in Python that allows you to **adjust brightness, volume, mute/unmute, and play/pause media** using hand gestures.  
It uses **OpenCV + MediaPipe** for real-time hand tracking and provides an **On-Screen Display (OSD)** for live feedback.  

---

## 📌 Project Overview  
GestuMedia Control uses computer vision and audio APIs to create a **contactless control system**.  
By pinching your thumb with different fingers, you can control system settings in real-time.  

---

## ✨ Features  
- 📺 **Brightness Control** → Thumb + Index finger  
- 🔊 **Volume Control** → Thumb + Middle finger  
- 🔇 **Mute/Unmute** → Thumb + Ring finger  
- ⏯️ **Play/Pause Media** → Thumb + Pinky finger  
- 🖥️ **On-Screen Display (OSD)** → Visual bars & indicators  

---

## 🛠️ Tools & Libraries  

| Library | Version | Purpose |
|---------|---------|---------|
| Python | 3.10+ | Main programming language |
| OpenCV (`opencv-python`) | 4.8.1.78 | Real-time video capture & OSD |
| MediaPipe | 0.10.8 | Hand landmark detection |
| NumPy | 1.26.0 | Math operations & interpolation |
| screen-brightness-control | 0.22.2 | System brightness control |
| PyCaw | 20230407 | Audio control (volume, mute) |
| Comtypes | 1.1.14 | Windows COM interface (required by PyCaw) |
| ctypes (built-in) | – | Play/Pause media key events |
| time (built-in) | – | Debouncing gesture actions |
| collections (deque) | – | Smoothing brightness/volume values |

---

## ⚙️ System Requirements  
- **OS**: Windows 10/11  
- **Python**: 3.10 or higher  
- **Hardware**: Webcam (720p or better recommended)  

---

## 📦 Installation  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/gestumedia-control.git
   cd gestumedia-control
