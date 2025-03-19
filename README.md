# Restaurant Recommendation System using Machine Learning

This project is a **Restaurant Recommendation System** built using **Machine Learning**. It utilizes the **Cosine Similarity** approach to recommend top 10 restaurants based on user preferences. The system is developed using the publicly available **Zomato Dataset**.

## Features
- Provides **Top 10 Restaurant Recommendations**.
- Displays essential details such as **Name**, **Rating**, and **Cost**.
- Efficient similarity calculation using **Cosine Similarity**.
- Comprehensive **Data Preprocessing** including text cleaning and column removal.

## Dataset
- The dataset used is a publicly available **Zomato Dataset**.
- It contains various features like restaurant name, location, cuisine, rating, cost, and other relevant information.

## Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-Learn**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

## Steps Performed
1. **Data Cleaning:**
    - Removed unnecessary columns.
    - Handled missing and duplicate data.
2. **Text Preprocessing:**
    - Applied techniques like tokenization, removing stopwords, and lowercasing.
3. **Feature Extraction:**
    - Utilized **TF-IDF Vectorization** to convert text data into numerical format.
4. **Similarity Calculation:**
    - Used **Cosine Similarity** to find similar restaurants.
5. **Recommendation Generation:**
    - Displayed top 10 restaurant recommendations based on similarity.

## Installation
1. Clone the repository:
    ```bash
    https://github.com/24kshah/Restaurant-Recommendation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd restaurant-recommendation-system
    ```
3. Open the project using Google Colab by uploading the `.ipynb` file.

## Usage
1. Run the notebook cells step-by-step in **Google Colab**.
2. Enter your preferred restaurant or cuisine.
3. View the top 10 recommended restaurants with their ratings and cost.

## Project Structure
```bash
📦 Restaurant-Recommendation-System
├── data
│   └── zomato.csv
├── restaurant_recommendation.ipynb
├── requirements.txt
├── README.md
```

## Conclusion
This project is a simple and efficient restaurant recommendation system using machine learning. It offers personalized restaurant suggestions based on user preferences using Cosine Similarity.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

