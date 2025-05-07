👁️ Real-Time Face Detection using OpenCV

This project implements a real-time face detection system using Python and OpenCV. The application captures video input from a webcam, detects human faces in the frame using Haar Cascade Classifiers, and displays the detected faces with bounding boxes in real time.

📁 Project Structure

* `detection.ipynb`: Main Jupyter notebook containing the code for real-time face detection.
* (Optional) `haarcascade_frontalface_default.xml`: Haar Cascade model for face detection (downloaded automatically in code or placed in the working directory).

🔍 Features

* Uses OpenCV's Haar Cascade Classifier for robust face detection.
* Captures and processes video stream in real-time from your system’s webcam.
* Displays the detected faces with bounding boxes.
* Option to exit the video stream using the **'q'** key.

🛠️ Requirements

Install the following Python packages:

```bash
pip install opencv-python
```

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/gurjeet3010/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. Open the notebook `detection.ipynb` and run all the cells sequentially.

   * Ensure your webcam is accessible.
   * The notebook will open a video window showing detected faces.

📸 Output Preview

Detected faces will be shown with green bounding boxes around them in the video stream.

📌 Notes

* Make sure you allow access to the webcam if prompted.
* Tested on Python 3.x and OpenCV 4.x.

🧠 Future Enhancements

* Integrate with deep learning models (e.g., DNN, MTCNN) for better accuracy.
* Add face recognition functionality.
* Create a standalone GUI or web app interface.
