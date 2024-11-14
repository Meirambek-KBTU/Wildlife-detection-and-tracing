# Wildlife Detection and Tracking

This project focuses on detecting and tracking wildlife using computer vision techniques, specifically utilizing YOLOv8 for object detection and DeepSort for tracking.

## Overview
Wildlife monitoring and tracking are essential for understanding animal behavior, conserving ecosystems, and preventing human-animal conflicts. This project provides a framework for detecting animals in video streams or recorded footage and tracking their movements in real-time.

## Features
- **Real-time animal detection** using YOLOv8.
- **Object tracking** with DeepSort algorithm to maintain continuous tracking of detected animals.
- **Customizable** for various types of wildlife by retraining the YOLOv8 model with specific datasets.
- **Output visualization** showing bounding boxes, tracking IDs, and paths of detected animals.

## Technologies Used
- **Python**: Main programming language.
- **YOLOv8 (Ultralytics)**: State-of-the-art object detection model.
- **DeepSort**: Algorithm for tracking detected objects across frames.
- **OpenCV**: For handling video input/output and visualizations.
- **NumPy & Pandas**: For data manipulation.
- **Matplotlib**: For plotting and analysis.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/Wildlife-detection-and-tracing.git
   cd Wildlife-detection-and-tracing
   ```
2. **Create a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Prepare your data**: Place the video files in the `data/` directory or modify the code to read from a different source.
2. **Run the detection and tracking script**:
   ```bash
   python main.py --input data/video.mp4 --output results/output_video.mp4
   ```
3. **View the results**: The processed video will be saved in the `results/` directory.

## Customization
- **Training YOLOv8**:
  - To train YOLOv8 on your custom dataset, follow the Ultralytics [YOLOv8 training guide](https://docs.ultralytics.com/yolov8/).
- **Adjusting DeepSort parameters**:
  - Modify the `deepsort/configs/deep_sort.yaml` to fine-tune tracking performance.

## Example Output
![Wildlife Detection and Tracking Demo](link-to-screenshot-or-gif)

## Future Work
- Integrate more advanced tracking algorithms.
- Enhance detection capabilities for specific species.
- Implement real-time streaming support.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For more information, reach out at [your-email@example.com] or visit [your LinkedIn profile](https://www.linkedin.com/in/username/).

