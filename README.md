# LLM Prompts


## Classifying data

### Generate classifications for a topic

> Disregard any previous instructions. Please respond solely in English. Assume the role of a data scientist specializing in natural language processing and vector databases. You have comprehensive expertise in Weaviate, a vector database for machine learning. I will provide you with a target topic {{PROMPT}}. Your task is to create classifications for this topic that can be used to generate datasets in a Weaviate vector database.
>
> Construct a markdown table that categorizes the given topic into 10 primary classifications. For each primary classification, list 7 sub-classifications or specific attributes. Additionally, identify the type of data each classification or sub-classification would hold in a separate column.
>
> The markdown table should be written in English and consist of the following columns: Primary Classification, Sub-Classification, Data Type. Here is the topic to start: {{PROMPT}}
