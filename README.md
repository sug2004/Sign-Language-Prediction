# Sign Language Prediction

This repository contains a machine learning project for predicting sign language gestures using deep learning techniques. The system processes video frames and classifies hand gestures into corresponding sign language symbols.

## Features

- Real-time sign language recognition
- Video frame processing with OpenCV
- Deep learning model training using TensorFlow
- Gesture prediction with high accuracy

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sug2004/Sign-Language-Prediction.git
   cd Sign-Language-Prediction
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```



## Usage

1. **Run the application:**

   ```bash
   python main.py
   ```

2. **Interact with the system:**

   - Ensure your webcam is enabled.
   - Perform sign language gestures in front of the camera.
   - See real-time predictions on the screen.

## Project Structure

```
Sign-Language-Prediction/
│
├── data/                 # Training and test data
├── models/               # Saved models
├── src/                  # Source code
│   ├── dataset.py        # Data loading and preprocessing
│   ├── model.py          # Model definition
│   ├── train.py          # Model training script
│   └── predict.py        # Real-time prediction
├── main.py               # Main application entry point
├── requirements.txt      # Required packages
└── README.md             # Project documentation
```

## Example Output

Below is an example of the system detecting and analyzing hand and facial landmarks:
![image](https://github.com/user-attachments/assets/fd7cb774-dc56-4af1-a6b4-5504353b6460)



## Model Training

1. **Prepare the dataset:** Place your dataset in the `data/` directory.
2. **Train the model:**
   ```bash
   python src/train.py
   ```
3. **Save and evaluate the model:** The trained model will be saved in the `models/` directory.

## Technologies Used

- Python
- TensorFlow
- OpenCV
- NumPy

## Contributing

Contributions are welcome! Please create a fork, make changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- OpenAI for AI research inspiration.
- Open-source community for valuable libraries and tools.

---

Thank you for checking out the Sign Language Prediction project! We hope it serves as a useful tool and learning resource.

