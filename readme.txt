# Face Detection Project

This project provides functionality for face detection using Python. It leverages several libraries and tools to detect faces in images, videos, and real-time via webcam.

## Features
- Face detection in images
- Face detection in videos
- Real-time face detection via webcam

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- Pillow (`PIL`)
- RetinaFace
- Transformers
- tqdm

### Installation

1. **Clone the Repository:**

```bash
git clone https://github.com/yourusername/facedetectionproject.git
```

2. **Install Dependencies:**

```bash
pip install -r requirements.txt
```

## Usage

1. **Face Detection in Images**  
   To detect faces in an image, run the following command:

```bash
python detect_faces_image.py --image path/to/your/image.jpg
```

2. **Face Detection in Videos**  
   To detect faces in a video file, run the following command:

```bash
python detect_faces_video.py --video path/to/your/video.mp4
```

3. **Real-time Face Detection via Webcam**  
   To detect faces in real-time using your webcam, run the following command:

```bash
python detect_faces_webcam.py
```

## Credits

- **OpenCV**: For image and video processing.
- **Pillow**: For handling image files.
- **RetinaFace**: For high-quality face detection.
- **Transformers**: For pre-trained deep learning models (optional).
- **tqdm**: For progress bars.

---

### Project Made By Prashant Kumbhare ™️
