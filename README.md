MetaFit – Yoga Posture Detection System

MetaFit is a yoga posture detection system built using OpenCV, NumPy, MediaPipe,Pandas as Backend and Front end using React.js, WebSocets.  
It helps users perform yoga poses correctly by tracking body keypoints in real time, detecting incorrect postures, and providing actionable feedback.

---

Features

- Real-time Pose Detection – Tracks body joints using webcam input  
- Yoga Posture Analysis – Detects angles at key joints to evaluate posture accuracy  
- Instant Feedback – Highlights incorrect alignment for immediate correction  
- Lightweight & Fast – Runs efficiently on CPU without requiring GPU support  
- Customizable Poses – Can be extended to support new yoga postures

---

Tech Stack

- **Programming Language:** Python  
- **Libraries:** OpenCV, NumPy, Pandas  
- **Model:** MediaPipe Pose (for keypoint detection)  

---

Installation

1. *Clone the repository*
git clone https://github.com/TanmaySantra/MetaFit.git
cd MetaFit
Create a virtual environment (optional but recommended)

bash
Copy code
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
Install dependencies

bash
Copy code
pip install -r requirements.txt
Usage
Run the application

bash
Copy code
python metafit.py
Perform yoga poses in front of your webcam

The system will track your body joints in real-time

Correct/incorrect posture feedback will be displayed

Project Structure
bash
Copy code
MetaFit/
│
├── metafit.py           # Main application file
├── requirements.txt     # Python dependencies
├── utils/               # Helper scripts (angle calculations, drawing functions)
├── poses/               # Pose configurations and reference data
└── README.md            # Project documentation
Future Enhancements
Add voice feedback for better user experience

Support additional yoga poses with custom datasets

Deploy as a web app using React + Flask/Express backend

Integrate with fitness tracking APIs for progress monitoring

Contributing
Contributions are welcome!

Fork the repo

Create a feature branch (git checkout -b feature-name)

Commit changes (git commit -m 'Add feature')

Push to branch (git push origin feature-name)

Open a pull request


Author
Tanmay Santra

GitHub: @TanmaySantra

LinkedIn: linkedin.com/in/tanmaysantra09
