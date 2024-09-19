# Search Engine and Product Recommendation System on Amazon Data

This project is a **Search Engine and Product Recommendation System** built using **Pandas**, **NLTK**, **Scikit-learn**, and **Streamlit**. The system allows users to input a product name and get the top recommendations based on **cosine similarity** of TF-IDF vectors of product titles and descriptions from Amazon data.

## Features
- **Product Search**: Search for Amazon products using product names.
- **Recommendation System**: Provides top 10 similar products based on the search query.
- **Interactive Web App**: Built using Streamlit for an easy-to-use interface.
- **Cosine Similarity**: Uses TF-IDF and cosine similarity for matching products.
- **Natural Language Processing (NLP)**: Tokenization and stemming of product titles and descriptions using NLTK.

## Demo

IMAGE
![image](https://github.com/user-attachments/assets/964b70a7-78d9-48bd-a8ee-71eed9f7f7d3)


## Usage

1. Prepare the Dataset: Ensure the ```amazon_product.csv``` file is present in the project directory. The file should contain columns like ```Title``` and ```Description``` of the products.

2. Run the App: Run the following command in the terminal to start the Streamlit web application:

```
streamlit run app.py
```
3. Search for Products:
- Enter a product name in the search bar and click the "Search" button.
- The top 10 most similar products will be displayed with their titles, descriptions, and categories.

## Dataset

The dataset (```amazon_product.csv```) should include the following columns:

- ```Title:``` The title of the product.
- ```Description:``` The description of the product.
- ```Category:``` The product category.
- ```id (optional):``` Product ID, if available.

## Future Enhancements

- Add more advanced NLP techniques like lemmatization.
- Extend the dataset with more product details.
- Include user ratings and reviews for better recommendations.
