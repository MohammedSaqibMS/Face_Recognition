# Face Recognition Using Deep Learning 📸🤖

Welcome to the **Face Recognition Project**, a comprehensive implementation of a face recognition system using deep learning techniques. This project demonstrates the application of neural networks for facial feature encoding and recognition.

## 🚀 Overview
This project provides an end-to-end implementation of a face recognition system:
- **Face Verification**: Determines if two images are of the same person.
- **Face Recognition**: Identifies a person from a database of encodings.

Built with TensorFlow, Keras, and Python, it utilizes the **Inception V2** architecture and incorporates the **Triplet Loss Function** for robust feature extraction and comparison.

## Features ✨
- **Triplet Loss Implementation**: Utilizes a robust loss function to optimize face embeddings.
- **Inception Model**: Leverages a pre-trained deep learning model for accurate face encoding.
- **Face Database Matching**: Compares face encodings to a database to identify individuals.
- **Real-World Applications**: Supports scenarios like office security and personalized systems.

## Requirements 🛠️
To run this project, you need:
- Python 3.8+
- TensorFlow and Keras
- OpenCV
- NumPy and Pandas
- Jupyter Notebook (for running and testing code)

Install the dependencies by running:
```bash
pip install -r requirements.txt
```

## Getting Started 🚀
1. Clone this repository:
   ```bash
   git clone https://github.com/MohammedSaqibMS/Face_Recognition.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Face_Recognition
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and execute the provided notebooks to train and test the model.

## Key Components 🧠
- **Triplet Loss Function**:
  Implements the triplet loss function to learn robust face embeddings.
- **Face Database**:
  Stores face encodings and associated names for recognition tasks.
- **Face Embeddings**:
  Each face is encoded into a 128-dimensional vector. The Euclidean distance between vectors determines similarity.
- **`who_is_it` Function**:
  Identifies individuals by comparing input image encodings with the database.

## Example Usage 📖
```python
# Identify a person in an image
min_dist, identity = who_is_it("images/camera_0.jpg", database, FRmodel)
print(f"Identified: {identity} (Distance: {min_dist})")
```

## Acknowledgments 🙌
This project is based on the techniques and methods taught in the [Deep Learning Specialization](https://www.deeplearning.ai/courses/deep-learning-specialization/) by Andrew Ng. Special thanks to [DeepLearning.AI](https://www.deeplearning.ai/) for their exceptional courses and resources.

## Contributions 🤝
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request.

## License 📜
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
