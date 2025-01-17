# Face Recognition Using Deep Learning 📸🤖

Welcome to the **Face Recognition Project**, a comprehensive implementation of a face recognition system using deep learning techniques. This project demonstrates the application of neural networks for facial feature encoding and recognition.

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
   git clone https://github.com/your-username/face-recognition-deep-learning.git
   ```
2. Navigate to the project directory:
   ```bash
   cd face-recognition-deep-learning
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

---

Happy Coding! 😊

