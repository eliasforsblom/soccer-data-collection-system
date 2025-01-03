# Research Summary

## 1. Tools and Libraries
- **OpenCV**:
  - Feature: Frame extraction and preprocessing.
  - Link: [OpenCV Documentation](https://docs.opencv.org/)
  - Action: Install using `pip install opencv-python`.

- **FFmpeg**:
  - Feature: Batch video processing and frame extraction.
  - Link: [FFmpeg Documentation](https://ffmpeg.org/)
  - Action: Install and test with `ffmpeg -i input.mp4 -vf fps=1 frame_%04d.png`.

- **YOLOv Models**:
  - Feature: Real-time object detection for soccer data.
  - Link: [Ultralytics Documentation](https://docs.ultralytics.com/)
  - Action: Install using `pip install ultralytics`.

- **Annotation Tools**:
  - Tools: CVAT, Roboflow, or LabelImg will be used for creating bounding box annotations for the dataset.
  - Link: [CVAT](https://opencv.github.io/cvat/), [Roboflow](https://roboflow.com/), [LabelImg](https://github.com/heartexlabs/labelImg).

## 2. Data Sources
- **Broadcast Soccer Data**:
  - Data will be gathered from TV channels that are recorded manually.
- **Annotation**:
  - Data will be annotated manually using tools like CVAT, Roboflow, or LabelImg.

## 3. Hardware Assessment
- **Current Setup**:
  - **GPU**: NVIDIA GeForce RTX 3070
  - **CPU**: Intel Core i5-12400F 2.50GHz
  - **RAM**: 16GB
- **Next Steps**:
  - Use the current local setup for initial fine-tuning.
  - Evaluate the feasibility of cloud options if additional resources are needed.

## 4. Next Steps
1. Set up tools and libraries.
2. Record and annotate datasets.
3. Test YOLOv model on initial soccer videos.
