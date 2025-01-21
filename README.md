# Differential Privacy on Electronic Health Records (EHR) using RNN & ANN

## Overview

This project demonstrates the application of **Differential Privacy (DP)** on **Electronic Health Records (EHR)** using **Recurrent Neural Networks (RNN)** and **Artificial Neural Networks (ANN)**. The goal is to enhance the privacy of sensitive healthcare data while maintaining high prediction accuracy.

We implemented DP by adding **Gaussian noise** to the EHR data, and then trained **RNN** and **ANN** models to classify the data. We found that our DP-enabled models outperformed traditional machine learning models, even with the added noise, proving the efficacy of differential privacy in protecting patient data without sacrificing prediction performance.

### Key Highlights:
- **Differential Privacy Implementation**: Utilized Gaussian noise for privacy protection.
- **RNN & ANN Models**: Used advanced deep learning techniques to classify patient data.
- **Superior Accuracy**: Achieved better classification accuracy than traditional machine learning models even with noise.
- **SGD Optimizer**: Optimized our models using Stochastic Gradient Descent (SGD).
- **Privacy-Preserving Healthcare Modeling**: Focused on privacy protection while maintaining data utility.

## Getting Started

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.x
- Required Python libraries:
  - **TensorFlow**: For building and training deep learning models.
  - **NumPy**: For numerical operations.
  - **Pandas**: For data manipulation.
  - **Matplotlib**: For visualizations.
  - **Scikit-learn**: For traditional machine learning models.

You can install the required libraries using `pip`:

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn
```

### Dataset

The project uses ["MIMIC-III Electronic Health Records (EHR) data"](https://physionet.org/content/mimiciii/1.4/) , which contains patient details such as age, gender, medical conditions, and health outcomes. For the purpose of this demonstration, you may use a synthetic dataset or your own EHR data with necessary anonymization. Ensure that the data is formatted correctly for the models.

## Project Structure

```
data/: Contains the dataset and any pre-processed data.
models/: Contains the RNN and ANN model definitions.
notebooks/: Jupyter Notebooks for data exploration, preprocessing, and results.
scripts/: Python scripts for training, testing, and evaluating models.
results/: Stores output files like model weights and evaluation metrics.
README.md: This file.
```

## Results

In our study, we observed that:

- The RNN and ANN models, after applying Gaussian noise for differential privacy, outperformed both advance and traditional machine learning classifiers.
- The models successfully maintained privacy while ensuring high predictive accuracy for patient outcomes.

## Future Work

- **Model Explainability**: Implement techniques to enhance model interpretability to make it easier for healthcare professionals to trust the predictions.
- **Longitudinal Analysis**: Incorporate time-series analysis to handle changes in patient data over time.
- **Real-World Testing**: Apply this methodology to real-world EHR data and assess the scalability of the solution in a clinical setting.

## References

- Differential Privacy in Healthcare
- RNN & ANN Models
- Differential Privacy

## Contributing

Feel free to fork this repository, submit issues, or create pull requests if you have suggestions for improvements or new features.

## License

GNU AFFERO GENERAL PUBLIC LICENSE
                       Version 3, 19 November 2007

 Copyright (C) 2025  Rudra Prasanna Mishra

 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU Affero General Public License as published
 by the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.

 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU Affero General Public License for more details.

 You should have received a copy of the GNU Affero General Public License
 along with this program.  If not, see <https://www.gnu.org/licenses/>.

## Acknowledgements

- The research paper ["Differential Privacy Implementation on Electronic Health Records using Deep Learning Models"](https://journal.esrgroups.org/jes/article/view/4861/3560) published in the Journal of Engineering Sciences.
- The use of open-source tools like TensorFlow, NumPy, and Scikit-learn made this project possible.
- Keras Documentation: [Keras](https://keras.io/)
- TensorFlow Documentation: [TensorFlow](https://www.tensorflow.org/)

## Contact

For questions, suggestions, or collaborations, feel free to reach out to:

**Rudra Mishra:** ["Gmail"](rudramishrassd.2635@gmail.com) & ["Linkedin"](https://www.linkedin.com/in/rudra-mishra/)
```

This README.md file provides a comprehensive overview of your project, including its purpose, setup instructions, usage guidelines, and future directions. It's formatted in Markdown, making it easily readable on GitHub and other platforms that support Markdown rendering.
