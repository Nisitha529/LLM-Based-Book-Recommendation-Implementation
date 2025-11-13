# LLM-Based-Book-Recommendation-Implementation
A book recommendation mechanism which is powered with LLMs is included in this repository. Different jupiter notebooks and python files had been implemented to achieve this objective. The following points describe the key steps of this project.

- Text Data Cleaning - Removing the skewed, and insufficient data rows.
- Semantic Vector Search - This step contains a creation of a vector database that would help the users to find the best matching book recommendations for their intended queries.
- Text classification - Under this step, categories of that books would fall had been adjusted. These adjustments were made to reduce the categories with very few book count or add meaningful categories that would support the user in a positive way. The zero-shot classification has been utilized here.
- Sentiment Analysis - Used LLMs to extract their tones, so users can get the help additional feature to reach better and solid recommendations from the model.
- Web Application Creation - Using the Gradio, a user friendly web interface has been created.

The following key dependecies had been used in this implementation.
 1. kagglehub
 2. langchain-community
 3. laghcain-opencv
 4. langhcain-chroma
 5. transformers
 6. gradio

