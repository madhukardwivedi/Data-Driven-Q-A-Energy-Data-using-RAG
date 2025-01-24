# Data-Driven-Q\&A-Energy-Data-using-RAG
EnergyQnA is a data-driven question-answering platform designed to deliver analytical insights from energy datasets. Using advanced technologies such as FAISS vector search, LLMs (Large Language Models), and semantic embeddings, this project transforms raw energy data into meaningful answers to complex queries.


## How to Run the Project

### GUI Interface:
To launch the interactive GUI for the project, use the following command in your terminal:

```bash
!streamlit run app1.py --server.port 8501
```
### GUI Interface:
This will start the Streamlit app on port `8501`. Open your browser and navigate to [http://localhost:8501](http://localhost:8501) to interact with the application.

### Step-by-Step Detailed Code:
For a detailed, step-by-step implementation of the code, you can run the Jupyter Notebook provided in the repository. This allows you to understand the underlying processes, debug, and experiment with different queries interactively.

### Important Note:
This project uses **OpenAI's GPT-4o-MINI** model for natural language understanding and analytical question answering. Please replace the `open_ai_api` variable in the code with your actual OpenAI API key to ensure functionality.

```python
# Replace with your OpenAI API key
open_ai_api = "your_actual_openai_api_key"
```
