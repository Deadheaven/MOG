# Real-Time Motion Detection using Background Subtraction (MOG/MOG2)

A Python project for detecting motion in video streams using Gaussian Mixture Models (MOG and MOG2) for background subtraction. The system processes real-time webcam input or video files to identify and highlight moving objects.

---

## 📋 Features
- **Real-Time Processing**: Detect motion from live webcam feeds or video files.
- **Background Subtraction**: Uses MOG and MOG2 algorithms for motion detection with dynamic background learning.
- **Customizable Parameters**: Adjust history, threshold, and learning rate to suit various environments.
- **Visual Output**: Displays detected motion regions with bounding boxes or masks.
- **Optional Logging**: Save frames with detected motion for later analysis.

---

## 💻 Technologies Used
- **Programming Language**: Python  
- **Core Library**: OpenCV  

---

## 🔍 Use Cases
- Security surveillance systems  
- Monitoring activity in restricted areas  
- Event triggering in home automation systems  

---

## 🚀 Getting Started

### Prerequisites
1. Python 3.6+ installed on your system.  
2. Install required Python packages using:  
   ```bash
   pip install -r requirements.txt
### Installation
1. Clone the repository:

bash
Copy code
git clone https://github.com/username/mog-motion-detection.git
cd mog-motion-detection
2. Connect a webcam or ensure the availability of a video file.

3. Run the script:

bash
Copy code
python motion_detection.py
