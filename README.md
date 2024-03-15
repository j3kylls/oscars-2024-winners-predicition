# Oscars 2024 Winners Prediction

![Oscars 2024](https://img.shields.io/badge/Oscars-2024-red)
![Python](https://img.shields.io/badge/Made%20with-Python-blue)

Welcome to the Oscars 2024 Winners Prediction project repository! In this project, we analyze the similarity patterns between prestigious awards such as SAG and Golden Globes, and Oscars over the years to predict the potential winners for the upcoming Oscars ceremony. We employ the concepts of Jaccard and cosine similarity in Python to make these predictions.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Oscars is one of the most highly anticipated events in the film industry, and predicting the winners can be both exciting and challenging. Our project aims to leverage the historical data of various awards, including SAG and Golden Globes, to identify similarities in winners' patterns across these ceremonies. By utilizing Jaccard and cosine similarity measures, we can estimate which nominees are most likely to emerge victorious at the upcoming Oscars.

## Methodology
1. **Data Collection**: We gather historical data from past [Oscars](https://www.kaggle.com/datasets/unanimad/the-oscar-award), [SAG](https://www.kaggle.com/datasets/unanimad/screen-actors-guild-awards), and [Golden Globes](https://www.kaggle.com/datasets/unanimad/golden-globe-awards) ceremonies, including nominees and winners.
2. **Preprocessing**: We preprocess the collected data to ensure consistency and compatibility across different datasets.
3. **Similarity Analysis**: Using Python, we calculate the Jaccard and cosine similarity scores between the winners of different awards over the years.
4. **Prediction**: Based on the calculated similarities, we predict the potential winners for each category at the upcoming Oscars.

## Installation
To set up the environment for running this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/oscars-2024-winners-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd oscars-2024-winners-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Contributing
Contributions to this project are welcomed and appreciated. If you have any suggestions, feature requests, or bug reports, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
