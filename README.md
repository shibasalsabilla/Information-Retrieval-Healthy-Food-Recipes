# Information-Retrieval-Healthy-Food-Recipes

This project aims to build an intelligent information retrieval (IR) system for healthy food recipes using a hybrid approach that combines BM25L, a lexical retrieval method, with MiniLM, a semantic embedding model. The dataset, scraped from EatingWell, consists of over 5,000 healthy recipes enriched with nutritional tags, instructions, and descriptions.

The system enhances search quality by applying Reciprocal Rank Fusion (RRF) to combine lexical and semantic scores, leading to improved precision and recall over individual methods. Evaluation on 60 user queries shows that the hybrid BM25L + MiniLM model consistently outperforms others, especially after fine-tuning.

This project demonstrates how combining traditional keyword matching with deep learning-based understanding can significantly improve the relevance and personalization of dietary information retrieval.

