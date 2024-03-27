

# Heart Disease Prediction

This project aims to predict the likelihood of heart disease in individuals based on certain medical attributes using machine learning techniques. It utilizes the Heart Disease dataset, which contains various features such as chest pain type, maximum heart rate achieved, and the slope of the peak exercise ST segment.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python installed (preferably Python 3.x) along with the necessary libraries specified in the `requirements.txt` file. You can install them using pip:

```
pip install -r requirements.txt
```

3. Download the Heart Disease dataset (`heart.csv`) and place it in the project directory.

4. Run the `heart_disease_prediction.py` script to train the machine learning models and perform predictions.

## Project Structure

The project directory contains the following files:

- `heart_disease_prediction.py`: The main Python script that loads the dataset, preprocesses the data, trains machine learning models, and performs predictions.
- `heart.csv`: The dataset file containing medical attributes and target labels.
- `README.md`: This README file providing information about the project and instructions for running it.
- `requirements.txt`: A text file listing the required Python libraries and their versions.

## Dependencies

This project requires the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these dependencies using the provided `requirements.txt` file.

## Usage

After setting up the project, you can run the `heart_disease_prediction.py` script to train the machine learning models and perform predictions. The script includes:

- Data loading and preprocessing.
- Exploratory data analysis (EDA) including visualization of data distribution and correlation analysis.
- Training of the K Nearest Neighbors (KNN) Classifier.
- Evaluation of the classifier using cross-validation.
- Prediction of heart disease likelihood for test cases.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Heart Disease dataset used in this project is sourced from the UCI Machine Learning Repository.
- Special thanks to the scikit-learn library for providing machine learning tools and algorithms.


