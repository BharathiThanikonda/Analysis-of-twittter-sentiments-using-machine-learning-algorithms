# Analysis of Twitter Sentiments using Machine Learning Algorithms

A comprehensive machine learning project for analyzing sentiment in Twitter data, implementing various classification algorithms to detect racist/sexist tweets.

## 📋 Project Overview

This project focuses on sentiment analysis of Twitter data using natural language processing techniques and multiple machine learning algorithms. The goal is to classify tweets as either containing hate speech (racist/sexist content) or being neutral/positive.

## 🎯 Objectives

- Perform exploratory data analysis on Twitter sentiment data
- Implement data preprocessing and text cleaning techniques
- Apply multiple machine learning algorithms for classification
- Compare model performance and accuracy
- Visualize data patterns and model results

## 📊 Dataset

The project uses Twitter sentiment data with the following structure:
- **Training Data**: Contains labeled tweets for model training
- **Test Data**: Used for model evaluation and prediction
- **Labels**: Binary classification (0 = Non-hate speech, 1 = Hate speech/racist/sexist)

## 🔧 Technologies Used

- **Python 3.x**
- **Libraries**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `matplotlib` & `seaborn` - Data visualization
  - `nltk` - Natural language processing
  - `scikit-learn` - Machine learning algorithms
  - `re` - Regular expressions for text processing

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/BharathiThanikonda/Analysis-of-twittter-sentiments-using-machine-learning-algorithms.git
```

2. Navigate to the project directory:
```bash
cd Analysis-of-twittter-sentiments-using-machine-learning-algorithms
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Open the Jupyter notebook:
```bash
jupyter notebook sentimentAnalysis.ipynb
```

## 📈 Project Structure

```
├── sentimentAnalysis.ipynb    # Main analysis notebook
├── train_tweets.csv          # Training dataset (not included in repo)
├── test_tweets.csv           # Test dataset (not included in repo)
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies
```

## 🔍 Analysis Pipeline

1. **Data Loading & Exploration**
   - Load training and test datasets
   - Explore data dimensions and structure
   - Analyze label distribution

2. **Data Preprocessing**
   - Text cleaning and normalization
   - Removal of special characters, URLs, and mentions
   - Tokenization and stop word removal
   - Feature extraction using TF-IDF

3. **Model Implementation**
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Naive Bayes
   - Random Forest
   - Other ensemble methods

4. **Model Evaluation**
   - Accuracy metrics
   - Precision, Recall, and F1-score
   - Confusion matrix analysis
   - Cross-validation results

5. **Visualization**
   - Data distribution plots
   - Word clouds for different sentiment categories
   - Model performance comparisons
   - Feature importance analysis

## 📊 Key Features

- **Comprehensive EDA**: Detailed exploratory data analysis with visualizations
- **Text Preprocessing**: Advanced text cleaning and feature engineering
- **Multiple ML Models**: Implementation and comparison of various algorithms
- **Performance Metrics**: Detailed evaluation using multiple metrics
- **Visualization**: Clear charts and plots for better understanding

## 🎯 Results

The project demonstrates:
- Effective preprocessing techniques for social media text
- Comparative analysis of different machine learning algorithms
- Insights into patterns of hate speech in social media
- Model performance optimization strategies

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Bharathi Thanikonda**
- GitHub: [@BharathiThanikonda](https://github.com/BharathiThanikonda)

## 🙏 Acknowledgments

- Thanks to the Twitter API for providing access to social media data
- NLTK team for excellent natural language processing tools
- Scikit-learn community for comprehensive machine learning library
- Matplotlib and Seaborn for powerful visualization capabilities

## 📞 Contact

If you have any questions or suggestions, feel free to reach out!

---

⭐ **If you found this project helpful, please give it a star!** ⭐
