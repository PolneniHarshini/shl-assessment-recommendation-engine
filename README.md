Assessment Recommendation Engine – SHL
Problem Statement

The objective of this project is to build an Assessment Recommendation Engine that recommends the most suitable SHL assessments based on a given job requirement.

Dataset

File name: Gen_AI Dataset.xlsx

The dataset contains:

Job requirements / hiring queries

SHL assessment names

Assessment URLs

Duration, skills, and role-related information

Approach

Load the Excel dataset using Pandas.

Preprocess the data by handling missing values.

Combine all relevant text fields into a single column.

Convert text data into numerical form using TF-IDF Vectorization.

Compute similarity using Cosine Similarity.

Recommend the top matching SHL assessments for a given job query.

Technologies Used

Python

Pandas

Scikit-learn

Google Colab

Why This Approach

Simple and explainable

No black-box machine learning

Business-aligned with SHL’s product recommendation use case

Easy to scale with new assessments

Sample Input

“I am hiring a Java developer with good communication skills. Test duration around 40 minutes.”

Sample Output

Core Java Entry Level

Interpersonal Communication

Java 8 Assessment

Conclusion

This recommendation engine helps recruiters quickly identify the most relevant SHL assessments, improving hiring efficiency and decision-making.
