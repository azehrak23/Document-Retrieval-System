
# Document-Retrieval-System

Natural language processing (NLP) techniques are used in this Python script to create a document retrieval and summarization system. The script is intended to handle a collection of documents related to global economics and provides a simple yet effective method for retrieving relevant documents based on user queries and producing concise summaries.

## Features

Inverted Index Generation: The script generates an inverted index for each word in the provided document collection. This index is then used to retrieve relevant documents for a given query in an efficient manner.

Document Retrieval: The system retrieves documents that are most relevant to the user's query using the inverted index, providing a quick overview of the relevant content.

Automatic Summarization: The script generates summaries for the retrieved documents by identifying key sentences based on word frequency. The goal of this summarization process is to extract the most important information from the documents.

## How to use

Install Dependencies: Ensure that all required dependencies, including NLTK, are installed. To download required resources, use the nltk.download commands provided.

Define Document Collection: Add your own documents and descriptions to the document_collection dictionary.

Execute the Script: When prompted, run the script and enter your query. After that, the system will retrieve relevant documents and generate a summary.


## Software Dependencies

Before running the script, make sure you have the following software installed on your system:

**Python**: Python is used to write the script. Python 3.6 or later must be installed.

_**pip install python==3.8**_

**NLTK Library**:The Natural Language Toolkit (NLTK) Library is used by the script for tokenization and stopword handling. Install NLTK and download all required resources.

_**pip install nltk**_

Download NLTK resources:

_**import nltk**_

_**nltk.download('punkt')**_

_**nltk.download('stopwords')**_


