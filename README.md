# FlameGuard: AI-Powered Fire Detection

## 🚀 Overview
FlameGuard is an AI-powered fire detection system that leverages machine learning and image processing techniques to detect fire in real time. The system utilizes Haar cascade classifiers trained specifically for fire detection and incorporates an alarm system for immediate alerts. This project aims to enhance fire safety by providing an early warning mechanism to prevent potential disasters.

## 🌟 Features
- **Real-time Fire Detection**: Uses trained Haar cascade classifiers to detect fire in video streams.
- **Audio Alert System**: Triggers an alarm sound when fire is detected.
- **Efficient and Lightweight**: Optimized for real-time processing on low-resource devices.
- **Customizable Sensitivity**: Adjustable parameters for fine-tuning fire detection.
- **Scalable**: Can be integrated into security systems, smart home applications, and industrial safety solutions.

## 🛠️ Technologies Used
- **Python**: Core programming language.
- **OpenCV**: For image processing and real-time detection.
- **Haar Cascade Classifier**: Trained model for fire detection.
- **NumPy**: For numerical operations.
- **Multimedia Libraries**: Used for playing alarm sounds when fire is detected.

## 📁 Project Structure
```
FlameGuard/
├── models/
│   ├── fire_detection_cascade_model.xml  # Trained fire detection model
│   ├── cascade.xml                        # Additional cascade classifier
├── assets/
│   ├── Alarm Sound.mp3                    # Audio file for fire alarm
├── src/
│   ├── fire_detection.py                   # Main detection script
│   ├── utils.py                            # Utility functions
├── README.md                               # Project documentation
└── requirements.txt                        # List of dependencies
```

## 🔧 Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kalpesh-S-Mahajan/firedetection.git
   cd FlameGuard
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the detection script:**
   ```bash
   python src/fire_detection.py
   ```

## 🎯 How It Works
1. The program captures video frames using OpenCV.
2. The Haar cascade classifier scans the frames to detect fire patterns.
3. If fire is detected, an alert sound is played.
4. The system continuously processes frames for real-time detection.

## ⚠️ Limitations
- The model may produce false positives in certain lighting conditions.
- Performance may vary based on the quality of input video.

## 🔥 Future Improvements
- **Deep Learning Integration**: Enhance accuracy using CNN models.
- **IoT Integration**: Connect with smart home devices for automated safety measures.
- **Cloud Alert System**: Implement cloud-based notifications for remote alerts.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📩 Contact
For inquiries, please reach out via [kalpeshmahajan325@gmail.com] or open an issue on GitHub.

---
**Stay safe with FlameGuard! 🚨🔥**

