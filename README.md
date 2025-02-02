# LLM-Semantic-Book-Recommender
This project involves building a book recommendation system that utilizes various NLP techniques like semantic search, text classification, and sentiment analysis. The goal is to recommend books based on user input queries, categorizing them into fiction and non-fiction, and sorting them based on the emotions or tones present in the books. A Gradio web application is used to present the system's results interactively.

# Overview
This project leverages Local HuggingFace models, ChromaDB, and Gradio to build an efficient recommendation system. All the steps, including data cleaning, vector search, text classification, sentiment analysis, and web application development, have been consolidated into a single Jupyter notebook (data-exploration.ipynb).

# Key Steps:
* Text Data Cleaning: The first step involves cleaning and preprocessing the text data to make it suitable for further analysis.
* Semantic (Vector) Search: Vector-based search performed using pre-trained embeddings to find the most similar books based on natural language queries.
* Text Classification: Used Zero-Shot Classification to classify books as "fiction" or "non-fiction," allowing users to filter recommendations by category.
* Sentiment Analysis: Using LLMs, the sentiment of the books is analyzed and extracted the emotions, enabling users to sort books based on tones like joy, suspense, sadness, etc.
* Web Application: Finally, a Gradio web application is created to allow users to get personalized book recommendations interactively based on the previous techniques.

# Technologies Used
* Python 3.11: The code for this project was developed using Python 3.11.
*	HuggingFace: Used for pre-trained models for text embeddings, zero-shot classification, and sentiment analysis.
*	ChromaDB: A vector database for storing book embeddings and enabling similarity search.
*	Gradio: Used for building the web application for user interaction.
*	pandas: For data manipulation and cleaning.
*	matplotlib and seaborn: For visualizing data distributions.
*	transformers: For utilizing pre-trained models and NLP functionalities.
*	kagglehub: A tool for downloading and managing datasets from Kaggle.
*	langchain-community: A framework for building NLP pipelines.
*	langchain-opencv: Used for image processing, if needed.
*	langchain-chroma: ChromaDB integration for semantic search and vector databases.
*	python-dotenv: For managing environment variables like API keys.
*	notebook, ipywidgets: For interactive widgets and notebook functionalities.
