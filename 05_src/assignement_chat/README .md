# patent search agent 

This project implements a chatbot using Python with Gradio for patent search.

1. **Search the USTPO patent directory:**  
Uses PatentSearch API, then ranks semantically based on similarity with user query the top 10 patent-claim. 4omini is then called to summarize and pick the top 2 patents.

2. **Semantic Search Service:**  
   Utilizing Chroma semantic search and OpenAI embeddings, this service allows the user to upload his innovation idea in a pdf and compares it to the top 2 semantically.

3. **Send Email to Lawyer**  
   The user can add his email and authentificate with app password (2 step auth on google account).

The ipynb file go over most of the explanations.
Still not fully working: integrating service 3 into gradio.
