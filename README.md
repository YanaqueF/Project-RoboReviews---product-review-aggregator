# Project-RoboReviews---product-review-aggregator
Project Overview:

RoboReviews is an AI-powered system that simplifies the analysis of large-scale product reviews, transforming unstructured data into actionable insights. By combining machine learning models and generative AI, RoboReviews provides businesses and consumers with summarized reviews, sentiment trends, and ranked product recommendations, making decision-making faster and more informed.

Problem Statement:

Modern consumers face decision fatigue due to the overwhelming number of online product reviews. Meanwhile, businesses struggle to extract meaningful insights from customer feedback at scale. RoboReviews bridges this gap by:

Classifying sentiments to understand customer opinions.

Grouping reviews into meta-categories for better organization.

Generating concise summaries and blog posts to guide consumers.

Workflow:

Data Preprocessing:

Cleaned raw review data to remove noise (e.g., duplicates, special characters).

Tokenized text for downstream tasks.

Model 1: Sentiment Analysis

Classified reviews as positive, neutral, or negative using Logistic Regression.

Handled class imbalance with SMOTE (Synthetic Minority Oversampling Technique), worsend the accuracy.

Model 2: Clustering for Product Categorization

Grouped reviews into 4 meta-categories (e.g., Tablets, Ebook Readers, Smart Speakers) using K-Means clustering.

Merged overlapping clusters for better interpretability.

Model 3: Generative Summarization

Applied N-shot prompting with generative AI models (e.g., Mistral, LLAMA) to generate summaries.

Tried to:
Highlighted key pros, cons, and overall conclusions for each category.

Output Generation:
Last part: Testing Model on a Fake Review, is still in ERROR
