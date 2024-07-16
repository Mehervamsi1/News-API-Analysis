# News-API-Analysis

Project Overview

Objective:
The primary goal was to explore and understand trends across different news topics through automated analysis of text data.

Key Steps and Techniques Used:

Data Collection:

Utilized the NewsAPI to gather approximately 100 articles per topic across 15 predefined categories. Topics ranged from Technology and Science to Politics and Entertainment.

Data Preprocessing:

Cleaned and prepared the collected text data:

Removed irrelevant characters, HTML tags, and non-alphabetic characters.
Tokenized sentences into words and removed stopwords (commonly occurring words with little semantic value).
Applied lemmatization to normalize words to their base or dictionary form (e.g., "running" to "run").

Topic Modeling (LDA):

Implemented Latent Dirichlet Allocation (LDA), a probabilistic model, to uncover latent topics within the corpus.
Each topic was represented as a distribution of words, enabling interpretation and labeling of topics like "Technology," "Science," etc.

Visualization:

Developed visualizations to aid in understanding and presenting the results:

Bar Graphs: Displayed the top words associated with each topic derived from LDA modeling.
Word Clouds: Visualized the most frequent words in the entire corpus and per identified topic, providing intuitive insights into prominent themes.

Interactive Dash Application:

Created a Dash web application allowing users to:

View a table of frequent words extracted from the corpus.
Select a word to retrieve related news articles where the word appears prominently.
Displayed article summaries and links to further explore relevant content.

Conclusion

This project demonstrated effective utilization of NLP techniques to extract meaningful insights from a large corpus of news articles. By leveraging tools like LDA for topic modeling and creating interactive visualizations, the project provided a systematic approach to understanding and exploring complex textual data. The combination of automated data collection, rigorous preprocessing, advanced modeling, and intuitive visualization through Dash contributed to a comprehensive analysis of news trends across diverse topics. This approach not only enhanced understanding but also showcased the potential of NLP in extracting valuable insights from vast textual datasets.
