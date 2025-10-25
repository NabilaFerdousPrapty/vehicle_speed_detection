# Industrial Attachment Report at ATC Tech Ltd.

**Submitted to:** Department of Electrical and Computer Engineering,  
Rajshahi University of Engineering & Technology (RUET), Rajshahi-6204, Bangladesh

**Course:** ECE 4100: Industrial Training  
**Title:** Industrial Attachment at ATC Tech Ltd., Rajshahi

---

## Acknowledgement

The industrial attachment at ATC Tech Ltd. has been a highly enriching experience. I express my deepest gratitude to Almighty Allah for the strength, patience, and capability to successfully complete this program.

I am grateful to the team at ATC Tech Ltd. for their constant support and guidance. Their mentorship significantly enhanced my learning experience.

I would like to extend heartfelt thanks to **Fariya Tabassun**, Head of the Department of Electrical and Computer Engineering at RUET, for her continuous guidance and encouragement.

Special thanks to ATC Tech Ltd.’s mentors and engineers who provided practical insights and knowledge, helping me gain hands-on experience in machine learning, computer vision, and real-world project execution.

Finally, I thank my family and friends for their unwavering support and encouragement throughout this journey.

---

## Chapter 1: Overview

### Industrial Attachment Overview

Industrial attachment provides students the opportunity to apply theoretical knowledge in real-world scenarios. At ATC Tech Ltd., we gained practical experience in **machine learning, computer vision, and AI-based vehicle monitoring systems**.

### Motivation

I chose ATC Tech Ltd. to apply academic concepts to a practical AI project, gain exposure to industry-standard tools, and develop hands-on skills in Python, PyTorch, OpenCV, and real-time video analytics.

### Objectives

- Understand machine learning workflow from dataset preparation to model evaluation.
- Implement real-time vehicle detection, tracking, and speed measurement.
- Learn to generate automated overspeed alerts for different vehicle types.
- Develop professional skills like teamwork, problem-solving, and project documentation.

---

## Chapter 2: About ATC Tech Ltd.

### Background

ATC Tech Ltd., headquartered in Rajshahi, Bangladesh, is a software and technology company specializing in **AI, machine learning, and digital solutions**. The company focuses on building innovative applications for clients across multiple industries, including traffic management and monitoring systems.

### Mission & Vision

- **Mission:** To deliver innovative and practical AI-driven solutions for real-world problems.
- **Vision:** To become a globally recognized technology company empowering industries through intelligent systems.

### Expertise

- Machine Learning & Deep Learning
- Computer Vision and Image Processing
- AI-powered Analytics
- Software Development & System Integration

### Services

- AI/ML Consulting & Implementation
- Vehicle Detection & Traffic Analytics Systems
- Custom Software Solutions
- Training & Workshops

### Clients

- Public and private organizations, including traffic monitoring agencies and technology startups.

### Technology

- **Programming & ML:** Python, PyTorch, NumPy, Pandas
- **Computer Vision:** OpenCV, YOLO12s
- **Data Handling & Analytics:** Pandas, NumPy

### Skills

- ML model training and evaluation
- Real-time video processing and object tracking
- Dataset preparation and augmentation
- Analytical thinking and problem-solving

### Workflow

1. Dataset collection and preprocessing
2. Model training on Kaggle datasets
3. Custom dataset creation and testing
4. Integration of detection, tracking, and alert modules
5. Offline testing with pre-recorded videos
6. Documentation and final project presentation

### Location

**Bangladesh Office:** Hi Tech Park, Silicon Tower, Level #7, Suit #A, Rajshahi  
**Email:** atctechltdbd@gmail.com

---

## Chapter 3: Day-wise Activities & Learning Experience

### Week 1: Fundamentals of Python, ML, and Kaggle Projects

**Day 1:** Orientation, environment setup, project overview.  
**Day 2:** Python basics and object-oriented programming.  
**Day 3:** NumPy & Pandas for data handling and preprocessing.  
**Day 4:** Introduction to machine learning concepts.  
**Day 5:** Kaggle Digit Recognition Project implementation.  
**Day 6:** Testing model on custom Handwritten Digit Dataset.  
**Day 7:** Review, reflection, and preparation for deep learning.

### Week 2: Deep Learning, Vehicle Detection, and Speed Monitoring

**Day 8:** Introduction to CNNs and PyTorch; preprocessing techniques.  
**Day 9:** Kaggle Animal Classification Project.  
**Day 10:** Custom Animal Dataset implementation using PyTorch.  
**Day 11:** Vehicle detection and counting on single-lane road.  
**Day 12:** Multi-lane vehicle detection and tracking.  
**Day 13:** Speed calculation and offline overspeed alerts on recorded videos.  
**Day 14:** Final integration and testing of all modules.

### Week 3: Model Optimization & Testing

- Fine-tuned detection thresholds.
- Validated speed calculation against recorded video data.
- Optimized tracking for multiple vehicle types.

### Week 4: Project Submission

- Integrated detection, tracking, and speed modules into a **complete system**.
- Conducted extensive testing on recorded videos for single and multi-lane roads.
- Generated **vehicle counts, average speeds, and overspeed alerts**.
- Prepared project documentation and **demonstration presentation** for mentors.

---

## Chapter 4: Technical Knowledge Acquired

- **Python Programming:** loops, functions, classes, and object-oriented programming
- **Data Handling:** NumPy arrays, Pandas dataframes, dataset preprocessing
- **Machine Learning:** supervised learning, training/testing, accuracy metrics
- **Deep Learning:** CNNs, PyTorch, model training, custom dataset handling
- **Computer Vision:** YOLO12s, OpenCV for object detection and tracking
- **Project Implementation:** integrating multiple modules for a real-world AI system

---

## Chapter 5: Reflection and Conclusion

The industrial attachment at ATC Tech Ltd. was a transformative experience. Collaborating with skilled professionals allowed us to **apply theoretical knowledge to practical AI projects**.

We became proficient in Python, NumPy, Pandas, PyTorch, OpenCV, and YOLO12s, while implementing a **real-time vehicle detection and speed monitoring system** on recorded videos. The project taught us challenges in dataset creation, model training, offline testing, and alert generation.

The attachment also enhanced our **professional skills**, including teamwork, problem-solving, communication, and project documentation. Mentorship from ATC Tech Ltd.’s engineers provided insight into **industry workflows, AI application, and project planning**.

Overall, this experience strengthened our **technical expertise and professional confidence**, preparing us for future careers in AI, machine learning, and software development.

---

## References

- [Kaggle Digit Recognition Dataset](http://kaggle.com/code/nabilaferdous/digit)
- [Kaggle Animal Classification Dataset](https://www.kaggle.com/code/nabilaferdous/animal-10)
- [HandWrittenDigitDataset](https://www.kaggle.com/datasets/nabilaferdous/testdataset)

-

## 🧑‍💻 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/vehicle-speed-detection.git
cd vehicle-speed-detection
```

### 2️⃣ Create and Activate a Virtual Environment

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**Mac/Linux:**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

> If you don’t have a `requirements.txt`, you can manually install:

```bash
pip install opencv-python torch torchvision numpy pandas matplotlib
```

### 4️⃣ Run the Main Script

Run the Python file that starts detection and speed measurement:

```bash
python main.py
```

If your file is named differently (e.g., `vehicle_speed_detection.py`), use:

```bash
python vehicle_speed_detection.py
```

### 5️⃣ Optional: Test with a Sample Video

You can place a video file (e.g., `traffic.mp4`) in the same folder and run:

```bash
python main.py --video traffic.mp4
```

---

## 📂 Folder Structure

```
vehicle-speed-detection/
│
├── main.py
├── yolov5/               # YOLO model files
├── data/                 # Datasets (if any)
├── utils/                # Helper functions
├── requirements.txt
└── README.md
```

## 🏁 Results

- Model accuracy for handwritten digits: **Above 50%**
- Real-time vehicle detection achieved stable **FPS and accuracy**
- Successful alert generation for overspeeding vehicles with variable speed limits

---

## 🧠 Learning Outcomes

- Strengthened understanding of **Python**, **Machine Learning**, and **Computer Vision**
- Learned **data preprocessing**, **model training**, and **real-time inference**
- Developed team collaboration and technical documentation skills

---

## 📍 Acknowledgment

We sincerely thank **ATC Tech Ltd** for providing mentorship, resources, and industry exposure that allowed us to explore practical AI-driven projects.

---

## 🧑‍🏫 How to Contribute

Feel free to fork this repository, open issues, or submit pull requests for improvements.

---
