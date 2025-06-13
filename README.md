# Deep Learning - Based Temporal Analysis of Badminton Gameplay

This project uses deep learning techniques to analyze badminton match videos by detecting player positions, movements, court key points, and classifying shots over time. The goal is to extract temporal dynamics of gameplay for performance analysis and tactical insights.

## Features

- Detection of player positions and movements on court
- Identification of court key points for spatial reference
- Shot classification for each rally
- Extraction of rally data and conversion to CSV format
- Evaluation using confusion matrix for shot classification accuracy

## Technologies Used

- Python for video processing and data extraction
- Deep learning frameworks (e.g., TensorFlow, PyTorch)
- OpenCV for computer vision tasks
- Custom dataset curated from multiple badminton match videos

## How to Run

1. Clone the repository.
2. Install required Python packages: `pip install -r requirements.txt`
3. Prepare the video dataset.
4. Run the detection and classification scripts.
5. Export extracted rally and shot data to CSV files.
6. Use evaluation scripts to generate confusion matrices.

## License

This project is licensed under the MIT License.
