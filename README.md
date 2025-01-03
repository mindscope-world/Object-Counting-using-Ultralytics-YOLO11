# Object Counting with YOLO

This project leverages YOLO (You Only Look Once) for object detection and counting in video files. A user-friendly interface built with Streamlit enables easy video processing, region-based counting, and visualization of results.

## Features

- **File Upload**: Supports video uploads in formats like MP4, AVI, and MOV.
- **Region Selection**: Enables selection of regions (Line, Rectangle, or Polygon) for object counting.
- **Real-Time Processing**: Visualizes the processing progress as frames are analyzed.
- **Output Playback**: Displays the processed video within the app.
- **Downloadable Results**: Allows users to download the output video after processing.

## Requirements

Ensure the following dependencies are installed:

- Python 3.7+
- OpenCV
- Streamlit
- Ultranytics Solutions library

Install the required packages using:
```bash
pip install opencv-python-headless streamlit ultralytics
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository.git
   cd your-repository
   ```

2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

3. Upload a video file, choose the region type, and start processing.

## Usage

1. **Upload a Video**: Use the sidebar to upload your video file.
2. **Select Region Type**: Choose the region type for object counting:
   - Line
   - Rectangle
   - Polygon
3. **View Progress**: The app shows the real-time progress of video processing.
4. **Playback and Download**: Once processed, the output video can be viewed or downloaded.

## Project Structure

- **`app.py`**: Main Streamlit application.
- **`requirements.txt`**: List of dependencies.
- **`outputs/`**: Directory for storing processed videos (auto-generated).

## Example

1. Upload a sample video file (e.g., `sample2.mp4`).
2. Choose "Rectangle" as the region type.
3. View the processed video directly in the app or download it for offline use.

## Contributions

Contributions are welcome! Feel free to submit a pull request or open an issue to improve the project.

## License

This project is licensed under the MIT License.

## Acknowledgments

- **YOLO Model**: For robust object detection.
- **Streamlit**: For making interactive web apps easy to build.
- **OpenCV**: For video processing and visualization.

