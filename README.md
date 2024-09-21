# PennAIR-software-challenge

This project implements a shape detection algorithm using OpenCV. It includes detection in both static images and dynamic videos, along with adaptations for various backgrounds.

## Instructions to Run the Code

### Prerequisites
- Python 3.x
- OpenCV
- NumPy

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shape-detection.git
   cd shape-detection
   ```

2. Install the required packages:
   ```bash
   pip install opencv-python numpy
   ```

### Usage
- **Static Image Shape Detection**
   ```bash
   python static_shape_detection.py
   ```
   Uses `PennAir 2024 App Static.png`.

- **Dynamic Video Shape Detection**
   ```bash
   python dynamic_shape_detection.py
   ```
   Uses `PennAir 2024 App Dynamic.mp4`.

- **Background Agnostic Detection**
   ```bash
   python background_agnostic_detection.py
   ```
   Uses `PennAir 2024 App Dynamic Hard.mp4`.

## Overview of Parts
1. **Part 1**: Detects shapes in a static image, traces outlines, and marks centers.
2. **Part 2**: Applies the detection algorithm to video frames.
3. **Part 3**: Adapts detection for varying backgrounds.
4. **Part 4 (Optional)**: Extend the algorithm for 3D detection.

## Videos
- **Part 1**: [Static Image Detection Video]
- **Part 2**: [Dynamic Video Detection Video]
- **Part 3**: [Background Agnostic Detection Video]

## License
This project is licensed under the MIT License.
```

