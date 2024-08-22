
# Identification of Cyberbullying in Social Media with Multimodal Analysis

This project focuses on identifying instances of cyberbullying on social media platforms using multimodal analysis, combining text, images, and other relevant data types. The approach leverages advanced machine learning models to detect and analyze abusive behavior, helping to make online spaces safer.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Team](#team)
- [Acknowledgements](#acknowledgements)

## Project Overview

Cyberbullying is a pervasive issue on social media platforms, with harmful effects on victims. This project aims to address this challenge by developing a system that can automatically identify cyberbullying content through multimodal analysis, considering both textual and visual content.

### Objectives

- Detect and identify cyberbullying incidents in text, images, audio or a combination of these all.
- Implement multimodal machine learning models to enhance detection accuracy.
- Provide insights into the types of content that are commonly associated with cyberbullying.
- Offer a user-friendly interface for visualization and analysis.

## Features

- **Text Analysis:** Detects abusive language and context using NLP techniques.
- **Image Analysis:** Identifies harmful or offensive images using CNN-based models.
- **Audio Analysis:** Detects The harmful And Abusive Word-sounds using LSTM technology
- **Multimodal Analysis:** Combines text and image data for a comprehensive analysis.
- **Real-time Monitoring:** Continuously monitors social media streams for cyberbullying.
- **Visualization Dashboard:** Displays analysis results with intuitive graphs and statistics.

## Technologies Used

- **Programming Languages:** Python
- **Data Management:** Local Memory
- **Data Integration and Transformation:** Pandas and Numpy
- **Data Visualization:** Matplotlib library
- **Machine Learning:** TenserFlow, Keras
- **Model Deployment:** NLTK, TenserFlow, Keras.

## Project Structure

```
├── data/               # Datasets used for training and testing
├── notebooks/          # Jupyter notebooks for exploratory data analysis and model development
├── src/                # Source code for the project
│   ├── data_processing/ 
│   ├── model/          
│   ├── utils/          
├── tests/              # Unit tests for the project
├── results/            # Results from experiments and analysis
├── docs/               # Documentation and project reports
├── .gitignore          # Git ignore file
├── README.md           # Project README file
└── requirements.txt    # Python dependencies
```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cyberbullying-identification.git
    ```

2. Navigate to the project directory:
    ```bash
    cd cyberbullying-identification
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Preprocess the data:
    ```bash
    python src/data_processing/preprocess_data.py
    ```

2. Train the model:
    ```bash
    python src/model/train_model.py
    ```

3. Run the analysis on new data:
    ```bash
    python src/model/run_analysis.py --input <input_data_path>
    ```

4. Visualize the results using the dashboard (details in the `docs` folder).

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

Please refer to our [CONTRIBUTING.md](docs/CONTRIBUTING.md) file for more details.

## Team

- **Project Guide:** *Dr. Rajat Kumar Behra*
- **Project Leader:** *Raunit Raj*
- **Programmer:** *Raunit Raj*
- **Data Research:** *Raunit Raj*
- **Data Analyst:** *Raunit Raj , Seema Kumari and Taniya De*
- **Data Engineering and Analysis:** *Seema Kumari and Taniya De*
- **Report and Miscellaneous:** *Seema Kumari and Taniya De*


## Acknowledgements

We would like to thank Dr. Rajat Kumar Behera Sir for providing the necessary datasets and guidence for this project.

---
