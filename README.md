# Coin Detection Project

## Description
This project aims to detect coins using machine learning techniques. The dataset used for this project is available on Kaggle. The project utilizes various libraries and techniques including:
- **OpenCV** (`cv2`): For image processing and computer vision tasks.
- **TensorFlow**: For building and training machine learning models.
- **NumPy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.

## Table of Contents
- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Workflows](#workflows)
- [Contact](#contact)

## Dataset
The dataset can be found at the following link:
[Coin Detection Dataset](https://www.kaggle.com/datasets/pradhandebasish/indian-coin-detection)

## Installation
To install the necessary dependencies, run the following command:
```sh
pip install -r requirements.txt
```

## Execution
To Run the app simply run the following command:
```sh
streamlit run main.py
```

## Usage
To run the project, follow these steps:
1. Update [`config.yaml`](command:_github.copilot.openSymbolFromReferences?%5B%22config.yaml%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22r%3A%5C%5CThe-Grand-Complete-Data-Science-Materials-main%5C%5CML%20Projects%5C%5CIndian-Coin-Detection%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fr%253A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%2520Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22path%22%3A%22%2Fr%3A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%20Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A25%2C%22character%22%3A10%7D%7D%5D%5D "Go to definition")
2. Update [`secrets.yaml`](command:_github.copilot.openSymbolFromReferences?%5B%22secrets.yaml%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22r%3A%5C%5CThe-Grand-Complete-Data-Science-Materials-main%5C%5CML%20Projects%5C%5CIndian-Coin-Detection%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fr%253A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%2520Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22path%22%3A%22%2Fr%3A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%20Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A26%2C%22character%22%3A10%7D%7D%5D%5D "Go to definition") (Optional)
3. Update [`params.yaml`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fr%3A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%20Projects%2FIndian-Coin-Detection%2Fparams.yaml%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "r:\The-Grand-Complete-Data-Science-Materials-main\ML Projects\Indian-Coin-Detection\params.yaml")
4. Update the entity
5. Update the configuration manager in `src/config`

## File Structure
```
Coin-Detection-Project/
├── data/
│   ├── raw/
│   ├── processed/
├── notebooks/
├── src/
│   ├── config/
│   ├── data/
│   ├── models/
│   ├── utils/
├── tests/
├── config.yaml
├── params.yaml
├── secrets.yaml
├── requirements.txt
└── README.md
```

## Workflows
1. Update [`config.yaml`](command:_github.copilot.openSymbolFromReferences?%5B%22config.yaml%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22r%3A%5C%5CThe-Grand-Complete-Data-Science-Materials-main%5C%5CML%20Projects%5C%5CIndian-Coin-Detection%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fr%253A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%2520Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22path%22%3A%22%2Fr%3A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%20Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A25%2C%22character%22%3A10%7D%7D%5D%5D "Go to definition")
2. Update [`secrets.yaml`](command:_github.copilot.openSymbolFromReferences?%5B%22secrets.yaml%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22r%3A%5C%5CThe-Grand-Complete-Data-Science-Materials-main%5C%5CML%20Projects%5C%5CIndian-Coin-Detection%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fr%253A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%2520Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22path%22%3A%22%2Fr%3A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%20Projects%2FIndian-Coin-Detection%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A26%2C%22character%22%3A10%7D%7D%5D%5D "Go to definition") (Optional)
3. Update [`params.yaml`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fr%3A%2FThe-Grand-Complete-Data-Science-Materials-main%2FML%20Projects%2FIndian-Coin-Detection%2Fparams.yaml%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "r:\The-Grand-Complete-Data-Science-Materials-main\ML Projects\Indian-Coin-Detection\params.yaml")
4. Update the entity
5. Update the configuration manager in `src/config`

## Contact
- **LinkedIn**: [linkedin.com/in/rayyan-ahmed9477](https://www.linkedin.com/in/rayyan-ahmed9477/)
- **Email**: [rayyanahmed265@yahoo.com](mailto:rayyanahmed265@yahoo.com)

