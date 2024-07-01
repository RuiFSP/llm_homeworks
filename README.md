# llm_homeworks
This is a repository where i'll save my work related to llm-zoomcamp from DataTalksClub

# 01-Intro: LLM and RAG Introduction

In the `01-intro` module, we embarked on an exploratory journey into the realms of Large Language Models (LLM) and Retrieval-Augmented Generation (RAG). This module was designed to provide a foundational understanding of these advanced AI concepts and their practical applications. Through a series of study sessions and a homework assignment, we delved into the mechanics of LLMs and RAG, learning how to implement a simple RAG pipeline to answer questions based on FAQ documents from various Zoomcamp courses.

## Study Sessions

During the study sessions, we covered several key topics:

- **Introduction to LLM and RAG**: We explored what LLMs and RAG are, including their architecture and how they can be utilized to enhance question-answering systems.
- **Preparing the Environment**: We prepared our development environment by installing necessary libraries and tools, ensuring we had everything needed to work with LLMs and RAG.
- **Retrieval with Elasticsearch and Minsearch**: We learned how to use Elasticsearch for indexing documents and performing searches, which is crucial for the RAG pipeline. Additionally, we explored the implementation of Minsearch, a custom indexing solution, to understand the intricacies of building a search engine tailored to our specific needs. Elasticsearch, a powerful open-source search and analytics engine, enabled us to efficiently store, search, and analyze large volumes of data in real time. The addition of Minsearch allowed us to experiment with custom indexing strategies, offering a hands-on experience in enhancing search capabilities beyond conventional methods.
- **Generation with OpenAI**: We experimented with invoking the OpenAI API to generate answers based on the prompts built from our search results.
- **OpenAI API Alternatives**: We also explored alternatives to the OpenAI API for those interested in running LLMs locally or seeking different options.

### Why a Custom Approach Is Beneficial

Utilizing a custom indexing approach like Minsearch alongside Elasticsearch offers several advantages:

- **Tailored Performance**: Custom indexing allows for optimization based on the specific data structures and query patterns of our application, potentially improving search performance and relevance.
- **Learning Opportunity**: Building and integrating a custom search solution provides invaluable insights into the mechanics of search engines, enhancing our understanding and skills in this area.
- **Flexibility**: A custom approach enables us to implement unique features and optimizations that might not be readily available in off-the-shelf solutions, allowing for more creative and effective use of data.
- **Cost Efficiency**: For certain use cases, a custom indexing solution can be more cost-effective, especially when dealing with specific scalability requirements or when needing to optimize for particular types of queries.

Incorporating both Elasticsearch and Minsearch in our project not only broadened our technical toolkit but also provided a comprehensive learning experience in handling and querying large datasets effectively.

## Homework

The homework assignment for this module involved:

- Indexing FAQ documents from DE Zoomcamp, ML Zoomcamp, and MLOps Zoomcamp using Elasticsearch. This allowed us to create a robust and scalable Q&A system.
- Creating a Q&A system capable of answering questions about these documents, leveraging the concepts and tools we learned during the study sessions, especially the integration of Elasticsearch for retrieval and OpenAI for generation.

This module served as a practical introduction to working with LLMs and RAG, setting the stage for more advanced topics in subsequent modules.

For more detailed information on the study sessions and homework, refer to the [01-intro_study README.md](01-intro_study/README.md) and [homework01.ipynb](01-intro_homework/homework01.ipynb).