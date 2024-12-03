# OpenAI Custom Chatbot

## Description

This project demonstrates the creation of a **custom chatbot using OpenAI's API**. The chatbot integrates a custom dataset sourced from the **Wikipedia API** and leverages OpenAI's completion model to generate intelligent responses. 

### Features
- **Custom Dataset Selection**:
  - We selected a dataset from Wikipedia API to provide high-quality, reliable information for the chatbot.
  - Explained the reasoning behind choosing this dataset, ensuring its relevance and credibility.
  
- **Dataset Integration**:
  - The dataset was processed into a pandas `DataFrame` format, making it efficient for query-based operations.
  - Integrated this custom dataset seamlessly with the chatbot query handling code.

- **OpenAI API Integration**:
  - The OpenAI API was utilized to access the **completion model**, ensuring accurate and context-aware responses.

- **Performance Demonstration**:
  - We designed and tested two sample questions to showcase the chatbot's capabilities with the custom prompt.

---

## Installation

### Prerequisites
- Python 3.7 or higher
- An active OpenAI API Key

### Required Libraries
Install the following dependencies using pip:

```bash
pip install openai==0.28
pip install tiktoken
