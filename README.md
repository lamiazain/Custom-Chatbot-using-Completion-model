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
```
## Usage

### 1. Setting Up the Environment
1. Clone this repository:
    ```bash
    git clone https://github.com/your-repo-name/openai-custom-chatbot.git
    cd openai-custom-chatbot
    ```

2. Install the required Python dependencies:
    ```bash
    pip install openai pandas requests
    ```

3. Set up your OpenAI API Key as an environment variable:
    ```bash
    export OPENAI_API_KEY='your-api-key'
    ```

---

### 2. Running the Code
1. Open the Jupyter Notebook file `Project_2_Completion_Model.ipynb` in a Jupyter Notebook or Jupyter Lab environment.
2. Execute the cells sequentially to:
    - Fetch the dataset using the Wikipedia API.
    - Preprocess the dataset into a pandas `DataFrame`.
    - Integrate the dataset with the OpenAI completion model.
    - Query the chatbot and observe its performance on custom questions.

---

### 3. Sample Questions
You can test the chatbot by entering questions related to the dataset. For example:
- **Question 1**: *"What is Python used for?"*
- **Question 2**: *"Who created Python?"*

These demonstrate how the custom dataset enhances the chatbot's responses with contextually accurate and relevant information.

---

### Example Output
**Question 1**:  
**Input**: *"What is Python used for?"*  
**Response**: Python is a high-level programming language widely used for web development, data analysis, machine learning, and scientific computing.

**Question 2**:  
**Input**: *"Who created Python?"*  
**Response**: Python was created by Guido van Rossum in 1991.

## Contact

For questions, feedback, or collaboration opportunities, feel free to reach out:

- **Email**: [lamiahasan4@gmail.com](lamiahasan4@gmail.com)
- **GitHub**: [Github]([https://github.com/your-username](https://github.com/lamiazain))
- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/lamia-zain/)
