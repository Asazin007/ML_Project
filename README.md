# Student Performance Predictor
A Machine Learning project in Python that predicts student performance based on various parameters. This project showcases proficiency in machine learning algorithms, data analysis, and the application of ML techniques to real-world problems. It utilizes a dataset containing information about students' gender, race/ethnicity, parental level of education, lunch type, test preparation course completion, and scores in math, reading, and writing.
### URL: 
https://mathsscore.azurewebsites.net/predictdata

## Features

- Predicts student performance using machine learning.
- Demonstrates modular programming for a well-structured codebase.
- Utilizes various machine learning algorithms, including AdaBoost Regressor, Random Forests, Gradient Boosting, KNeighbors Regressor, etc.
- Performs hyperparameter tuning to optimize model performance.
- Creates a prediction pipeline using a Flask web application.
- Deploys the project to the Azure Cloud using a CI/CD pipeline.
- Dataset included for analysis.

## Screenshot 
![On Azure Server](https://github.com/Asazin007/ML_project/blob/main/Screenshot/Screenshot%20(336).png)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Asazin007/Maths-Score-Predicter.git
   cd gh repo clone Asazin007/Maths-Score-Predicter.git
   ```

2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask web application:

   ```bash
   python application.py
   ```

2. Open a web browser and go to `http://localhost:5000/predictdata` to access the Student Performance Predictor.

3. Enter the required parameters from the dataset, and the model will predict the student's performance.

## Dataset

The dataset provided in this project includes the following columns:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them.
4. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
