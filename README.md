# Chess Detection and PNG Conversion

This project is a digital image processing and machine learning application designed to detect a chessboard from a video input and convert chess games into PNG chess notation.

## Features

- **Chessboard Detection**: Identifies the chessboard and pieces from video frames using advanced image processing techniques.
- **Move Recognition**: Tracks and recognizes moves made during the game.
- **PNG Conversion**: Converts recognized chess moves into Portable Game Notation (PGN).
- **Machine Learning**: Leverages trained models to enhance detection accuracy.

## Technologies Used

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - OpenCV: For image and video processing.
  - NumPy: For numerical computations.
  - TensorFlow/Keras: For machine learning model development.
  - matplotlib: For visualizing results and debugging.
- **Jupyter Notebook**: Interactive development environment for code and results presentation.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/CP-RektMart/Cu-ChessGame-to-PGN-SunnySleepy.git
   cd Cu-ChessGame-to-PGN-SunnySleepy
   ```
2. **Setup Environment**: Ensure you have Python 3.8 or higher and the necessary dependencies installed.

## Usage

1. **Run the Notebook**: Open the `Digital_Imaging_Final_Project.ipynb` file in Jupyter Notebook or JupyterLab and execute the cells step by step.

2. **Input Video**: Place your chess video files in the `resources/example_videos/` directory.

3. **Generate PGN**: The notebook will process the video, detect moves, and output the corresponding PGN file.

## Results

This project demonstrates successful detection and tracking of chessboard and pieces. It outputs accurate PGN files for analyzed games. The detailed results are showcased in the Jupyter notebook.

## Future Work

- Improve piece classification accuracy with more training data.
- Add support for real-time chess move detection.
- Enhance performance for non-standard chessboard configurations.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

