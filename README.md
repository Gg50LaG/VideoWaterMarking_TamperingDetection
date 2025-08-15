# Open Video Watermarking & Tampering Detection

A Python + Flask-based application for video watermarking and tampering detection.  
This project allows you to upload videos, apply watermarks, and verify authenticity through tamper detection.

---

## Features
- Upload and process videos in the browser
- Apply robust watermarking techniques
- Detect tampering or alterations
- Flask-based web interface
- Works on Ubuntu (WSL compatible)

---

## Installation & Setup (Ubuntu 24.04 / WSL)

# Install Required Packages
sudo apt update
sudo apt install python3 python3-pip python3-venv
sudo apt install libgl1

# Clone the Repository
git clone https://github.com/Gg50LaG/VideoWaterMarking_TamperingDetection.git
cd VideoWaterMarking_TamperingDetection

# Create & Activate Virtual Environment
python3 -m venv .venv
source .venv/bin/activate

# Install Python Dependencies
pip install --upgrade pip
pip install -r requirements.txt

# Run the Application
python app.py


# If successful, you’ll see:

 * Running on http://127.0.0.1:8000
