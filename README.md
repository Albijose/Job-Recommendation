# Job-Recommendation
TF-IDF VECTORIZATION AND COSINE SIMILARITY
AI-Based Job Recommendation System Using NLP and Cosine Similarity
Description:

This project is an intelligent job recommendation system designed to match job seekers with relevant job listings based on their profile. Using Natural Language Processing (NLP) techniques and cosine similarity, it recommends top job postings from a dataset of over 500,000 listings.

🔍 Key Features:
Input: User profile includes experience, salary, location, work type, skills, and education.

Data Processing: Job listings are cleaned, normalized, and experience/salary ranges are split for filtering.

Vectorization: TF-IDF vectorization converts job descriptions and user input into numerical form.

Matching: Cosine similarity measures textual similarity between user input and job descriptions.

Filtering: Jobs are filtered based on profile fit (e.g., experience/salary range).

Ranking: Jobs are ranked by similarity scores, and the top matches are recommended.

🛠 Techniques Used:
Data Preprocessing (handling missing values, text normalization)

TF-IDF Vectorization

Cosine Similarity

Pandas, NumPy, Scikit-learn for implementation

📊 Output:
Returns the top 10 job matches with similarity scores

Dataset link  - https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset
