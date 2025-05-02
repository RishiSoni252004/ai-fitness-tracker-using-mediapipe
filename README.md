
# AI Fitness Tracker

**AI Fitness Tracker** is a computer vision-powered fitness application that uses **Mediapipe** and **OpenCV** to track and analyze exercise movements in real-time. The app helps users monitor their form, count repetitions, and improve workout efficiency through an intuitive, camera-based interface. It is perfect for learning AI-driven pose detection and building practical fitness applications.

---

## Features

- Real-time pose detection using Mediapipe
- Automatic repetition counting for exercises (e.g., squats, bicep curls)
- Visual feedback to improve exercise form and posture
- Lightweight and easy-to-run locally on CPU
- Simple, customizable codebase for adding new exercises

---

## Tech Stack

- **Frontend (Visualization)**: OpenCV (Python)
- **Backend (Pose Detection)**: Mediapipe
- **Programming Language**: Python
- **Other Tools/Libraries**: NumPy, Math, time

---

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.x installed  
- pip (Python package installer)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/RishiSoni252004/ai-fitness-tracker-using-mediapipe.git
cd ai-fitness-tracker-using-mediapipe
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the application**

```bash
streamlit run Demo.py
```

> 📷 Make sure your webcam is connected — the app will use it for real-time pose detection.

---

## Usage

- Select the exercise you want to track (default exercises: squats, bicep curls, push-ups)
- Start performing the exercise — the app will automatically count repetitions and give visual feedback
- To end the session, simply close the window


---

## License

This project is licensed under the **MIT License**.
