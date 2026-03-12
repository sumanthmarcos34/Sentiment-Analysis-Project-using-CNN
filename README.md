# Sentiment Analysis on US Airline Reviews using CNN

## Overview
This project performs sentiment analysis on US airline tweets using a Convolutional Neural Network (CNN). The system automatically classifies tweets into **positive**, **negative**, or **neutral** sentiments. The goal is to analyze customer feedback and identify patterns related to airline service quality and customer satisfaction.

---

## Features
- Sentiment classification of airline tweets  
- Deep learning model using CNN  
- Data preprocessing and text cleaning  
- Visualization of training accuracy and loss  
- Analysis of customer opinions from social media  

---

## Dataset
The project uses the **Twitter US Airline Sentiment Dataset**, which contains around **14,000+ tweets** related to six major US airlines. Each tweet is labeled as positive, negative, or neutral.

Dataset information includes:
- Tweet text
- Airline name
- Sentiment label
- Additional metadata related to tweets

---

## Technologies Used
- **Programming Language:** Python  
- **Deep Learning:** TensorFlow / Keras  
- **Libraries:** NumPy, Pandas, Scikit-learn  
- **Visualization:** Matplotlib  
- **Dataset Source:** Kaggle (US Airline Twitter Sentiment Dataset)

---

## Model Architecture
The CNN model used in this project includes:

- Embedding Layer for word representation  
- 1D Convolution Layer to capture sentiment patterns  
- Max Pooling Layer for feature selection  
- Dropout Layer to prevent overfitting  
- Dense Layer with Softmax for sentiment classification  

---

## Project Structure
```
Sentiment-Analysis-Project-using-CNN
│
├── Sentiment Analysis.ipynb     # Jupyter notebook implementation
├── Sentiment Analysis.py        # Python script
├── Tweets.csv                   # Dataset
├── database.sqlite              # Additional dataset
├── Accuracy plot.jpg            # Training accuracy graph
├── Loss plot.jpg                # Training loss graph
└── README.md                    # Project documentation
```

---

## Installation

Clone the repository:

```
git clone https://github.com/sumanthmarcos34/Sentiment-Analysis-Project-using-CNN.git
```

Navigate to the project directory:

```
cd Sentiment-Analysis-Project-using-CNN
```

Install required libraries:

```
pip install tensorflow pandas numpy scikit-learn matplotlib
```

---

## Usage

Run the Python script:

```
python "Sentiment Analysis.py"
```

Or open the notebook:

```
Sentiment Analysis.ipynb
```

---

## Results
The CNN model successfully classifies tweets into sentiment categories.  
Typical performance results include:

- **Accuracy:** around 82% – 91%  
- **F1 Score:** above 0.85  

Training graphs such as **accuracy and loss plots** are included in the repository.

---

## Applications
- Social media opinion analysis  
- Customer feedback analysis  
- Brand reputation monitoring  
- Business intelligence insights  

---

## Author
**Sumanth R**  
CSE – Data Science  
ACS College of Engineering  

---

## License
This project is created for academic and research purposes.
