# Posture Pro: Real-Time Spine Corrector 🧘‍♂️
Posture Pro is an AI-powered desktop application designed to monitor your posture in real-time. Using Computer Vision, it detects slouching or improper neck angles and alerts you to sit up straight, helping prevent long-term spinal issues.

🚀 Features
Real-Time Detection: Monitors shoulder and neck alignment using a standard webcam.

Visual Feedback: Overlays a skeletal wireframe on the video feed to show your current posture.

Alert System: Notifies the user when they have been slouching for a specific duration.

Lightweight: Optimized to run efficiently on most laptops without a dedicated GPU.

🛠️ Tech Stack
Language: Python

Library: OpenCV (Image Processing)

AI Model: MediaPipe (Pose Estimation)

Math: NumPy (Angle Calculation)

⚙️ Installation:
Clone the repository:
git clone https://github.com/your-username/posture-pro-cv.git
cd posture-pro-cv

Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

📈 How it Works
The system calculates the angle between the Ear, Shoulder, and Hip landmarks provided by MediaPipe. If the angle falls below a certain threshold (e.g., 165°), the system flags it as "Bad Posture."

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
