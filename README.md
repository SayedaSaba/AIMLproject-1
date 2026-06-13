Face Recognition Attendance System

Overview:

The Face Recognition Attendance System is a computer vision-based application developed using Python and OpenCV. The system captures face images through an IP Webcam, detects faces using a Haar Cascade Classifier, and recognizes registered users using a trained deep learning model. Once a user is identified, attendance is recorded automatically, reducing the need for manual attendance management.

Features:

- Real-time face detection and recognition
- Automatic attendance marking
- IP Webcam integration for image capture
- Face image collection and preprocessing
- Deep learning-based face recognition
- User-friendly and efficient attendance process

Technologies Used:

- Python
- OpenCV
- NumPy
- Keras
- Haar Cascade Classifier

Usage:

1. Run "collect_data.py" to collect face images.
2. Train the model using the collected dataset.
3. Run "recognize.py" to start the attendance system.

Privacy:

To protect privacy, the original training dataset containing personal face images is not included in this repository.

Future Enhancements:

- Multi-user face recognition support
- Attendance storage using a database
- Graphical User Interface (GUI)
- Cloud-based attendance management
- Improved recognition accuracy and performance
- Integration with college or office attendance systems
