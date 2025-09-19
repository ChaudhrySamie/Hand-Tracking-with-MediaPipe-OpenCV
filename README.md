===============================
📌 README.md
===============================
# Hand Detection with MediaPipe & OpenCV

This project uses **MediaPipe** and **OpenCV** to detect and track hands in real time using your laptop/webcam.  
It can track up to **two hands** simultaneously and visualize hand landmarks with connections.

---

## 🚀 Features
- Real-time **hand detection** via webcam  
- Tracks up to **two hands**  
- Visualizes **landmarks and connections**  
- Press **Q** to quit the program  

---

## 🛠️ Requirements

- Python **3.11** (recommended for Mediapipe compatibility)  
- Virtual environment (optional but recommended)  

### Install dependencies
```bash
pip install opencv-python mediapipe

##If you don’t have pip updated:
```bash
python -m pip install --upgrade pip

▶️ Usage

##Clone this repository:

git clone https://github.com/your-username/hand-detection.git
cd hand-detection


##(Optional but recommended) Create & activate virtual environment:

python -m venv handenv
handenv\Scripts\activate   # On Windows
source handenv/bin/activate # On Mac/Linux


##Install required packages:

pip install -r requirements.txt


##Run the program:

python hand_detection.py


##Press Q to exit.

📂 Project Structure
hand-detection/
│── hand_detection.py    # Main script
│── requirements.txt     # Dependencies
│── README.md            # Documentation
