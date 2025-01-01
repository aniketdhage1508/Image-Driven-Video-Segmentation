# Vision Matrix: Image-Driven Video Segmentation for Surveillance

## Project Overview
This project leverages **YOLOv10** and **OpenCV** for efficient face detection, recognition, and video segmentation. The system identifies specific individuals in video footage based on an uploaded reference image and segments relevant clips for streamlined surveillance and analysis. Designed for real-time processing, it offers a powerful solution for law enforcement and public safety.

## Key Features
- **Real-Time Detection and Segmentation**: Fast and accurate face detection using YOLOv10.
- **Image-Driven Person Recognition**: Matches faces in video frames with a provided image for targeted analysis.
- **Automated Video Clipping**: Outputs segmented videos focusing only on frames containing the identified person.
- **User-Friendly Interface**: Built with Streamlit for easy interaction.

---

## System Architecture
The system integrates:
1. **YOLOv10** for face detection.
2. **OpenCV** for frame extraction, face recognition, and video processing.
3. **Streamlit** for user interface and interaction.

![System Architecture](path/to/system_architecture_image.png)

---

## Workflow
1. **Input**: Users upload a video file and a reference face image.
2. **Processing**:
   - YOLOv10 detects faces in video frames.
   - OpenCV compares detected faces with the reference image.
   - Frames with matches are clipped and compiled into a new video.
3. **Output**: A downloadable video containing only the relevant segments.

![Process Flow](path/to/process_flow_image.png)

---

## Installation

### Prerequisites
- Python 3.8+
- GPU with CUDA support for optimal performance.
- Libraries: OpenCV, Streamlit, face_recognition.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/vision-matrix.git
   cd vision-matrix
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Demo
### Input
Upload:
- **A video file** (e.g., `.mp4`, `.avi`).
- **A reference image** (e.g., `.jpg`, `.png`).

### Output
Download the processed video with highlighted segments.

![Demo Input-Output](path/to/demo_input_output_image.png)

---

## Results
### Training Curves
![Training Curves](path/to/training_curves_image.png)

### Original vs Processed Video
![Original Video](path/to/original_video_image.png)
![Segmented Video](path/to/segmented_video_image.png)

---

## Technologies Used
- **YOLOv10**: High-performance face detection.
- **OpenCV**: Frame processing and face recognition.
- **Streamlit**: Interactive web interface.

---

## Future Scope
- **Enhanced Detection**: Improve handling of occluded or low-quality faces.
- **Real-Time Processing**: Integrate GPU acceleration for faster frame analysis.
- **Advanced Features**: Add multi-face detection and tracking.

---

## Contribution
Contributions are welcome! Please submit a pull request or open an issue for discussion.

---

## Acknowledgments
This project is part of the AIIC Project Competition at **VishwaCon**, developed by the **Vision Matrix** team.

## License
This project is licensed under the [MIT License](LICENSE).

---

Thank you for using Vision Matrix! For any queries, feel free to contact us.


### Notes:
- Replace `path/to/...` placeholders with the actual paths to the images (training curves, system architecture, process flow, demo input-output) in your repository.
- Add a `requirements.txt` file with the necessary Python libraries.
- Update the contact and license information as per your preferences.
